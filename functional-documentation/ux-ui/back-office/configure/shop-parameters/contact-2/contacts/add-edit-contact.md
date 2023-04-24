# Add / Edit Contact

## Description

This page is responsible for Adding or Editing the Contacts

<figure><img src="../../../../../../../.gitbook/assets/image (61).png" alt="Contact page UI"><figcaption><p>Contacts page User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/contact/contacts.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Backoffice Headers](../../../../../common-components/back-office-header/)
* [Language dropdown for input fields](../../../../../common-components/language-dropdown-for-input-fields.md)

## Contacts / Stores Tabs

There are 2 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* Contacts (active)
* [**Stores**](../../contact-1/add-or-edit-stores.md)

## Contacts section

The section starts with the envelope-style icon and title _Contacts_.

### Title

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field title is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or pre-filled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Contact name (e.g. Customer Support).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">This field cannot be longer than 255 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-contact.md#title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

This field is language dependent

### Email address

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only valid email address construction allowed.</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-contact.md#email-address-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Save messages?

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>If enabled, all messages will be saved in the "Customer Service" page under the "Customer" menu.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-contact.md#save-messages-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Description

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-contact.md#description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

This field is language dependent

## Behavior descriptions

### Shop association behavior

This association block lets user choose, which Multistores can be affected with the settings changes. This component uses a [Checkmark navigation CTA buttons](../../../../../common-components/checkmark-navigation-cta-buttons.md) common component.

### Title behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding the contact Title.

### Email address behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding an email address.

### _Save messages?_ behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. If the switch is Enabled, all messages will be saved in the "Customer Service" page under the "Customer" menu.

### Description behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding the Description text for Contact.

## Multistores functionality

This page is [Multistores dependent](../../../../../common-components/multistores-dependent.md) page.
