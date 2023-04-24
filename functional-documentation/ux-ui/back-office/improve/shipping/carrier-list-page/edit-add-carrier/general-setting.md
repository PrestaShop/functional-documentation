# General setting

## Description

The purpose of this page is to set up the general attributes of carrier.

<figure><img src="../../../../../../../.gitbook/assets/Capture d’écran 2023-03-06 à 12.04.35.png" alt=""><figcaption></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../../../common-components/shop-switcher-with-eye-icon.md).
* [Bell icon](../../../../../common-components/bell-icon.md)-[Toolbar UI KIT](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar)
* [Account icon](../../../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../../common-components/help-button.md) - [Buttons Outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## The UI elements

### Carrier name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The name field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Allowed letters, numbers, spaces and ().-</td><td align="center">The name field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Allowed characters: letters, spaces and "().-". The carrier's name will be displayed during checkout. For in-store pickup, enter 0 to replace the carrier name with your shop name.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">Your entry in field name (language English (English)) exceeds max length 64 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="general-setting.md#carrier-name-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Transit time input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The field delay is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>;=#{}</td><td align="center">The delay field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Country name - Invalid characters: &#x3C;>;=#{}</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="general-setting.md#transit-time-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Speed grade input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only one number from 0 to 9 is allowed.</td><td align="center">The grade field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Enter a "0" for a longest shipping delay, or "9" for the shortest shipping delay.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>1</td><td align="center">The grade field is too long (1 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="general-setting.md#speed-grade-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Logo input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>JPG, GIF, PNG, WEBP</td><td align="center">Cannot upload file.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Format: JPG, GIF, PNG, WEBP. Filesize: 8.00 MB max. Current size: undefined.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>8.00 MB</td><td align="center">Cannot upload file.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="general-setting.md#logo-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Tracking URL input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">The url field is invalid.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>For example: 'http://example.com/track.php?num=@' with '@' where the tracking number should appear.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Delivery tracking URL: Type '@' where the tracking number should appear. It will be automatically replaced by the tracking number.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="general-setting.md#tracking-url-input-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### General settings step behavior

This step has elements:

* [Carrier name input](general-setting.md#carrier-name-input-behavior)
* [Transit time input](general-setting.md#transit-time-input-behavior)
* [Speed grade input](general-setting.md#speed-grade-input-behavior)
* [Logo input](general-setting.md#logo-input-behavior)
* [Tracking URL input](general-setting.md#tracking-url-input-1)

### Carrier name input behavior

This is input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter carrier name.&#x20;

### Transit time input behavior

This is input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter transit time. This input has language dropdown to enter information for customers in different languages.

### Speed grade input behavior

This is input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter speed grade.

### Logo input behavior

This is input ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) to choose file that will be shown as carrier logo. This input has a file icon on the left input side. On the right input side there is CTA button with a catalog icon with title **Choose a file**. Once clicked on input or button opens modal with this PC files. When file uploaded it is shown in Logo block in each carrier creation step.

### Tracking URL input

This is input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter tracking URL.

### Previous button behavior

This is outline CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked the previous step is displayed. When hover mouse pointer on button, its color changes. This button is shown in each new carrier creation step.

### Next button behavior

This is outline CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked the next step is displayed. If there is an error, this button is disabled. When hover mouse pointer on button, its color changes. This button is shown in each new carrier creation step.

### Finish button behavior&#x20;

This is a green CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)), once clicked saves carrier and display carrier list. If there is an error, this button is disabled. When hover mouse pointer on button, its color changes. This button is shown in each new carrier creation step.

##
