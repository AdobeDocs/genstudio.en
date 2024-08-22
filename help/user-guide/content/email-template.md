---
title: Prepare an email template for Adobe GenStudio for Performance Marketers
description: Learn how to build a custom email template for Adobe GenStudio for Performance Marketers.
level: Intermediate
feature: Templates, Content
---

# Prepare email template for Adobe GenStudio for Performance Marketers

Typically, a designer creates the visual design of a template in a design program such as Adobe XD. After an email template is designed, coded, and tested, you can prepare it for upload and use in GenStudio for Performance Marketers.

See [Anatomy of a template](/help/user-guide/content/use-templates.md#anatomy-of-a-template).

## Add guidelines

Before you prepare a Meta ad template, ensure that you have added [guidelines](/help/user-guide/guidelines/overview.md) to your GenStudio for Performance Marketers and populated them with comprehensive info for relevant brands. The [brand guidelines](/help/user-guide/guidelines/brands.md) directly influence generated content.

**Example**: If you want the body of an email template to be no larger than 500 characters, add that requirement to the [channel guidelines](/help/user-guide/guidelines/brands.md#channel-guidelines) for the "body" field.

If guidelines are not added to GenStudio for Performance Marketers, defaults are used.

## Code an email template

After a template is designed, it is coded using HTML and inline CSS. The code should be clean and responsive for various devices.

See [Template examples](/help/user-guide/content/customize-template.md#template-examples).

## Test an email template

Use your email delivery or proofing platform to test your email and verify that it renders properly across different email clients and devices.

Test to ensure that your email template satisfies the following:

* Layout adjusts for different screen sizes using CSS media queries
* Buttons are clickable and navigate to the intended place
* Email template is readable and usable on mobile devices

## Define generated content areas

Define the areas in your email template that should be dynamically populated with content from GenStudio for Performance Marketers. 

To define generated content areas:

* Identify the text elements in the template that GenStudio for Performance Marketers should auto-generate, such as the headline or CTA.
* Adapt your HTML template by inserting placeholders within it using the Handlebars syntax.

See [Content placeholders](/help/user-guide/content/customize-template.md#content-placeholders).

## Preview the template

Control the visibility of specific content areas with Built-In Helpers. For example, you can include tracking parameters to links in an exported template while maintaining clean preview links.

See [Template preview](/help/user-guide/content/customize-template.md#template-preview).

## Upload and use template

After your template is designed, coded, tested, and previewed, you can upload it to GenStudio for Performance Marketers for use in generating brand new marketing content.

See [Working with templates](use-templates.md).
