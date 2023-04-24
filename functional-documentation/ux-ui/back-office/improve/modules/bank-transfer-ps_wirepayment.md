# Bank transfer (ps\_wirepayment)

This one of the most important modules is responsible for the secure payment transaction via the webshop.&#x20;

<figure><img src="../../../../../.gitbook/assets/image (5) (2).png" alt="Bank transfer UI"><figcaption><p>Bank transfer User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* [Bell icon](../../../common-components/bell-icon.md)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Configuration block](../../../common-components/configuration-block.md)
* [Page header CTA buttons](../../../common-components/page-header-call-to-action-buttons-modules.md)

## Information alert

There is an [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) component notification message, containing a question mark icon and a specific Bank transfer square icon. The text is:

_**This module allows you to accept secure payments by bank wire.**_

_If the client chooses to pay by bank wire, the order status will change to 'Waiting for Payment'._

_That said, you must manually confirm the order upon receiving the bank wire._

## Account details block

The block starts with the mail-styled icon and the title _Account details_.

### Account owner

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Account owner is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric and letter values</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="bank-transfer-ps_wirepayment.md#account-owner-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Account details

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Account details are required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric and letter values.</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Such as bank branch, IBAN number, BIC, etc.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="bank-transfer-ps_wirepayment.md#account-details-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Bank address

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric and letter values</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="bank-transfer-ps_wirepayment.md#bank-address">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Customization block

The block starts with the gear-styled icon and the title _Customization_.

### Reservation period

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric and letter values</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Number of days the items remain reserved</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="bank-transfer-ps_wirepayment.md#reservation-period">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Customer information

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric or letter values</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Information on the bank transfer (processing time, starting of the shipping...)</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="bank-transfer-ps_wirepayment.md#customer-information-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Display the invitation to pay in the order confirmation page

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Your country's legislation may require you to send the invitation to pay by email only. Disabling the option will hide the invitation on the confirmation page.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="bank-transfer-ps_wirepayment.md#display-the-invitation-to-pay-in-the-order-confirmation-page-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Account owner behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Defines the account owner identity.

### Account details behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) and [Forms Helpers UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers) components. Defines the Bank transfer account details.

### Bank address behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Defines the bank address details.

### Reservation period behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) and [Forms Helpers UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers) components. Displaying the reservation timing in customer information block.

### Customer information behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) and [Forms Helpers UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers) components. Displays the information about the Bank transfer processing details.

### Display the invitation to pay in the order confirmation page behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. In some countries, the only way for paying for the items, is after receiving the specific email. The email will be&#x20;

## Multistores functionality

Page is [Multistores independent](../../../common-components/multistores-independent.md) page.
