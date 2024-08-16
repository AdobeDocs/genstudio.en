---
title: Get started with Adobe GenStudio for Performance Marketers
description: Learn how to set up your GenStudio for Performance Marketers to generate new brand-aligned marketing content.
level: Beginner
feature: Prompt, Brands Service, Personas Service, Products Service, Generative AI, Guidelines
---

# Get started with Adobe GenStudio for Performance Marketers

GenStudio for Performance Marketers is a comprehensive platform for creating, evaluating, and managing marketing experiences that reflect and adhere to your brand identity.

Stakeholder access to its many capabilities is controlled by assigned user roles. Your assigned user role determines the tasks you can perform within GenStudio for Performance Marketers. An administrator sets your permissions, which is defined in your welcome email.

If you are new to generative AI-based tools or simply curious about GenStudio for Performance Marketers' core principles see [Concepts](concepts.md) and [Write effective prompts](effective-prompts.md).

## User roles

Creating and deploying modern marketing campaigns requires collaboration among stakeholders with varying responsibilities and skill sets.

Three types of GenStudio for Performance Marketers user roles support this diversity of organizational roles. Permissions are tailored to each of these user types and support each user's responsibilities in the marketing organization.

**The three user role types are**:

* **Creators** use GenStudio for Performance Marketers' generative AI capabilities to create marketing campaign assets, request content review and approval, and publish approved  drafts of this content. All GensStudio users can access and use an asset once its creator has saved it to Content.

* **Collaborators** are the widest range of GenStudio for Performance Marketers users. Collaborators can view and approve content and are an essential part of the workflow that ensures content you generate matches your organization's needs and standards.

* **System administrators** have the broadest set of permissions within GenStudio for Performance Marketers. System administrators can add and delete users and content. Admins perform the essential onboarding task of establishing the fundamental guardrails for campaign asset creation and deployment. Admins implement these guardrails by uploading brand and organizational-specific information such as [brand guidelines](/help/user-guide/guidelines/overview.md).

>[!NOTE]
>Before any users are provisioned into these roles, an administrator must be designated as a superuser in the Adobe Admin console to perform one-time set up tasks. This superuser role operates only in the context of the Adobe Admin Console. It has no role in the GenStudio for Performance Marketers platform interface. There is no concept of superuser in GenStudio for Performance Marketers role assignments.

### Creators

**Creators** have the core permissions needed to create GenStudio for Performance Marketers [!DNL Brands], [!DNL Campaigns], and [!DNL Content] assets. They can also edit and delete assets they have created. GenStudio for Performance Marketers supports the quick creation of hundreds of pieces of content. These users can generate content fragments or whole experiences that orchestrate discrete pieces of approved content to meet the needs of specific marketing campaigns.

Creators interact with GenStudio for Performance Marketers' generative AI technologies through _prompting_. The prompt area in the Canvas provides tools to place prompts in the context of a specific campaign's guidelines. As a result, the quality and success of generated content partially depend on the quality of the brand guidelines your organization has uploaded and the specificity of your prompt.

See [Write effective prompts](effective-prompts.md).

The following table displays the default creator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|----------------|----------------|
|   [!DNL Brands]| no  | no | no |  yes |
|   [!DNL Campaigns] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Content] |     yes  |   yes     |    yes   |   yes      |
|   [!DNL Insights] |  can configure ad connectors only  |    |     |   yes  |
|   [!DNL Personas] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Products] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Reviews and approvals]  |   yes     |  yes   |    yes     |    yes     |

### Collaborators 

**Collaborators** can view assets in GenStudio for Performance Marketers but not create, edit, or delete these assets. Collaborators include stakeholders who are essential to the success of the review and approval process for content but who do not need to create or directly edit content. Legal experts and managers of creators are examples of potential collaborators. GenStudio for Performance Marketers collaborators might have permissions to create and view assets in other Creative Cloud products.

The following table displays the default collaborator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|----------------|----------------|
|   [!DNL Brands]| yes  | yes | yes |  yes |
|   [!DNL Campaigns] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Content] |     yes  |   yes     |    yes   |   yes      |
|   [!DNL Insights] |    no |  no  |   no  |   yes  |
|   [!DNL Personas] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Products] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Reviews and approvals] |   no     |   no  |  no       |   yes      |

### Administrators

**Administrators** create and assign users to any of the GenStudio for Performance Marketers supported roles. They can assign new permissions to individual creators or collaborators as required. Their most critical job is to complete the initial onboarding tasks that prepare your organization to deploy GenStudio for Performance Marketers.

The following table displays the default system administrator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|----------------|----------------|
|   [!DNL Brands]| yes  | yes | yes |  yes |
|   [!DNL Campaigns] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Content] |     yes  |   yes     |    yes   |   yes      |
|   [!DNL Insights] |  yes   |  yes  |   yes |  yes   |
|   [!DNL Personas] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Products]  | yes    |   yes      |  yes       |    yes       |
|   [!DNL Reviews and approvals] |  yes      | yes    |     yes    |   yes      |


## Prepare GenStudio for Performance Marketers to generate content

System administrators prepare their organization's GenStudio for Performance Marketers environment for creators and collaborators to create campaign assets. These preliminary set-up tasks include:

1. [Add guidelines](./guidelines/overview.md) for [!DNL Brands], [!DNL Products], and [!DNL Personas]. Setting up the key building blocks of your organization's brand identity is an essential prerequisite for the work of creators and collaborators. You can either upload brand guideline documents or manually enter brand information.
   * **Prepare your guidelines documents**. The more descriptive and comprehensive your brand guidelines, the better the output. Include brief examples of features that you consider essential to you brand and add descriptions of behavior you want to exclude from content creation. GenStudio for Performance Marketers extracts information from these uploaded documents and begins building your brand. Information such as brand voice, channel, and image guidelines, are populated as GenStudio for Performance Marketers assembles each guideline from your uploaded documents.
   * **Edit or complete brand guideline fields as needed**. Comprehensive brand guidelines form the basis of GenStudio for Performance Marketers' understanding of your organization's brand. Once GenStudio for Performance Marketers has extracted the information it needs from your brand guideline documents, you are prompted to manually edit or complete fields of extracted information. Specify individual product focus areas for content creation by adding a [!DNL Product]. [!DNL Personas] guidelines help tailor content creation for defined customer segments.

   Although setting up an organization's brand guidelines can be a one-time action, you might need to revise and enhance these guidelines based on your organization's volatility, growth, and changing market circumstances.

1. **[Upload templates](./content/use-templates.md)**. Templates provide shortcuts and accelerate content creation. A template contains approved features, such as headers and footers, and establishes guardrails for content creation. Administrators typically upload and manage templates for their organization. Creators use templates to jumpstart the content creation process within the established boundaries of organizational brand.

1. **[Upload approved assets](./content/manage-assets.md)**. Approved assets in [!DNL Content] are available to all GenStudio for Performance Marketers creators. You can seed [!DNL Content] with assets that creators can use to create new experiences or assets. 

1. **[Connect to a Meta (Facebook) account](./insights/connect-channel.md)**. You must configure a connection between GenStudio for Performance Marketers and your organization's social accounts to receive data from your active marketing campaigns, assets, and experiences. [[!DNL Insights]](./insights/overview.md) provides tools to analyze channel-derived data.
