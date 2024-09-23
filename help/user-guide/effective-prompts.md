---
title: Write effective prompts
description: Learn how to write effective prompts for Adobe GenStudio for Performance Marketers.
feature: Prompt, Generative AI, Brands Service, Personas Service, Products Service, Guidelines
exl-id: 0cd4db4f-d031-4c1f-a4e7-adc220f947fc
---
# Write effective prompts

Communicating with the generative AI is essential to working effectively in Adobe GenStudio for Performance Marketers.

GenStudio for Performance Marketers provides a generative AI prompt each time there is an opportunity to modify an asset. The components of an effective prompt should include descriptive language, examples, and information not provided through your configured guidelines.

As a best practice, supply GenStudio for Performance Marketers with your brand information using [guidelines](/help/user-guide/guidelines/overview.md), then you can fully leverage the generative AI to produce brand-aligned content experiences.

## Descriptive language

You can use natural language to articulate your ideas to create experiences. Your prompt guides the AI to generate channel content that is personalized and images that complement your vision. The more details that you provide, the greater the chance of producing an image or an experience that meets your needs. Use clear and descriptive language to provide as much detail as possible:

- For **images**, use words that describe ambiance, mood, color, composition, and style.
- For **copy**, use words that describe the audience, purpose, new feature descriptions, examples, and actions.

The following is a sample prompt that articulates information about your intent, target audience, and style.

```bash
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the generative AI capabilities of Photoshop and use references to natural imagery.
```

+++See sample results

![three generated emails](/help/assets/sample-email.png)

+++

## Prompt criteria

In GenStudio for Performance Marketers [[!DNL Create]](/help/user-guide/create/overview.md), you can use **[!UICONTROL Prompt criteria]** ([_Parameters_](/help/user-guide/create/overview.md#parameters) and a prompt) in the prompt area to add details through selection to improve the AI interpretation.

For [emails](/help/tutorials/create-email-experience.md), the prompt criteria might include adding [guidelines](/help/user-guide/guidelines/overview.md) in _Parameters_, upload of an asset to use in the email variants, and a descriptive prompt. For a [Meta ad](/help/tutorials/create-meta-ad.md), the prompt criteria might include a brand guideline in _Parameters_, selection or upload of an existing asset, settings related to images or assets such as aspect ratio, and a prompt. The real power begins with [configuring guidelines](/help/user-guide/guidelines/add-guidelines.md).

>[!NOTE]
>
>If guidelines are added in _Parameters_ in the prompt area, you do not need to include reference to them in your prompt. GenStudio for Performance Marketers leverages those [!DNL Brands], [!DNL Products], and [!DNL Personas] in content generation.

### Guidelines

GenStudio for Performance Marketers guidelines help the generative AI to personalize your asset composition. When presented with prompt criteria, you can choose a [[!DNL Brand]](/help/user-guide/guidelines/brands.md), a [[!DNL Persona]](/help/user-guide/guidelines/personas.md), and a [[!DNL Product]](/help/user-guide/guidelines/products.md) from your configured guidelines.

>[!TIP]
>
>You control how and when GenStudio for Performance Marketers uses your [!DNL Brand] guidelines. See [Guidelines](/help/user-guide/guidelines/overview.md) to learn how to configure and manage your brand guidelines.

### Structured prompts

In GenStudio for Performance Marketing, you enter one prompt that initiates content generation for an entire asset. For emails with multiple sections, you can structure your prompt to provide section-specific instructions. For instance, you can use specific verbiage in your prompt to instruct GenStudio for Performance Marketing to generate different content for each section in an email.

The structured prompt should:

- Use one of the following as a section name in both the structured prompt and email template:
  - Pod
  - Group
  - Section
  - Module

  For instance, you can use `moduleA` or `Group-body` as a section name in the prompt as long as the matching section name is also used in the template.

- Follow the recommended rules/structure. If the prompt structure does not adhere to the provided format, the prompt will apply to *all* email sections and will still facilitate content generation.
- Use section names as [defined in your email template](/help/user-guide/content/customize-template.md#sections-or-groups). When creating your structured prompt, your prompt references must match the section names coded in your email template.
- Be case insensitive. For instance, you can use `Pod` or `pod` in your email template and structured prompt.
- Reference the generic user prompt first, and then the section-specific directives.
- Use a colon, hyphen, comma, or other demarcation (`,:;#$!~|@=-%&*^_`) as a separation between the section name reference and directive. For instance, you can use the following as a section-specific prompt directive: `Pod1; Describe how to easily edit text and swap images.`

The following is a sample prompt that articulates the recommended prompt structure and leverages an email template that utilizes the identifying term `Pod` as in `Pod1`, `Pod2`, and `Pod3`.

```bash
Create a marketing email describing new features in suite of products for Creative Cloud.
  
Pod1: Describe how to easily edit text and swap images without switching to another application, all in just a few clicks.
Pod2: Describe how the AI Assistant for Acrobat enables you to gain document insights and access one-click summaries to enhance productivity.
Pod3: Describe the generative fill capabilities in Adobe Photoshop.
```

See [Customize template](/help/user-guide/content/customize-template.md#sections-or-groups).

## Try again

Prompting is an iterative process. If the results are not meeting your expectations, review your prompt and make some changes or add more details. Or, you can paste in sections from a campaign brief. You can even request that GenStudio for Performance Marketers avoid certain words, elements, or themes.

## Best practices

Some simple best practices for crafting effective prompts:

- Be specific and provide details about what to do and not do.
- Provide context using external references.
- Leverage GenStudio for Performance Marketers guidelines.
- Review and adjust guidelines regularly.
- Iterate and refine.
- Learn through experimentation.
