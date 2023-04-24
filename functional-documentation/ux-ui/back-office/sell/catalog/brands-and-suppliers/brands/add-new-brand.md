# Add new brand

## Description

This page opens when in Brands page click on the "Add new brand" button. This creation form allows to create new brand. &#x20;

<figure><img src="../../../../../../../.gitbook/assets/image (8).png" alt="Add new brand User Interface"><figcaption><p>Add new brand User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../../../common-components/account-icon.md).
* [Shop switcher](../../../../../common-components/shop-switcher.md).
* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Text Editing Tools list](../../../../../common-components/text-editing-tools-list.md).
* [Language dropdown for input fields](../../../../../common-components/language-dropdown-for-input-fields.md).
* Shop association block (todo link)
* [Save button](../../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* [Cancel button](../../../../../common-components/cancel-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).

## The UI elements

### Name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>;=#{}</td><td align="center">"<em>invalid characters that were input</em>" is invalid</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters:&#x3C;>;=#{}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Please fill out this field.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">This field cannot be longer than 64 characters</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#name-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Short description input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>;=#{}</td><td align="center">"<em>invalid characters that were input</em>" is invalid</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>'number of entered symbols' <em>of 21844 characters allowed</em></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>21844</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#short-description-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Description input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>;=#{}</td><td align="center">"<em>invalid characters that were input</em>" is invalid</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>'number of entered symbols' <em>of 21844 characters allowed</em></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>21844</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#description-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Logo input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder: Choose file(s)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Upload a brand logo from your computer.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>No file chosen</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#logo-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta title input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>;=#{}</td><td align="center">"<em>invalid characters that were input</em>" is invalid - Language: "<em>chosen language</em>"</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters:&#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#meta-title-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta description input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>;=#{}</td><td align="center">"<em>invalid characters that were input</em>" is invalid - Language: "<em>chosen language</em>"</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters:&#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#meta-description-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta keywords input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>={}</td><td align="center">"<em>invalid characters that were input</em>" is invalid - Language: "<em>chosen language</em>"</td><td></td></tr><tr><td>Default value</td><td>Placeholder: <em>Add tag</em></td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>To add tags, click in the field, write something, and then press the "Enter" key. Invalid characters:&#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#meta-keywords-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enabled toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-brand.md#enabled-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Title of Brands behavior

It contains title and star icon.

### Name input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter new brand name.

### Short description input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter brand short description.

### Description input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter brand description.

### Logo input behavior

This is a field ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) for uploading a logo, it has a button "Browse", when pressed opens a native OS popup to navigate to the logo file. When logo file is double-clicked or selected and clicked Open button, popup closes.&#x20;

### Meta title input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter meta title.

### Meta description input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter meta description.

### Meta keywords input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter meta keywords.

### Enabled toggle switch behavior

This toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows to enable or disable this new brand.

## Multistores functionality

[Multistores independent](../../../../../common-components/multistores-independent.md) page. Multistore functionality depends on Shop association block settings.&#x20;
