# Delivery Slips

## Description

This UI allows configuring the Delivery Slips - download the PDF or manage the additional options.

<figure><img src="../../../../../.gitbook/assets/image (8) (1) (1).png" alt="Delivery Slips User Interface"><figcaption><p>Delivery Slips User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../common-components/cancel-button.md)
* [E-commerce logo ](../../../common-components/back-office-header/prestashop-logo.md)
* [Version number](../../../common-components/prestashop-version-number.md)
* [Quick access dropdown ](../../../common-components/quick-access-dropdown.md)
* [Search input](../../../common-components/search-input-field.md)&#x20;
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../common-components/account-icon.md)
* [Language dropdown for input fields](../../../common-components/language-dropdown-for-input-fields.md)
* [Save button](../../../common-components/save-button.md)
* [Cancel button](../../../common-components/cancel-button.md)

## Delivery Slips meaning

Delivery Slip is a PDF-typed document in Prestashop, where the delivery information about order is being printed in.

## Creation of the Delivery Slip

Once the Order is being entered to the Shipped status, the PDF of the Delivery Slip is generated, and it can be downloaded in the Order page.

## Top UI elements

**Delivery Slips** - H1 class title for the page.

## Printer icon and Print PDF block

This block allows setting the desired date range and to download the Delivery Slips one after one in a single PDF file.

* **From and **_**i**_** tooltip icon** - setting the date range using the date widget. When the icon is hovered, the tooltip text is _Format: 2011-12-31 (inclusive)_.
* **To and **_**i**_** tooltip icon** - setting the date range using the date widget. When the icon is hovered, the tooltip text is _Format: 2011-12-31 (inclusive)_.
* **Generate PDF Call-to-action** - clicking the button initiates the PDF download process.

## Delivery Slip PDF structure

* **Logo** - top-right logo of the shop.
* **DELIVERY, date and the Delivery Slip name** - delivery slip title, timestamp and factual delivery name, containing Latin letters and numbers with hashtag (#) prefix.
* **Shop name**
* **Billing & Delivery Address and the address**
* **Order Reference**
* **Order Date**
* **Carrier**
* **Reference**
* **\*\*Product \*\***
* **Qty** - meaning Quantity.
* **Payment Method** - the name payment method.
* **Price amount with the currency symbol**

## Screw icon and Delivery slip options block

### **Delivery prefix with **_**i**_** tooltip icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field name is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Prefix used for delivery slips</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">The field name is required at least in your default language.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>128</td><td align="center">This value is too long. It should have 128 characters or less. - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="delivery-slips.md#delivery-prefix-with-i-tooltip-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Delivery number with **_**i**_** tooltip icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>The next delivery slip will begin with this number and then increase with each additional slip.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>19</td><td align="center">This value is not valid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="delivery-slips.md#delivery-number-with-i-tooltip-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Enable product image with **_**i**_** tooltip icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Add an image before product name on delivery slip.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">The field name is required at least in your default language.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>128</td><td align="center">This value is too long. It should have 128 characters or less. - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="delivery-slips.md#enable-product-image-with-i-tooltip-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

If the settings update is successful, there will be green notification with the checkmark icon and text _Update successful_.

If the settings update is not successful, because the Delivery number is typed with Latin letters or up to 19 characters, there will be an error with red exclamation mark and the text with _This value is not valid._

## Behavior descriptions

### **Delivery prefix with **_**i**_** tooltip icon behavior**&#x20;

Input field, where custom Delivery Slip character prefix can be modified or added. It can be managed with the different languages, using the dropdown with the language list installed in the system. Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Delivery number with **_**i**_** tooltip icon behavior**&#x20;

Input field, where custom Delivery Slip number can be modified or added. The number entered will mark the beginning number of all Delivery Slip numbers further. Max 19 characters allowed to input. Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Enable product image with **_**i**_** tooltip icon behavior**&#x20;

Enable or Disable toggle button, that Enables or Disables displaying product image, in the PDF file. By default, the toggle switch is Disabled. Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

## Multistores functionality

This page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.

All the configuration inputs and PDF downloads are separately maintained by separate Multistores, because these settings are saved in different databases. It means, that settings saved in one Multistore will not be reflected in the other ones.
