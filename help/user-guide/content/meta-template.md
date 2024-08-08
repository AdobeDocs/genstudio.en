---
title: Prepare a Meta ad template for GenStudio
description: Learn how to build a custom Meta ad template for GenStudio.
level: Intermediate
feature: Templates, Content
---

# Prepare Meta ad template for GenStudio

Creating a Meta ad template involves a structured approach tailored for social media. After a Meta ad template is designed and tested, you can prepare it for upload and use in GenStudio.

## Add guidelines

Before you prepare a Meta ad template, ensure that you have added [guidelines](/help/user-guide/guidelines/overview.md) to your GenStudio and populated them with comprehensive info for relevant brands. The [brand guidelines](/help/user-guide/guidelines/brands.md) directly influence generated content.

**Example**: If you want the body of a Meta ad template to be no larger than 500 characters, add that requirement to the [channel guidelines](/help/user-guide/guidelines/brands.md#channel-guidelines) for the "body" field.

If guidelines are not added to GenStudio, defaults are used.

## Design a template

Typically, a designer creates the visual design of a template in a design program such as Adobe XD.

See [Anatomy of a template](/help/user-guide/content/use-templates.md#anatomy-of-a-template) and [Template examples](/help/user-guide/content/customize-template.md#template-examples).

### Ad specifications

GenStudio supports these aspect ratios for Meta ads:

* Square (1:1): 1080 x 1080 pixels 
* Vertical (4:5): 1080 x 1350 pixels
* Story (9:16): 1080 x 1920 pixels

If the ad is not designed in one of the these aspect ratios, GenStudio automatically crops the image into the appropriate size.  

## Test a Meta ad template

Test your template using Meta's Creative Hub to see how the ad looks in different placements such as in a feed or as a story.

Use your email delivery or proofing platform to test your email and verify that it renders properly across different email clients and devices.

## Define generated content areas

Define the areas in your email template that should be dynamically populated with content from GenStudio. 

To define generated content areas:

* Identify the text elements in the template that GenStudio should auto-generate, such as the headline or CTA.
* Adapt your HTML template by inserting placeholders within it using the Handblebars syntax.

See [Content placeholders](/help/user-guide/content/customize-template.md#content-placeholders).

## Preview the template

Control the visibility of specific content areas by utilizing Built-In Helpers. For example, you can include tracking parameters to links in an exported template while maintaining clean preview links.

See [Template preview](/help/user-guide/content/customize-template.md#template-preview).

## Upload and use template

After your template is designed, coded, tested, and previewed, you can upload it to GenStudio for use in generating brand new marketing content.

See [Working with templates](use-templates.md).
