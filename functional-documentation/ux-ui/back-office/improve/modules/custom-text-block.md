# Custom text block

## Description

This module adds a custom text block at the bottom of the front-office page.&#x20;

<figure><img src="../../../../../.gitbook/assets/image (13) (1).png" alt="Custom text block User Interface"><figcaption><p>Custom text block User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Page header call to action buttons (modules)](../../../common-components/page-header-call-to-action-buttons-modules.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Language dropdown for input fields](../../../common-components/language-dropdown-for-input-fields.md).
* [Text editing tools list](../../../common-components/text-editing-tools-list.md).
* Shop association block (todo link)
* [Configuration block](../../../common-components/configuration-block.md).&#x20;
* [Save button](../../../common-components/save-button.md) - [Buttons basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).

## The UI elements

### Text block input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Text example</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="custom-text-block.md#text-block-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Custom text block title behavior&#x20;

This is title of the block that has two elements: Text block and Shop association.

### Text block input behavior

This is a text input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) here it's possible select in which language the text will be written. Above the text field there is a [Text editing tools list](../../../common-components/text-editing-tools-list.md).

### **Shop association block behavior**

This is [shop association block](custom-text-block.md#shop-association-block-behavior) it also has 4 outlined CTA buttons ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) to configure shop associations:

* Collapse all - it has minus icon, once clicked it hides all shops.
* Expand all - it has plus icon, once clicked it shows all shops.
* Check all - it has checked checkbox icon, once clicked it checkes all shops.
* Unckeck all - it has unchecked checkbox icon, once clicked it uncheckes all shops.

## Multistores functionality

This page is [Multistores dependent ](../../../common-components/multistores-dependent.md)page.
