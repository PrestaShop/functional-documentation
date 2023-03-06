# Add new / edit carrier

## Description

The purpose of this page is to add new or edit carrier. It has these steps for new carrier addition:&#x20;

* General settings
* Multistore (If multistore is enabled)
* Shipping locations and costs
* Size, weight, and group access
* Summary

<figure><img src="../../../../../../.gitbook/assets/image (1).png" alt="Add new / edit carrier General settings step User Interface"><figcaption><p>Add new / edit carrier General settings step User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../common-components/e-commerce-logo.md).
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md).
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Cancel button](../../../../common-components/cancel-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Help Button](../../../../common-components/help-button.md) - [Buttons Outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Language dropdown for input fields](../../../../common-components/language-dropdown-for-input-fields.md).&#x20;
* [Checkmark navigation CTA buttons](../../../../common-components/checkmark-navigation-cta-buttons.md) - [Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons).
* Shop association block (todo link)

## The UI elements

### Carrier name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The name field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Allowed letters, numbers, spaces and ().-</td><td align="center">The name field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Allowed characters: letters, spaces and "().-". The carrier's name will be displayed during checkout. For in-store pickup, enter 0 to replace the carrier name with your shop name.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">Your entry in field name (language English (English)) exceeds max length 64 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#carrier-name-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Transit time input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The field delay is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>&#x3C;>;=#{}</td><td align="center">The delay field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Country name - Invalid characters: &#x3C;>;=#{}</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#transit-time-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Speed grade input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only one number from 0 to 9 is allowed.</td><td align="center">The grade field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Enter a "0" for a longest shipping delay, or "9" for the shortest shipping delay.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>1</td><td align="center">The grade field is too long (1 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#speed-grade-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Logo input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>JPG, GIF, PNG, WEBP</td><td align="center">Cannot upload file.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Format: JPG, GIF, PNG, WEBP. Filesize: 8.00 MB max. Current size: undefined.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>8.00 MB</td><td align="center">Cannot upload file.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#logo-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Tracking URL input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">The url field is invalid.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>For example: 'http://example.com/track.php?num=@' with '@' where the tracking number should appear.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Delivery tracking URL: Type '@' where the tracking number should appear. It will be automatically replaced by the tracking number.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#tracking-url-input-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Add handling costs toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Include the handling costs (as set in Shipping > Preferences) in the final carrier price.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#add-handling-costs-toggle-switch">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Free shipping toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Include the handling costs (as set in Shipping > Preferences) in the final carrier price.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#free-shipping-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Billing radio buttons

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>According to total weight.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#billing-radio-buttons-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Tax dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>First tax rule by tax rule list.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#tax-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Out-of-range behavior dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Apply the cost of the highest defined range.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Out-of-range behavior occurs when no defined range matches the customer's cart (e.g. when the weight of the cart is greater than the highest weight limit is defined by the weight ranges).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#out-of-range-behavior-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Range Will be applied when the weight or currency is >= input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only.</td><td align="center">This range is not valid.</td><td></td></tr><tr><td>Default value</td><td>0.000000</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#range-will-be-applied-when-the-weight-or-currency-is-greater-than-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Range Will be applied when the weight or currency is < input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only.</td><td align="center">This range is not valid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#range-will-be-applied-when-the-weight-or-currency-is-less-than-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Maximum package width (**Dimension unit**) input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Integer numbers allowed only.</td><td align="center">The max_width field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum width managed by this carrier. Set the value to "0", or leave this field blank to ignore. The value must be an integer.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#maximum-package-width-dimension-unit-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Maximum package height (**Dimension unit**) input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Integer numbers allowed only.</td><td align="center">The max_height field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum height managed by this carrier. Set the value to "0", or leave this field blank to ignore. The value must be an integer.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#maximum-package-height-dimension-unit-input-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Maximum package depth (**Dimension unit**) input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Integer numbers allowed only.</td><td align="center">The max_depth field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum depth managed by this carrier. Set the value to "0", or leave this field blank to ignore. The value must be an integer.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#maximum-package-depth-dimension-unit-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Maximum package weight (**Dimension unit**) input&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Integer numbers allowed only.</td><td align="center">The max_weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum weight managed by this carrier. Set the value to "0", or leave this field blank to ignore. The value must be an integer.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#maximum-package-weight-dimension-unit-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Group access checkboxes

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>All groups marked</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Mark the group that are allowed access to this carrier.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#group-access-checkboxes-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enabled toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Enable the carrier in the front office.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-carrier.md#enabled-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### General settings step behavior

This step has elements:

