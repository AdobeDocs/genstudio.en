---
title: Prepare an email template
description: Learn how to build a custom email template for GenStudio.
level: Intermediate
feature: Templates, Content
---

# Prepare an email template

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

Use the Handlebars syntax to [insert content placeholders](/help/user-guide/content/customize-template.md#content-placeholders) where GenStudio needs to populate the email with content.

The following example is a simple HTML email template.

+++Example: Basic template

The following is a basic example of an HTML template for email. The head contains simple, inline CSS for styling. The body contains a `pre-header`, `headline`, and `image` placeholder for use by GenStudio to inject content during the email generation process.

```handlebars {line-numbers="true" highlight="13"}
<!DOCTYPE html>
<html>
<head>
    <title>Adobe</title>
    <style>
        .container {
            width: 100%;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>{{ pre_header }}
    <div class="container">
        <h1>{{ headline }}</h1>
        <p><img alt="{{ headline }}"
                src="{{ image }}"
                width="600" height="600"
                border="0"/></p>
        <p>{{ body }}</p>
    </div>
</body>
</html>
```

+++

## Test an email template

Use your email delivery or proofing platform to test your email and verify that it renders properly across different email clients and devices.

Test to ensure your email template satisfies the following:

* Layout adjusts for different screen sizes using CSS media queries
* Buttons are clickable and navigate to the right places/things
* Email template is readable and usable on mobile devices
