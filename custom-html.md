# Custom HTML

## Overview

The Custom HTML content block enables you to insert your own HTML code into designs crafted in the builder. While it's as straightforward as adding a text block, this feature is primarily intended for those proficient in HTML. Using custom HTML can impact how your design adjusts to various screen sizes, so make sure the HTML you use is responsive and email compliant. Note that custom HTML typically falls outside of standard support.\


<figure><img src="https://lh7-eu.googleusercontent.com/-8YjBcyUDf7hjR8sKq-MNvOLCywdqJNX9WK6sJAqvwm_Ge3WrGnTw-eUYtYXaJ7T3LJfw87LL7mCsxtpQF3YuQTtN2zqkFZS-g0hnSZDIutDIvaqkDbQXD9IbgiYgJbm-T023WsJ8HSBjgpZpCp0rsg" alt=""><figcaption></figcaption></figure>

## Why Use Custom HTML?

Here are a few scenarios where custom HTML can be valuable:

* **Customized Content:** You're not restricted to predefined settings, giving you more control over styling.
* **Special Elements:** Add content like HTML5 videos or anchor links, which are not standard elements in the builder.
* **Advanced CSS Effects:** While CSS animations aren't universally supported in emails, they can make your web pages more engaging.
* **Live Content:** Embed real-time content like product recommendations or countdowns by pasting code from external vendors.

## How to Add Custom HTML

1. **Drag the Block:** Insert an HTML content block into your design, just like you would with any other block.
2. **Edit HTML:** Click the block to open the HTML editor on the sidebar. You'll see placeholder code, which you can replace with your own HTML. Syntax highlighting and indentation features help make the code readable.

<figure><img src="https://lh7-eu.googleusercontent.com/2kI4wBse5pF1jPtDXy6YlPmvSUTtdlGLAEBCJ75AeVlRJf4ryFXNG9NjsfbllfucnJO6VGN4qZJAN_lUXpN-Ybbjw8jStPtlCEbw_l913Dyt3tn4jrmSQnl3N584OEF2RxRNIZbkwQuk87qwqhBGLPI" alt=""><figcaption></figcaption></figure>

## HTML Tag Restrictions in Emails

When adding custom HTML to emails, a code sanitizer checks and automatically corrects your code. Unsupported tags like \<script> and \<iframe> are removed to avoid security risks and deliverability issues.

Allowed HTML Tags: (for emails only)

* **Tags:** a, abbr, address, area, b, bdo, etc.
* **Attributes:** style, id, class, data-\*, title, href, name, target, etc.

## Using Custom HTML with Pages

The Page Builder doesn't employ a sanitizer, offering more freedom but also more responsibility. You can use any HTML, CSS, or JavaScript syntax when designing landing pages.

## Accessibility Keys for Custom HTML Content Blocks

This section outlines and describes the accessibility keys currently available for navigating the Custom HTML content block. In this section, you'll learn about which keys to use to set your focus, customize properties, exit your design, and save your changes.

{% hint style="warning" %}
We are still working on developing our application's accessibility, and you may notice that some actions aren't available yet. Additional accessibility features are coming soon.&#x20;
{% endhint %}

### **Setting Your Focus**

Take the following steps to set your focus:

1. **Select the Custom HTML Block:** Use `ArrowUp` or `ArrowDown` to navigate to the Custom HTML block. A high-contrast border will appear to show it's selected.
2. **Activate the Block:** Press `Enter` to activate the block, preparing the sidebar for HTML input.

### **Enter HTML**

Take the following steps to enter your HTML:

1. **Accessing the HTML Editor:** After activation, use `Tab` to move to the HTML editor in the sidebar, where you can input your HTML.
2. **Inputting and Editing HTML Code:** Enter your HTML code directly in the editor.

### **Exiting and Saving Changes**

Use the following key to save and exit your design:

* Press `Esc` to exit the editor and save your changes.
