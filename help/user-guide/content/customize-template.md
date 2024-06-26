---
title: Build a custom template
description: Learn how to build a custom template for GenStudio.
feature: Content Hub
level: Intermediate
---

# Build a custom template

While templates provide a base structure, you can adapt them to specific needs and preferences.

## Templating language

Use the _Handlebars_ templating language to construct your custom template. The Handlebars syntax uses regular text with double braces as content placeholders. For example, this tells GenStudio where to place the headline:

```handlebars
<div>{{ headline }}</div>
```

>[!TIP]
>
>See [`What is Handelbars?`](https://handlebarsjs.com/guide/#what-is-handlebars) in the _Handlebars language guide_.

## Template fields

GenStudio recognizes and interprets certain fields automatically based on the name, source, and role. Field content is either automatically generated, sourced from the brand references, or manually supplied, such as a link for the CTA.

Recognized field names:

| Field          | Role                   | Source     | Channel template     |
| -------------- | ---------------------- | ---------- | -------------------- |
| `subject`      | Subject                | generated  | -- |
| `pre_header`   | Pre header             | generated  | email       |
| `headline`     | Headline               | generated  | email<br>social ad<br>display ad |
| `body`         | Body copy              | generated  | email<br>social ad<br>display ad |
| `cta`          | Call to action         | generated  | email<br>social ad<br>display ad |
| `on_image_text`| On image text          | generated  | social ad |
| `brand_logo`   | Logo of selected brand | brand      | social ad<br>display ad |

A template cannot use more than 20 fields.

### Sections or groups

_Sections_ provide a way to inform GenStudio that fields belonging to the section require a high degree of coherence. You can use a prefix to group the fields.

- `group1_headline`
- `group1_body`

Each section can have only one of a field type. For example, Group 1 can only have one `group1_headline` field.

A template can include up to three sections.

### Emails

GenStudio automatically supplies the email template with a `subject` field, so do not use it in your email template. You can use the following generated fields:

- `pre_header`
- `headline`
- `body`
- `cta`

## Channel-specific guidance

Each channel has specific requirements and template customization opportunities.

Social media ads (Meta) and display ads use a background image with a text and brand logo overlay. Meta ad templates require an aspect ratio to scale the image, whereas display ads use height and width dimensions. You can provide only one image field in this case.
