---
title: Write effective prompts
description: Learn how to write effective prompts for GenStudio.
feature: Prompt, Brands Service, Personas Service, Products Service
---

# Write effective prompts

Communicating with the generative AI is essential to working effectively in GenStudio.

GenStudio provides a generative AI prompt each time there is an opportunity to create or modify an asset. You can use natural language to articulate your ideas to create new experiences. The components of an effective prompt include using descriptive language, uploading [!DNL Brands] guidelines, providing examples, and referencing specific channel characteristics.

## Descriptive language

Your prompt guides the AI to generate images that complement your vision. The more details that you provide, the greater the chance of producing an image or an experience that meets your needs. Use clear and descriptive language to provide as much detail as possible:

- For **images**, use words that describe ambiance, mood, color, composition, and style.
- For **copy**, use words that describe audience, voice and tone, purpose, and actions.

### [!DNL Brands] and Campaign references

You can use descriptive language related to articulate certain Brand characteristics or campaing objectives with your prompt.

| Brand traits     | Brand information | Campaign information |
| ---------------- | ----------------- | -------------------- |
| Voice and tone   | Channel           | Marketing strategy   |
| Core values      | Audience          | Objective            |
| Frequent keywords | Product          | Key message          |
| Restrictions     | Concepts          | Themes               |
| Unique attributes | | |

For example, the following prompt might include specific characteristics that the AI can equate to your [!DNL Brands] guidelines:

```terminal
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the generative AI capabilities of Photoshop and use references to natural imagery. Use "Experience the power of generative AI in Photoshop" as the subject.
```

- Brand guidelines:

  - **Audience**—users of Photoshop
  - **Product**—Photoshop
  - **Voice and tone**—motivation, imagery
  - **Keyword**—AI
  - **Unique attributes**—infrequent

- Campaign brief:

  - **Objective**—encourage users to follow the tutorial
  - **Strategy**—target infrequent users, highlight AI capabilities

## Prompt criteria

In the GenStudio [[!DNL Create]](./create/overview.md) mode, you can use **[!UICONTROL Prompt criteria]** to add details through selection to improve the AI interpretation. For on-brand images, the prompt criteria might include general settings related to images, such as aspect ratio. For channels, you might select a template, or choose a [[!DNL Brand]](../user-guide/references/brands.md), a [[!DNL Persona]](../user-guide/references/personas.md), or [[!DNL Product]](../user-guide/references/products.md) from references guides.

## Channel characteristics

Each channel has certain inherent characteristics, or _fragments_, that you can reference in your prompt. For example, you can directly mention the subject line of an email or the headline of a social media asset.

Characteristics that influence channel asset composition:

| Channel fragments | Channel   | Description |
| ------------------| --------- | :---------- |
| Pre header        | email | A second subject line or email preview text |
| Subject           | email | A compelling and interesting title to summarize the content of an email |
| Headline          | email, social ads, display ads | A title or phrase to grab the reader's attention |
| Body              | email, social ads, display ads | Marketing content that includes message, links, and images |
| CTA               | email, social ads, display ads | (Call to Action) An instruction given to the reader that inspires a response. Usually one or two words, such as `Get started` |
| On image text     | social ads | TBD |

### Example: Use channel fragments

>[!BEGINTABS]

>[!TAB Email]

**Prompt for Email**

_Write an email in a conversational tone that thanks our customers for their recent purchase. Limit the Subject to 35 characters, but infer a sense of appreciation. In the body of the email, remind customers of our dedication to innovation and creativity. Ask kindly to complete a short survey of their purchase experience. Do not use contractions._

TBD

>[!TAB Social ads]

**Prompt for Social ads**

>[!TAB Display ads]

**Prompt for Display ads**

>[!ENDTABS]

## On-brand image characteristics

Images have certain inherent characteristics, or _fragments_, that you can call out in your prompt.

Characteristics that influence image composition:

| Image fragments    | Description | Examples |
| ------------------ | :---------- | -------- |
| **Background**     | Set the stage by describing layouts, location, places | <ul><li>Use bright, roomy environments</li></ul> |
| **Color and tone** | Specify color or color theme, palette, color interpretation and accessibility | <ul><li>Use soft tones for clothing</li><li>Use bold and vibrant colors to highlight data in charts</li></ul> |
| **Composition**    | Define objects, focal point, position, aspect ratio, framing, and depth-of-field | <ul><li>Illustrations should have a single, clear focal point</li></ul> |
| **Lighting**       | Describe how highlights and shadows affect different objects| <ul><li>Use natural light</li></ul> |
| **Restrictions**   | List requirements or avoidances | <ul><li>Avoid images that include children</li><li>Do not use clip art</li></ul> |

For better results, make sure that you articulate your most important ideas first:

_A woman in MyBrand attire using a digital tablet while standing indoors, use warm yellow and green tones_
