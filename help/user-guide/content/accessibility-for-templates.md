---
title: Create accessible templates
description: Build templates in Adobe GenStudio for Performance Marketers that are capable of reaching more of your audience and providing an optimal experience.
feature: Templates, Content
---

# Create accessible templates

Adobe is committed to providing an optimal experience for all audiences. See [Accessibility Initiatives at Adobe](https://www.adobe.com/trust/accessibility/initiatives.html) for further reading.

In GenStudio for Performance Marketers, you can upload assets and templates that enable content creation for a variety of experiences. Adhering to accessibility standards helps your content reach your maximum intended audience.

Use the following recommendations to prepare your templates using optimal accessibility standards.

## Alternative text

Provide text alternatives for non-textual content, such as images.

```html
<img alt="Collage of ideas, books, man holding giant pencil, computer" src="card-create-assets.png">
```

![Collage of ideas, books, man holding giant pencil, computer](../../assets/card-create-assets.png){width="400"}

## Link Purpose (Link Only)

Create clear link text that describes the purpose and location of the link.

For example, using link text such as "Click here" or "Read more" does not clearly describe the purpose of the link:

```html
<a href="product-site.html">Click here</a>
```

As a best practice, you should use text that clearly describes where the link goes. A better example might use the title of the link source and the purpose:

```html
<a href="product-site.html">Explore Product Site</a>
```

## Language

Many products and services use language in a creative or unique way. Avoid jargon, long sentences, and complex phrases. Use clear, concise, easy-to-read language compatible with your target audience.

- Use clear descriptions, inline definitions, or relatable examples when possible. It can be difficult to translate a unique vernacular.

- Spell out or link to a definition for the first instances of an acronym or abbreviation. It can be difficult to translate abbreviations.

- Use visual elements to supplement text or complex ideas when possible.
