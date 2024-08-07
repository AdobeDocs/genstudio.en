---
title: Prepare an email template for GenStudio
description: Learn how to build a custom email template for GenStudio.
level: Intermediate
feature: Templates, Content
---

# Prepare email template for GenStudio

Typically, a designer will create the visual design of a template in a design program such as Adobe XD. After an email template is designed, coded, and tested, you can prepare it for upload and use in GenStudio.

See [Anatomy of a template](/help/user-guide/content/use-templates.md#anatomy-of-a-template).

## Code an email template

After a template is designed it is coded using HTML and inline CSS. The code should be clean and responsive for various devices.

See [Template examples](/help/user-guide/content/customize-template.md#template-examples).

## Test an email template

Use your email delivery or proofing platform to test your email and verify that it renders properly across different email clients and devices.

Test to ensure your email template satisfies the following:

* Layout adjusts for different screen sizes using CSS media queries
* Buttons are clickable and navigate to the right places/things
* Email template is readable and usable on mobile devices

## Define generated content areas

Define the areas in your email template that should be dynamically populated with content from GenStudio. 

To define generated content areas:

* Identify the text elements in the template GenStudio should auto-generate, such as the headline or CTA.
* Adapt your HTML template by inserting placeholders within it using the Handblebars syntax.

See [Content placeholders](/help/user-guide/content/customize-template.md#content-placeholders).

## Preview the template

Control the visibility of specific content areas by utilizing Built-In Helpers. For example, you can include tracking parameters to links in an exported template while maintaining clean preview links.

See [Template preview](/help/user-guide/content/customize-template.md#template-preview).
