---
description: Learn more about importing your existing HTML designs into the Email Builder.
---

# HTML Importer

## Overview

The HTML Importer allows you to transform your existing HTML email templates into an editable format within the email builder.

With the HTML Importer, you no longer need to manually recreate your email designs from scratch. Instead, simply import your pre-built HTML, and the importer will convert it into a format compatible with the application's Email Builder. This supports a faster, more efficient workflow for editing and updating existing email content in the no-code builder.

{% hint style="info" %}
**Note:** The HTML Importer is designed to convert the **majority** of HTML into a format compatible with the Email Builder. You may notice that a small percentage of your design may not perfectly match your original design after importing HTML into the Email Builder. These scenarios require light manual editing in the no-code Email Builder to complete your design.  &#x20;
{% endhint %}

## How to Use

To use the HTML Importer feature, follow these steps:

1. Log in to the application.
2. Navigate to the section or panel where import options are located.
3. Select the **HTML Importer** feature.
4. Upload your existing HTML email file or paste your HTML code into the designated field.
5. Submit the HTML for import.
6. After the importer finishes processing, your content will appear in the no-code Email builder, ready for drag-and-drop editing.

## HTML Requirements

To ensure a successful import, your HTML must meet the following criteria:

* **DOCTYPE Declaration**: Your HTML file must start with a valid `<!DOCTYPE html>` declaration.
* **Valid Structure**: Your HTML must include `<html>` and `<body>` tags.
* **Character Encoding**: Include `<meta charset="UTF-8">` inside the `<head>` to prevent character issues during conversion.
* **Static Content Only**: The importer supports static HTML and CSS. It does **not** support HTML created or manipulated via JavaScript.
* **Public Resources**: All images and linked resources must be **publicly accessible** online. Content hosted on private networks or behind firewalls cannot be imported successfully.

To get the best results, make sure your HTML follows standard [email development best practices](https://beefree.io/hub/html-email-creation).

## Content Block Limitations

While the importer supports most standard email elements, a few content blocks and elements are currently not supported. They are the following:

* **Background Images**
* **Dividers**
* **Menus**

Additionally, **custom fonts** are supported in most cases, especially if hosted on services like Google Fonts. However, highly specific proprietary fonts may require manual integration.

While these are not supported through the conversion, these can easily be added to design with a bit of light editing within the no-code Email Builder.

## Additional Considerations

Consider the following when using the HTML Importer:

* **Migration vs. Perfect Reproduction:** The importer is designed to **migrate** your HTML into a visually editable format—not to pixel-perfectly replicate the original. Some design adjustments may be needed after importing to achieve the desired look. However, this is still significantly faster than starting from scratch.
* **Consistency and Predictability:** Every time you use the importer with the same HTML file, the result will be the same.
* **Security and Data Usage:** Imported templates are **not stored** by the importer service. They are processed in real-time and returned to the builder for editing. Your content remains your own.
*   **Supported Formats:** The importer works with plain HTML only. Other email formats like `.eml` are not supported directly. If needed, convert these to valid HTML before importing.&#x20;

    **Note:** Images are **not** uploaded or re-hosted. They continue to reference the original URL provided in the HTML.
* **Dynamic Content and Merge Tags:** For best results, add dynamic content and merge tags within the Email Builder after the import.

### FAQs

This section includes answers to the most frequently asked questions.

**What happens to unsupported HTML tags?**\
They won’t break the import, but may not render as expected. It’s a good idea to validate your code and clean unsupported elements before importing.

**Does this tool use AI?**\
No. The importer does not rely on AI or machine learning. It is a deterministic conversion engine designed for reliability and performance.

**Can I import templates with external CSS?**\
External CSS may work if publicly hosted, but is not fully supported. For best results, inline your styles.
