---
title: Prepare an email template for GenStudio
description: Learn how to build a custom email template for GenStudio.
level: Intermediate
feature: Templates, Content
---

# Prepare an email template for GenStudio

Typically, a designer will create the visual design of a template in a design program such as Adobe XD. After an email template is designed, coded, and tested, you can prepare it for upload and use in GenStudio. 

## Anatomy of an email template

A basic email design includes the following elements: 

* **Preheader**: The preheader (between 40-50 characters) acts as a secondary subject line, complementing and enhancing the main subject line. The preheader is visible in a recipient's inbox alongside the subject line, before the email is even opened.  
* **Header**: The header is the top section of the email that the recipient sees after opening the email. It sets the tone and provides immediate context for the email content. 
* **Body**: The body is the main content area of the email where the primary message is conveyed. This can include text, images, and other media. 
* **CTA (Call to Action)**: The CTA is a call-to-action that encourages the recipient to take a specific action, such as clicking a link, making a purchase, or signing up for an event. 
* **Images**: Images are used to enhance the visual appeal of the email, break up text, and support the message. 
* **Footer**: The footer typically contains additional information such as contact details, social media links, legal disclaimers, and unsubscribe options. 

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
