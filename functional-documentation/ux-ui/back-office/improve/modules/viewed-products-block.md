# Viewed products block

## Description

This is the module to show recently viewed products for the customers in product page.

<figure><img src="../../../../../.gitbook/assets/image (34).png" alt="Viewed products block User Interface"><figcaption><p>Viewed products block User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).&#x20;
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../common-components/page-header-call-to-action-buttons-modules.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).&#x20;
* [Configuration block](../../../common-components/configuration-block.md).

## The UI elements

### Products to display input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numbers allowed</td><td align="center">Invalid number.</td><td></td></tr><tr><td>Default value</td><td>8</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Define the number of products displayed in this block.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="viewed-products-block.md#products-to-display-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Title of Settings behavior

This title includes the title and settings icon.&#x20;

### Products to display input behavior

This is number input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter number of viewed products to display in front office.

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.