* [Carrier name input](add-new-edit-carrier.md#carrier-name-input-behavior)
* [Transit time input](add-new-edit-carrier.md#transit-time-input-behavior)
* [Speed grade input](add-new-edit-carrier.md#speed-grade-input-behavior)
* [Logo input](add-new-edit-carrier.md#logo-input-behavior)
* [Tracking URL input](add-new-edit-carrier.md#tracking-url-input-1)

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

### Multistore step behavior

This step contains these common components:

* Shop association block (todo link)
* [Checkmark navigation CTA buttons](../../../../common-components/checkmark-navigation-cta-buttons.md)

### Shipping locations and costs step behavior

This step has elements:

* [Add handling costs toggle switch](add-new-edit-carrier.md#add-handling-costs-toggle-switch-behavior)
* [Free shipping toggle switch](add-new-edit-carrier.md#free-shipping-toggle-switch-behavior)
* [Billing radio buttons](add-new-edit-carrier.md#billing-radio-buttons-behavior)
* [Tax dropdown](add-new-edit-carrier.md#tax-dropdown-behavior)
* [Out-of-range behavior dropdown](add-new-edit-carrier.md#out-of-range-behavior-dropdown-behavior)
* [Range Will be applied when the weight or currency is >=  input](add-new-edit-carrier.md#range-will-be-applied-when-the-weight-or-currency-is-greater-than-input-behavior)
* [Range Will be applied when the weight or currency is <  input](add-new-edit-carrier.md#range-will-be-applied-when-the-weight-or-currency-is-less-than-input-behavior)
* [Zones settings](add-new-edit-carrier.md#zones-settings-behavior)
* [Add new range button](add-new-edit-carrier.md#add-new-range-button-behavior)
* [Delete button](add-new-edit-carrier.md#delete-button-behavior)

### Add handling costs toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows choosing if the handling costs are added to the final price or not.

### Free shipping toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows choosing if the carrier is free or not.

### Billing radio buttons behavior

There are 2 radio buttons ([Forms radio buttons](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons)) are displayed: "According to total price." and "According to total weight.". When "According to total price" is selected, the ranges are defined by currency. The currency displayed is the default one configured in International > Localization. When "According to total weight" is selected, the ranges are defined by weight. The weight displayed is the one defined in International > Localization.

### Tax dropdown behavior

This is dropdown menu ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) that displays all the enabled tax rules existing in International > Taxes > Taxes rules.

### Out-of-range behavior dropdown behavior

This is dropdown menu ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) that allows to select one of the 2 options: "Apply the cost of the highest defined range" or "Disable carrier". \
If the total weight or total price of the cart is not in one of the defined ranges and if the chosen option is "Disable carrier", then the carrier will be disabled. If the total weight or total price of the cart is not in one of the defined ranges and if the chosen option is "Apply the cost of the highest defined range", then the carrier price will be the one corresponding to the highest range.

### Range Will be applied when the weight or currency  is >= input behavior

This is input ([Forms basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter weight or currency number when range starts.

### Range Will be applied when the weight or currency  is < input behavior

This is input ([Forms basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter weight or currency number when range finishes.\
If one of the ranges overlaps another, the following error message is displayed: "Ranges are overlapping" and the fields for all zones are disabled.

### Zones settings behavior

All the zones existing in International > Locations > Zones are displayed below in alphabetical order to chose zones for the range. \
Each zone has a checkbox ([Forms checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes)) allowing to enable its input field. Only numbers are allowed in zones fields, inputting any other symbol will result in the field being marked in red.\
The disabled zones are marked as inactive. When trying to go to the next step without selecting any zone the following error message is displayed: "Please select at least one zone".&#x20;

### Add new range button behavior

This is CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) once clicked, a new column of range setting is displayed. When hover mouse pointer on button, its color changes.\
When clicking on it and if one of the existing ranges isn't completed, the following message is displayed "Please validate the last range before creating a new one."

### Delete button behavior

This is CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) it appears under each added range. Once button clicked opens popup that has notification: _Are you sure to delete this range?_ and 2 buttons:

* OK -it is a blue color CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)), once clicked deletes range and closes popup.
* Cancel -it is outlined CTA button ([Buttons outlined UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked cancels deletion and closes popup.

When hover mouse pointer on each button, it color changes.

### Size, weight and group access step behavior

This step has elements:

* [Maximum package width (Dimension unit) input](add-new-edit-carrier.md#maximum-package-width-dimension-unit-input-behavior)
* [Maximum package height (Dimension unit) input](add-new-edit-carrier.md#maximum-package-height-dimension-unit-input-1)
* [Maximum package depth (Dimension unit) input](add-new-edit-carrier.md#maximum-package-depth-dimension-unit-input-behavior)
* [Maximum package weight (Dimension unit) input](add-new-edit-carrier.md#maximum-package-weight-dimension-unit-input-behavior)
* [Group access checkboxes](add-new-edit-carrier.md#group-access-checkboxes-behavior)

### Maximum package width (Dimension unit) input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter package width. The dimension unit mentioned in parenthesis is the one defined in International > Localization > Localization.

### Maximum package height (Dimension unit) input

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter package height. The dimension unit mentioned in parenthesis is the one defined in International > Localization > Localization.

### Maximum package depth (Dimension unit) input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter package depth. The dimension unit mentioned in parenthesis is the one defined in International > Localization > Localization.

### Maximum package weight (Dimension unit) input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter package weight. The weight dimension unit mentioned in parenthesis is the one defined in International > Localization > Localization.

### Group access checkboxes behavior

The ID and the name of all existing customers' groups are displayed. A checkbox ([Forms checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes)) is displayed before each group to select or unselect them. A global checkbox allows selecting/unselecting all customers' groups in one click.

### Summary step behavior

This step has elements:

* [Carrier information block](add-new-edit-carrier.md#carrier-information-block-behavior)&#x20;
* [Enabled toggle switch](add-new-edit-carrier.md#enabled-toggle-switch-behavior)

### Carrier information block behavior

The information about the carrier being created are displayed:

The carrier's price, the transit time, if the shipping costs are calculated according to the price or to the weight, the tax rule, the different ranges, the behavior if the weight or the price is higher than the defined ranges, the delivery zones, the customers' groups, and the shops are displayed.

### Enabled toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows to enable or disable created carrier.

## Multistores functionality

[Multistores independent](../../../../common-components/multistores-independent.md) page. Multistore functionality depends on Shop association block settings.&#x20;
