---
title: Write effective prompts
description: Learn how to write effective prompts for GenStudio.
feature: Prompt, Brands Service
---

# Write effective prompts

Communicating with the Generative AI is essential to working effectively in GenStudio.

GenStudio provides a Generative AI prompt each time there is an opportunity to create or modify an asset. You can use natural language to articulate your ideas to create new experiences. The components of an effective prompt include using descriptive language, uploading brand guidelines, providing examples, and restrictions.

## Descriptive language

Your prompt guides the AI to generate images that complement your vision. The more details that you provide, the greater the chance of producing an image that meets your needs. Use clear and descriptive language to provide as much detail as possible. Use words that describe ambiance, mood, color, composition, and style.

For example, the following prompts use descriptive language:

- **Image prompts**

  - _An image of a serene beach scene at dawn with soft pastel colors, gentle waves, and a clear sky with a few scattered clouds, in a hand-drawn style._

  - _A bustling cityscape at night with neon lights, tall skyscrapers, and busy streets, in a hyper-realistic style._

  - _A fantasy forest with towering trees, glowing mushrooms, and mystical creatures, in a vibrant, colorful style._

- **Text prompt**

  - _Write an email that would help users understand the value of the Text-to-Vector Graphics feature. This email should inspire users to experiment with new GenAI features. What is Text-to-Vector Graphic? Text to Vector Graphic is a revolutionary Generative AI feature where you can quickly and more easily create scalable vector graphics with a simple text prompt, including icons, scenes, and patterns. How does Text-to-Vector Graphic work? With a placeholder graphic selected or not, in the Properties panel, taskbar, or Text-to-Vector Graphic panel, select a type, enter a prompt, and generate amazing art! Do not use "generate art" or "create art." Do not use the words "new" and "create" in the same sentence._

+++See the results of the sample text prompt:

![Example generated email](../assets/text-prompt.png){width="250"}

+++

## Prompt criteria

In the GenStudio [Create](./create/overview.md) mode, you can use **[!UICONTROL Prompt criteria]** to add details through selection to improve the AI interpretation. You can choose from your company references **[!DNL Brands]** or a specific **[!DNL Persona]** or **[!DNL Product]**, and use descriptive language to articulate certain characteristics.

Characteristics include traits and information extracted from References guidelines and Campaign briefs that you provide.

| Brand traits     | Brand information | Campaign information |
| ---------------- | ----------------- | -------------------- |
| Voice and tone   | Channel           | Marketing strategy   |
| Core values      | Audience          | Objective            |
| Frequent keywords | Product          | Key message          |
| Restrictions     | Concepts          | Themes               |
| Unique attributes | | |

See the References overview for details on uploading your brand guidelines.

## Channel guidelines

Each channel has certain inherent characteristics, or fragments, that you can call out in your prompt. For example, you can reference the subject line of an email or the headline of a social media asset.

>[!BEGINTABS]

>[!TAB Email]

Characteristics that influence email composition:

- `preheader`—A second subject line or email preview text.
- `subject`—A compelling and interesting title to summarize the content of an email.
- `headline`—A title or phrase to grab the reader's attention.
- `body`—Marketing content that includes message, links, and images.
- `cta` (Call to Action)—An instruction given to the reader that inspires a response. Usually one or two words, such as `Get started`.

Use a text prompt to generate marketing emails. The more details that you provide by way of characteristics, the more effective the results generated. The following prompt references the `subject` of the email:

```text
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the AI capabilities of Photoshop and use references to majestic, natural imagery. Use "Experience the power of generative AI in Photoshop" as the subject.
```

This prompt might include specific characteristics extracted from:

- Brand guidelines

  - **Audience**—users of Photoshop
  - **Product**—Photoshop
  - **Voice and tone**—motivation, imagery

- Campaign brief

  - **Objective**—encourage users to follow the tutorial
  - **Strategy**—target infrequent users, highlight AI capabilities

>[!TAB Image]

Characteristics that influence image composition:

|   | Description |
| -------------- | :---------- |
| **Background** | Set the stage by describing layouts, location, places |
| **Color and tone** |Specify color or color theme, palette, color interpretation and accessibility |
| **Composition** | Define objects, focal point, position, and depth-of-field, framing |
| **Lighting** | Describe how highlights and shadows affect different objects|
| **Restrictions** | List requirements or avoidances |

For better results, state your most important ideas first.

>[!TAB Social Ads]

Characteristics that influence social media composition:

- `headline`—A title or phrase to grab the reader's attention.
- `body`—Marketing content that includes message, links, and images.
- `cta` (Call to Action)—An instruction given to the reader that inspires a response.

| Site fragments      |
| ------------------- |
| Headline            |
| Body                |
| On-Image Text       |
| CTA (Call to Action) |
| Image               |

Facebook and Instagram...TBD

>[!TAB Display Ad]

Characteristics that influence display ad composition:

- `headline`—A title or phrase to grab the reader's attention.
- `body`—Marketing content that includes message, links, and images.
- `cta` (Call to Action)—An instruction given to the reader that inspires a response.
- `caption`—

TBD?

>[!ENDTABS]
