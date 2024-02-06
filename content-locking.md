# Content Locking

#### Overview

Content locking is an essential feature in the builder that enables specific user roles to lock design elements, preventing unauthorized modifications. This is especially useful in scenarios such as regulated industries where certain text, like legal disclaimers in email footers, must not be altered.

#### Use-Cases for Content Locking

Imagine you are a digital marketing agency with a new junior editor on your team. Your client operates in a regulated industry, and their emails must include specific legal language in the footer. Locking this content ensures the junior editor can't make unauthorized changes.

#### How to Lock Rows and Content Blocks

<figure><img src="https://lh7-eu.googleusercontent.com/DTp6Cbfkmqb7kIVTBvmGM68cfhbyJYssZ4CPrO5-6WPdW_n81wx_stmROnpPifBRQMfA5ntmvL-opUyg2UT9Jsn7DvbQPC-yiyVYhoWqKVxTc2LQFXfZg_8orEt4mL-nZQBGSg-792Sgf4QYTH_EC5g" alt=""><figcaption></figcaption></figure>

* Role Restrictions: Users with Manager roles or above have the ability to lock rows or individual content blocks.
* Row-Level Locking: When a row is locked, the contained content blocks are automatically locked.
* Content Block-Level Locking: It's possible to lock individual content blocks without affecting the entire row.

#### Visibility for Lower-Level Users

* Inability to Edit: Editors and Contributors can't modify locked rows or content blocks.
* Alert Message: Attempting to edit locked elements triggers an alert message.
* Drag-and-Drop Restrictions: These users also can't drag new content into a locked row, indicated by a diagonal overlay pattern.

<figure><img src="https://lh7-eu.googleusercontent.com/FsBk6eUuCd168z4cNB5duA_5v5kDzBOMU6SNBryWzSzr_jLdtm9nBf5nsF-ExwZXxjY7JA2Dv2Q5ZNbEvl0-CL5du03GTmGvXJnY13os5ANqXi6AAn_VWxWZJsiTC7BEyYByZF1iGGNW3AXhbc-ZQDM" alt=""><figcaption></figcaption></figure>

**Partial Locking: Lock Layout, Edit Content**

Unlock Within Locked Rows: Content blocks can be individually unlocked within a locked row, allowing specific edits while maintaining the layout.
