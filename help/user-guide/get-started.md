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

Creating and deploying modern marketing campaigns requires collaboration among stakeholders with varying responsibilities and skill sets. Three types of GenStudio user roles support this diversity of organizational roles. Permissions are tailored to each of these suser types and support each user's responsibilities in the marketing organization:

* **Creators** use GenStudio's generative AI capabilities to create marketing campaign assets, request content review and approval, and publish approved, definitive drafts of this content, where all GensStudio users can access and use them.

* **Collaborators** are the widest range of GenStudio users. Collaborators can view and approve GenStudio content and are an essential part of the workflow that ensures that your campaogn assets meet your organizations needs and standards.

* **System administrators** have the widest set of permissions within GenStudio. System administrators can add and delete users and content from Genstudio. Admins perform essential the onboarding task of establishing the fundamental guardrails for campaign asset creation and deployment. Admins implement these guardrails by uploading brand- and organizational- specific information such as brand guidelines and  that high-level components such as brand guidelines and .

Note: Before any users are provisioned into these roles, an administrator must be designated as a superuser in the Adobe Admin console to perform one-time set up tasks. This superuser role operates only in the context of the Adobe Admin Console. It has no role in the GenStudio platform interface. There is no concept of superuser in GenStudio role assignments.

### GenStudio creators

_Creators_ have the core set of permissions needed to create GenStudio brand, campaign, and Content assets. They can also edit and delete assets they have created. GenStudio supports the quick creation of hundreds of pieces of content. These GenStudio users can create content fragments or large experiences that orchestrate discrete pieces of approved content to meet the needs of specific marketing campaigns.

Creators interact with GenStudio's generative AI technologies through _prompting_. The Prompt area on GenStudio's main creating area, the Canvas, provides tools to place prompts in the context of a specific campaign's guidelines. As a result, the success of your prompting efforts partially depends on the quality of the brand guidelines your organization has uploaded and the specificity of your prompt. Review [prompting best practices](effective-prompts.md) for an overview of prompting best practices.

The following table displays the default GenStudio creator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|
|   Brand services| no  | no | no |  yes |
|   Content |     yes  |   yes     |    yes   |   yes      |
|   Campaign, Persona, Product | yes    |   yes      |  yes       |    yes       |
|   Review & approval |   yes     |  yes   |    yes     |    yes     |
|   Insights |  can configure ad connectors only  |    |     |   yes  |

### GenStudio collaborators 

_Collaborators_ can view brand and campaign assets in GenStudio but not create, edit, or delete these assets. Collaborators include stakeholders who are essential to the success of the review and approval process for GenStudio content but who do not need to create or directly edit content. Example collaborators include legal experts and managers of creators. GenStudio collaborators might have create and view asset permission in other Creative Cloud products.

The following table displays the default GenStudio collaborator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|
|   Brand services| yes  | yes | yes |  yes |
|   Content |     yes  |   yes     |    yes   |   yes      |
|   Campaign, Persona, Product | yes    |   yes      |  yes       |    yes       |
|   Review & approval |   no     |   no  |  no       |   yes      |
|   Insights |    no |  no  |   no  |   yes  |

### GenStudio administrators

Admin users create and assign users to all supported roles within GenStudio workflows as defined by the GenStudio Product Card. They can assign new permissions to individual creators or collaborators as a particular campaign requires. Their most critical tasks: Performing the initial onboarding tasks that prepare your organization to deploy GenStudio.

The following table displays the default GenStudio system administrator permissions:

| Feature | Create  | Update | Delete | View |
|-----------|----------------|----------------|
|   Brand services| yes  | yes | yes |  yes |
|   Content |     yes  |   yes     |    yes   |   yes      |
|   Campaign, Persona, Product | yes    |   yes      |  yes       |    yes       |
|   Review & approval |  yes      | yes    |     yes    |   yes      |
|   Insights |  yes   |  yes  |   yes |  yes   |


## First Admin task: Prepare GenStudio to generate marketing content

System adminstrators prepare their organization's GenStudio environment for creators and collaborators to create campaign assets. These preliminary set-up tasks include:

1. [Set up guidelines](./guidelines/overview.md)—Brands, Products, and Personas. Setting up the key building blocks of your organization's marketing campaigns is an essential prerequisite for the work of GenStudio creators and collaborators. Set up requires either uploading guideline documents that your organization has created or manually entering brand information.

  **Prepare your guidelines documents**. The more descriptive and comprehensive your brand guidelines, the better GenStudio's output. Consider including brief examples of features that you consider essential to you brand. Don't hesitate to add descriptions of behavior you want to exclude from GenStudio content creation.

  GenStudio extracts information from your uploaded documents and begins building your brand. Information such as brand voice, channel, and image guidelines, are populated as GenStudio assembles each guideline from your guideline documents.

  **Enter information into select brand guidelines fields in GenStudio**. 

  **


1. [Upload templates](./content/use-templates.md). _Templates_ provide shortcuts and accelerate content creation. A template contains approved features, such as headers and footers, and establishes guardrails for content creation. Administrators typically upload and manage templates for their organization. Creators use templates to jumpstart the content creation process.

1. [Upload approved assets](./content/manage-assets.md). Approved assets in GenStudio Content are available to all GenStudio creators 


1. [Connect to a Meta (Facebook) account](./insights/connect-channel.md). Channel guidelines (email, display ads, and social ads) 

Depending on your organization's volatility and growth, your brand guidelines might change or expand. You can revise and enhance thee model that GS has of your brand guidlines bu uploaridn a revised or expanded brand guidlines PDF. We present this task as one-time only, but in reaility, you might need to iterately revisit it.


