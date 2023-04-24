# Edit / Add Supplier

## Description

This page is responsible for Adding or Editing a specific Supplier.

<figure><img src="../../../../../../.gitbook/assets/image (41) (1).png" alt="Adding or Editing Supplier UI"><figcaption><p>Adding or Editing Supplier User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/catalog/brands-and-suppliers/suppliers.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)
* [Cancel button](../../../../common-components/cancel-button.md)
* [Save button](../../../../common-components/save-button.md)
* [Text Editing Tools list](../../../../common-components/text-editing-tools-list.md)

## Tabs

There are 2 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* **Brands**
* **Suppliers** (active)

## Suppliers section

The section starts with the truck-style icon and title _Suppliers_.

### Name

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this feald (browser error)</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters: &#x3C;>;=#{}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">This field cannot be longer than 64 characters</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Description

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center"><em>-</em>"@#$@#" is invalid</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Will appear in the list of suppliers.<br><em>{total_characters_typed} of 21844 characters allowed</em></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Phone

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center">"@#$@#" is invalid</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>32</td><td align="center">This field cannot be longer than 32 characters</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#phone-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Mobile phone

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center">"@#$@#" is invalid</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>32</td><td align="center">This field cannot be longer than 32 characters</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#mobile-phone-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Address

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#address-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Address (2)

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#address-2-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Zip/Postal code

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center">"@#$@#" is invalid</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>12</td><td align="center">This field cannot be longer than 12 characters</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#zip-postal-code-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### City

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this feald (browser error)</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center">"%$@#" is invalid</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">This field cannot be longer than 64 characters</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#city-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Country

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Default Prestashop localized country </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#country-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### DNI

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES/NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center">"%$@#" is invalid</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>16</td><td align="center">This field cannot be longer than 16 characters</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#dni-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Logo

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Upload a supplier logo from your computer.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#logo-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta title

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden invalid characters: &#x3C;>={}</td><td align="center">For example "==={{" is invalid - Language: English (English)</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">This field cannot be longer than 255 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#meta-title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta description

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden invalid characters: &#x3C;>={}</td><td align="center">For example "==={{" is invalid - Language: English (English)</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>512</td><td align="center">This field cannot be longer than 512 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#meta-description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta keywords

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden invalid characters: &#x3C;>={}</td><td align="center">For example "==={{" is invalid - Language: English (English)</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>To add tags, click in the field, write something, and then press the "Enter" key. Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">This field cannot be longer than 255 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#meta-keywords-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enabled

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-supplier.md#enabled-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Shop association behavior

This association block lets user choose, which Multistores can be affected with the settings changes. This component uses a [Checkmark navigation CTA buttons](../../../../common-components/checkmark-navigation-cta-buttons.md) common component.

### Name behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier name.

### Description behavior

[Text Editing Tools list](../../../../common-components/text-editing-tools-list.md) common component. For editing the Description name.

### Phone behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier's phone number.

### Mobile phone behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Mobile phone number.

### Address behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier's address.

### Address (2) behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier's additional address.

### Zip/Postal code behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier's ZIP or Postal code.

### City behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier's City name.

### Country behavior

[Dropdown Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component. For editing or adding the Supplier's Country from the list.

### DNI behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Dynamic number insertion (DNI) is a marketing technology that gives businesses attribution for the phone calls driven from their digital advertising and website.

### Logo behavior

Browsing the image file from the UI modal, that appears from the local machine for user. By default, _Choose file(s)_ placeholder appears in the component.

### Meta title behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier's Meta title.

### Meta description behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Supplier's Meta title description.

### Meta keywords behavior

[PS Tags UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/ps-tags--ps-tags) component. For adding or editing the Meta keywords, separated by comma.

### Enabled behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Enabling or disabling this particular Supplier.

## Multistores functionality

This page is [Multistores independent](../../../../common-components/multistores-independent.md) page.
