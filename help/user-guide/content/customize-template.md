---
title: Customize templates
description: Learn how to build a custom template for GenStudio.
level: Intermediate
feature: Templates
---

# Customize templates

You can adapt your HTML templates for GenStudio by using the _Handlebars_ templating language. The Handlebars syntax uses regular text with double braces as content placeholders. See [`What is Handlebars?`](https://handlebarsjs.com/guide/#what-is-handlebars) in the _Handlebars language guide_ to learn how to prepare your template.

## Content placeholders

GenStudio recognizes and interprets the content placeholders automatically based on the field name. Insert the field name using the Handlebars syntax into your template where you need GenStudio to place content.

For example, the following line tells GenStudio where to place the `headline`:

```handlebars
<div>{{ headline }}</div>
```

When using your custom template in the [[!DNL Create] workflow](../create/overview.md#create-capabilities), field content is either generated, sourced from your selected guidelines, or manually supplied. The maximum number of fields allowed in a custom template is twenty.

**Recognized field names**:

| Field          | Role                   | Channel template     |
| -------------- | ---------------------- | -------------------- |
| `pre_header`   | Pre header             | email       |
| `headline`     | Headline               | email<br>social ad |
| `body`         | Body copy              | email<br>social ad |
| `cta`          | Call to action         | email<br>social ad |
| `on_image_text`| On image text          | social ad |
| `image`        | Image                  | email<br>social ad |
| `brand_logo`   | Logo of selected brand | social ad |

>[!IMPORTANT]
>
>GenStudio automatically supplies the email template with a `subject` field, so do not include the subject field in your email template.

### Background image

When designing an ad for Meta, it is important to use a background image complemented by text and a brand logo overlay. To guarantee proper scaling of the image, Meta ad templates require specifying an `aspect ratio`. In this context, you can provide only one image field.

## Sections or groups

_Sections_ provide a way to inform GenStudio that fields belonging to a section require a high degree of coherence. Establishing this relationship helps the AI to generate content that matches the creative elements in the section. A template can include up to three sections.

Use a prefix to group the fields of a section:

- `group1_headline`
- `group1_body`

Each section can have only one of a field type. For example, Group 1 can only have one `group1_headline` field.

## Template preview

Email templates sometimes contain special content that is not necessary to preview in GenStudio. You can control the visibility of this content by using Built-in Helpers, which are special expressions in the Handlebars template language that help to perform certain actions.

The `_genStudio.browser` value is set when rendering a template, and the `genStudio.export` value is set when exporting a template. You may decide to include certain content at the top of the emails using a conditional wrapper, for example, when the template is used for export:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Another example may be to prevent the use of tracking codes when previewing an email template in GenStudio. This example shows how to add tracking parameters to links in the exported template, while keeping the preview links clean:

```handlebars
<a class="button" {{#if _genStudio.browser }}href="{{ link }}"{{/if}}{{#if _genStudio.export }}href="{{ link }}?trackingid=<%=getTrackingId()%>&mv=email"{{/if}} target="_blank">{{ cta }}</a>
```

## Static content

Email and Meta templates often link to images and CSS files hosted outside GenStudio. When GenStudio generates thumbnails for these templates or the experiences derived from them, it may ignore these external resources if they do not have the correct Cross-Origin Resource Sharing (CORS) headers.

To ensure that these resources are available during the thumbnail generation process, consider two options:

1. **Use CORS headers**: The host server must send responses with an `Access-Control-Allow-Origin` header set to `https://experience.adobe.com` value for production environments. This method allows GenStudio to access and include the resources.
1. **Use Data URLs**: Embed the external resources directly into the template using Data URLs. This method bypasses CORS restrictions and ensures that the resources are available during thumbnail generation.
