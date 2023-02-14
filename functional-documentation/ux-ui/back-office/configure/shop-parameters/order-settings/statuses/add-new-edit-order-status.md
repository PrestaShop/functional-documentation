# Add new / edit order status

## Description

This page allows adding or editing the Order statuses which are managed in the Orders listing page.&#x20;

<figure><img src="../../../../../../../.gitbook/assets/image (4) (3) (1).png" alt=""><figcaption><p>Order status Add or Edit User Interface</p></figcaption></figure>

## Common components

* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../../../common-components/help-button.md) - [Buttons outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Save button (todo link) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* Cancel button (todo link) - [Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Language switcher near the input field (todo link)
* Color picker (todo link when done)

## Tab selection

Selection is defined with the [Navigation navigation tabs UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-tabs). Statuses tab is selected by default in this page.

## Order status section

The section contains a clock icon, a title _Order status_ in the header and the whole content down the header.&#x20;

### Status name field

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field name is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Invalid characters: numbers and !&#x3C;>,;?=+()@#"{}_$%:</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty field</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Order status (e.g. 'Pending'). Invalid characters: numbers and !&#x3C;>,;?=+()@#"{}_$%:</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">Your entry in field name (language English (English)) exceeds max length 64 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-order-status.md#behavior-of-the-status-name-field">Behavior</a></td><td align="center">-</td><td>Language switcher</td></tr></tbody></table>

### Language switcher

(common component todo link).

### Icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All graphical extensions: JPG, GIF, PNG.</td><td align="center">Image format not recognized, allowed formats are: .gif, .jpg, .png</td><td></td></tr><tr><td>Default value</td><td>Empty field</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Upload an icon from your computer (File type: .gif, suggested size: 16x16).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">Your entry in field name (language English (English)) exceeds max length 64 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-order-status.md#behavior-of-the-icon">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Color title

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>#ffffff</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Status will be highlighted in this color. HTML colors only. "lightblue", "#CC6600")</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-order-status.md#color-picker-component-behavior">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Checkboxes with the particular settings

There are particular statements from [Forms Checkboxes UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes). Those statements can apply to the particular Order status. Once the checkbox or the sentence is clicked, the statement will be enabled after clicking Save CTA button. Once the checkbox or the sentence is clicked once again, the statement will be disabled after clicking Save CTA button. The statements are with the explanations:

* Consider the associated order as validated.
* Allow a customer to download and view PDF versions of his/her invoices.
* Hide this status in all customer orders.
* Send an email to the customer when his/her order status has changed.
* Attach invoice PDF to email.
* Attach delivery slip PDF to email.
* Set the order as shipped.
* Set the order as paid.
* Show delivery PDF.

### Cancel button

Cancel button CTA (common component link todo)

### Save button

Save button CTA (common component link todo)



## Behaviors descriptions

Add figma link here ( [Tristan Lehot](https://app.gitbook.com/u/wxuQ8dEUfYTsCcCBbcFmmedKE5t2 "mention"))

### Behavior of the Status name field

The field belongs to the [Forms normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal). This field defines the name of the old or the new Order status. Once the field is filled, clicking Save will store the name.

### Behavior of the Icon

This component is from [Forms files UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files). The icon of the can be updated or added to the particular Order status. Once the graphical element is selected from the native machines' Browse popup, clicking OK and then Save in Prestashop will store the icon.

### Color picker component behavior

Color picker (todo common component link when merge)

## Multistores functionality

[Multistores dependent](../../../../../common-components/multistores-dependent.md) page.
