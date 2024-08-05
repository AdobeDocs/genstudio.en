---
title: Get started with GenStudio
description: Learn how to set up your GenStudio to generate new brand-aligned marketing content.
level: Beginner
feature: Prompt, Brands Service, Personas Service, Products Service, Generative AI
---

# Get started with GenStudio

GenStudio is a comprehensive platform for creating, evaluating, and managing marketing experiences that reflect and adhere to your brand identity. 
Stakeholder access to its many capabilities is controlled by assigned user roles. Your assigned user role determines the tasks you can perform within GenStudio. A GenStudio administrator sets your permissions, which is defined in your welcome email. 

## Concepts

If you are new to generative AI-based tools or simply curious about GenStudio's core principles, explore these conceptual topics: 

* [GenStudio concepts](concepts.md)

* [Review prompting best practices](effective-prompts.md)

## GenStudio user roles

Creating and deploying modern marketing campaigns requires collaboration among stakeholders with varying responsibilities and skill sets. Three types of GenStudio user roles support this diversity of organizational roles. Permissions are tailored to each of these user types and support each user's responsibilities in the marketing organization.

**The three user role types are**:

* **Creators** use GenStudio's generative AI capabilities to create marketing campaign assets, request content review and approval, and publish approved, definitive drafts of this content. All GensStudio users can access and use an asset once its creator has saved it to Content.

* **Collaborators** are the widest range of GenStudio users. Collaborators can view and approve GenStudio content and are an essential part of the workflow that ensures that your campaign assets meet your organization's needs and standards.

* **System administrators** have the widest set of permissions within GenStudio. System administrators can add and delete users and content from Genstudio. Admins perform essential the onboarding task of establishing the fundamental guardrails for campaign asset creation and deployment. Admins implement these guardrails by uploading brand and organizational-specific information such as [brand guidelines](/help/user-guide/guidelines/brands.md).

>[!NOTE]
>Before any users are provisioned into these roles, an administrator must be designated as a superuser in the Adobe Admin console to perform one-time set up tasks. This superuser role operates only in the context of the Adobe Admin Console. It has no role in the GenStudio platform interface. There is no concept of superuser in GenStudio role assignments.

### GenStudio creators

_Creators_ have the core permissions needed to create GenStudio [!DNL Brands], [!DNL Campaigns], and [!DNL Content] assets. They can also edit and delete assets they have created. GenStudio supports the quick creation of hundreds of pieces of content. These GenStudio users can generate content fragments or whole experiences that orchestrate discrete pieces of approved content to meet the needs of specific marketing campaigns.

Creators interact with GenStudio's generative AI technologies through _prompting_. The GenStudio Canvas Prompt area provides tools to place prompts in the context of a specific campaign's guidelines. As a result, the quality and success of generated content partially depend on the quality of the brand guidelines your organization has uploaded and the specificity of your prompt.

See [prompting best practices](effective-prompts.md).

The following table displays the default GenStudio creator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|
|   [!DNL Brands]| no  | no | no |  yes |
|   [!DNL Campaigns] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Content] |     yes  |   yes     |    yes   |   yes      |
|   [!DNL Insights] |  can configure ad connectors only  |    |     |   yes  |
|   [!DNL Personas] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Products] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Review and approval]  |   yes     |  yes   |    yes     |    yes     |

### GenStudio collaborators 

_Collaborators_ can view brand and campaign assets in GenStudio but not create, edit, or delete these assets. Collaborators include stakeholders who are essential to the success of the review and approval process for GenStudio content but who do not need to create or directly edit content. Example collaborators include legal experts and managers of creators. GenStudio collaborators might have create and view asset permission in other Creative Cloud products.

The following table displays the default GenStudio collaborator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|
|   [!DNL Brands]| yes  | yes | yes |  yes |
|   [!DNL Campaigns] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Content] |     yes  |   yes     |    yes   |   yes      |
|   [!DNL Insights] |    no |  no  |   no  |   yes  |
|   [!DNL Personas] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Products] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Review and approval] |   no     |   no  |  no       |   yes      |

### GenStudio administrators

Admin users create and assign users to any of the GenStudio supported roles. They can assign new permissions to individual creators or collaborators as a particular campaign requires. Their most critical job is to complete the initial onboarding tasks that prepare your organization to deploy GenStudio.

The following table displays the default GenStudio system administrator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|
|   [!DNL Brands]| yes  | yes | yes |  yes |
|   [!DNL Campaigns] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Content] |     yes  |   yes     |    yes   |   yes      |
|   [!DNL Insights] |  yes   |  yes  |   yes |  yes   |
|   [!DNL Personas] | yes    |   yes      |  yes       |    yes       |
|   [!DNL Products]  | yes    |   yes      |  yes       |    yes       |
|   [!DNL Review and approval] |  yes      | yes    |     yes    |   yes      |


## First Admin task: Prepare GenStudio to generate marketing content

System adminstrators prepare their organization's GenStudio environment for creators and collaborators to create campaign assets. These preliminary set-up tasks include:

1. [Set up guidelines](./guidelines/overview.md)[!DNL Brands], [!DNL Products], and [!DNL Personas]. Setting up the key building blocks of your organization's marketing campaigns is an essential prerequisite for the work of GenStudio creators and collaborators. Set up requires either uploading guideline documents that your organization has created or manually entering brand information.

  **Prepare your guidelines documents**. The more descriptive and comprehensive your brand guidelines, the better GenStudio's output. Consider including brief examples of features that you consider essential to you brand. Don't hesitate to add descriptions of behavior you want to exclude from GenStudio content creation. GenStudio extracts information from these uploaded documents and begins building your brand. Information such as brand voice, channel, and image guidelines, are populated as GenStudio assembles each guideline from your uploaded documents.

  **Edit or complete brand guideline fields as needed**. Comprehensive brand guidelines form the basis of GenStudio's understanding of your organization's brand. Once GenStudio has extracted the information it needs from your brand guideline documents, you are prompted to manually edit or complete fields of extracted information as needed.

  **Create product and persona guidelines**. 

Although setting up an organization's brand guidelines can be a one-time action, you might need to revise and enhance these guidelines based on your organization's volatility, growth, and changing market circumstances.

1. [Upload templates](./content/use-templates.md). _Templates_ provide shortcuts and accelerate content creation. A template contains approved features, such as headers and footers, and establishes guardrails for content creation. Administrators typically upload and manage templates for their organization. Creators use templates to jumpstart the content creation process within the established boundaries of organizational brand.

1. [Upload approved assets](./content/manage-assets.md). Approved assets in GenStudio Content are available to all GenStudio creators. You can seed GenStudio Content with assets that creators can subsequently use to create new marketing campaigns or assets. 

1. [Connect to a Meta (Facebook) account](./insights/connect-channel.md). You must configure a connection between GenStudio and your organization's social accounts, email, and display ads to receive data from your active marketing campaigns, assets, and experiences. GenStudio [Insights](./insights/overview.md)provides tools to analyze channel-derived data.
