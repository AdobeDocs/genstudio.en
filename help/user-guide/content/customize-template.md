---
title: Customize templates
description: Learn how to build a custom template for GenStudio.
level: Intermediate
feature: Templates, Content
---

# Customize templates

You can adapt your HTML templates for GenStudio by using the _Handlebars_ templating language. The Handlebars syntax uses regular text with double braces as content placeholders. See [`What is Handlebars?`](https://handlebarsjs.com/guide/#what-is-handlebars) in the _Handlebars language guide_ to learn how to prepare your template.

<!-- This is for email. In the future, maybe use tabs to provide guidance for other template types.
-->If you do not have an HTML template ready to use in GenStudio, you can start by defining the structure of your email using HTML tags: `DOCTYPE`, `html`, `head`, and `body`. You can include CSS styles to customize the appearance of your email.

```html
<!DOCTYPE html>
<html>
<head>
    <title>Title</title>
    <style>
    </style>
</head>
<body>
</body>
</html>
```

See [Template examples](#template-examples).

>[!TIP]
>
>In the next few sections, add content placeholders for email fields, see example templates, hide unnecessary elements from preview, and manage links to static content. Once your template is ready, you can [upload it to GenStudio](use-templates.md#upload-a-template) and start generating personalized emails based on your custom template.

## Content placeholders

Within the head or body of the template, you can use Handlebars syntax to insert content placeholders where you require GenStudio to populate the email with actual content. GenStudio recognizes and interprets the content placeholders automatically based on the field name.

For example, you can use `{{ headline }}` to indicate where the headline of the email should be placed:

```handlebars
<div>{{ headline }}</div>
```

### Field names

The maximum number of fields allowed in a custom template is twenty.

#### Recognized field names

The following tables lists the field names that are recognized by GenStudio by population.

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
>GenStudio automatically supplies the email template with a `subject` field during the [!DNL Create] process, so it is not necessary to include the subject field in your email template.

#### Manual field names

All other field names are treated as manually populated fields. If you want a section to be editable, add double brackets around the section you want to edit.

> Example: ``{{customVariable}}`` (customVariable is the manually editable section)

### Background image

When designing an ad for Meta, it is important to use a background image complemented by text and a brand logo overlay. To guarantee proper scaling of the image, Meta ad templates require specifying an `aspect ratio`. In this context, you can provide only one image field.

## Sections or groups

_Sections_ inform GenStudio that fields belonging to a section require a high degree of coherence. Establishing this relationship helps the AI to generate content that matches the creative elements in the section.

Use a prefix of your choice in the field name to indicate a field is part of a section or group. 

For example, you may want to spotlight content that appears in a highlighted area:

- `spotlight_headline`
- `spotlight_body`

Each section can have only one of a field type. In the above example, the `spotlight` prefix can only have one `spotlight_headline` field.

A template can include up to three sections:

- `headline`
- `body`
- `spotlight_headline`
- `spotlight_body`
- `news_headline`
- `news_body`

GenStudio understands that `spotlight_headline` is more closely related to `spotlight_body` than to `news_body`.

## Template examples

+++Example: Template with one section

The following is a basic example of an HTML template for email with one section. The head contains simple, inline CSS for styling. The body contains a `pre-header`, `headline`, and `image` placeholder for use by GenStudio to inject content during the email generation process.

```handlebars {line-numbers="true" highlight="13"}
<!DOCTYPE html>
<html>
<head>
    <title>Adobe</title>
    <style>
        .container {
            width: 100%;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>{{ pre_header }}
    <div class="container">
        <h1>{{ headline }}</h1>
        <p><img alt="{{ headline }}"
                src="{{ image }}"
                width="600" height="600"
                border="0"/></p>
        <p>{{ body }}</p>
    </div>
</body>
</html>
```

+++

+++Example: Template with multiple sections

The following is the same HTML template in the example above, but with two more sections. The head contains inline CSS for styling a pod. The body uses two pods with content placeholders using a prefix.

```handlebars {line-numbers="true" highlight="33"}
<!DOCTYPE html>
<html>
<head>
    <title>Adobe</title>
    <style>
        .container {
            width: 100%;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
        .pod {
            background-color: #f8f8f8;
            margin: 10px;
            padding: 20px;
            border-radius: 5px;
        }
        .pod h2 {
            color: #333;
        }
        .pod p {
            color: #666;
        }
    </style>
</head>
<body>{{ pre_header }}
    <div class="container">
        <h1>{{ headline }}</h1>
        <p><img alt="{{ headline }}"
                src="{{ image }}"
                width="600" height="600"
                border="0"/></p>
        <p>{{ body }}</p>
        <div class="pod">
            <h2>{{ pod1_headline }}</h2>
            <p>This is Pod 1 content.</p>
        </div>
        <div class="pod">
            <h2>{{ pod2_headline }}</h2>
            <p>This is Pod 2 content.</p>
        </div>
    </div>
</body>
</html>
```

+++

## Template preview

Control the visibility of special content by using Built-in Helpers (special expressions in the Handlebars template language that perform certain actions). For example, you can add tracking parameters to links in the exported template while keeping the preview links clean.

The `_genStudio.browser` value is set when rendering a template, and the `genStudio.export` value is set when exporting a template. You may decide to include certain content at the top of the emails using a conditional wrapper, for example, when the template is used for export:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Another example may be to prevent the use of tracking codes when previewing an email template in GenStudio. This example shows how to add tracking parameters to links in the exported template, while keeping the preview links clean:

```handlebars
<a class="button" {{#if _genStudio.browser }}
   href="{{ link }}"{{/if}}{{#if _genStudio.export }}
   href="{{ link }}?trackingid=<%=getTrackingId()%>&mv=email"{{/if}}
   target="_blank">{{ cta }}</a>
```

## Static content

Email and Meta templates often link to images and CSS files hosted outside GenStudio. When GenStudio generates thumbnails for these templates or the experiences derived from them, it may ignore these external resources if they do not have the correct Cross-Origin Resource Sharing (CORS) headers.

To ensure that these resources are available during the thumbnail generation process, consider two options:

1. **Use CORS headers**: The host server must send responses with an `Access-Control-Allow-Origin` header set to `https://experience.adobe.com` value for production environments. This method allows GenStudio to access and include the resources.
1. **Use Data URLs**: Embed the external resources directly into the template using Data URLs. This method bypasses CORS restrictions and ensures that the resources are available during thumbnail generation.
