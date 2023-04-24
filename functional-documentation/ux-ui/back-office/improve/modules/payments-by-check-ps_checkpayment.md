# Payments by check (ps\_checkpayment)

## Description

This module configures the Payments by Check functionality in the webshop.

<figure><img src="../../../../../.gitbook/assets/image (11) (3).png" alt="Payment by Check configuration User Interface"><figcaption><p>Payment by Check configuration User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../common-components/back-office-header/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/back-office-header/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../common-components/forms/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/back-office-header/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/back-office-header/search-input-field.md)
* [Shop switcher with eye icon](../../../common-components/multistore-component/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/back-office-header/account-icon.md)&#x20;
* [Configuration block](../../../common-components/multistore-component/configuration-block.md)
* [Page header CTA buttons](../../../common-components/page-header-call-to-action-buttons-modules.md)

## Information alert

There is an [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) component notification message, containing a question mark icon and specific Payments by check icon. The text is:

_**This module allows you to accept payments by check.**_

_If the client chooses this payment method, the order status will change to 'Waiting for payment'._

_You will need to manually confirm the order as soon as you receive a check._

## Contact details block

The block starts with the mail-styled icon and the title _Contact details_.

### Payee

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The payee field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any characters</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="payments-by-check-ps_checkpayment.md#payee-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Address

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The "Address" field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any characters</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Address where the check should be sent to.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="payments-by-check-ps_checkpayment.md#address-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Payee behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. The detailed description about the payee. It will be noticed in the checkout process.

### Address behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. The detailed description about the address. It will be noticed in the checkout process.

## Multistores functionality

Page is [Multistores dependent](../../../common-components/multistore-component/multistores-dependent.md) page.
