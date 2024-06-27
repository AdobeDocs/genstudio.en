---
title: Build a custom template
description: Learn how to build a custom template for GenStudio.
feature: Content Hub
level: Intermediate
---

# Build a custom template

While templates provide a base structure, you can adapt them to your specific needs and preferences.

## Templating language

Use the _Handlebars_ templating language to construct your custom template. The Handlebars syntax uses regular text with double braces as content placeholders. For example, the following line tells GenStudio where to place the headline:

```handlebars
<div>{{ headline }}</div>
```

>[!TIP]
>
>See [`What is Handelbars?`](https://handlebarsjs.com/guide/#what-is-handlebars) in the _Handlebars language guide_.

## Template fields

GenStudio recognizes and interprets certain fields automatically based on the name, source, and role. Field content is either generated, sourced from the brand references, or manually supplied, such as a link for the CTA. The maximum number of fields allowed in a template is twenty.

**Recognized field names**:

| Field          | Role                   | Source     | Channel template     |
| -------------- | ---------------------- | ---------- | -------------------- |
| `pre_header`   | Pre header             | generated  | email       |
| `headline`     | Headline               | generated  | email<br>social ad<br>display ad |
| `body`         | Body copy              | generated  | email<br>social ad<br>display ad |
| `cta`          | Call to action         | generated  | email<br>social ad<br>display ad |
| `on_image_text`| On image text          | generated  | social ad |
| `brand_logo`   | Logo of selected brand | brand      | social ad<br>display ad |

>[!IMPORTANT]
>
>GenStudio automatically supplies the email template with a `subject` field, so do not include the subject field in your email template.

### Sections or groups

_Sections_ provide a way to inform GenStudio that fields belonging to a section require a high degree of coherence. Establishing this relationship helps the AI to generate content that matches the creative elements in the section. A template can include up to three sections.

Use a prefix to group the fields of a section:

- `group1_headline`
- `group1_body`

Each section can have only one of a field type. For example, Group 1 can only have one `group1_headline` field.

### Background image

Social media ads (Meta) and display ads use a background image with a text and brand logo overlay. Meta ad templates require an `aspect ratio` to scale the image, whereas display ads use `height` and `width` dimensions. You can provide only one image field in this case.

## Template preview

Email templates sometimes contain special content that is not ...
