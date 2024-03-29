# Top-sellers block (ps\_bestsellers)

## Description

This is the module to show top-selling products for the customers in homepage.

<figure><img src="../../../../../.gitbook/assets/image (1) (4) (2).png" alt="Top-sellers block UI"><figcaption><p>Top-sellers block User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/modules/ps-bestsellers.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Configuration block](../../../common-components/configuration-block.md)
* [Page header CTA buttons](../../../common-components/page-header-call-to-action-buttons-modules.md)

## Settings block

### Products to display

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>8</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Determine the number of product to display in this block</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="top-sellers-block.md#products-to-display-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Products to display behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number) component. This small input declares the number of products to display in the top-seller block.

## Multistores functionality

## Behavior

#### Save - Call to action

<figure><img src="../../../../../.gitbook/assets/image (17).png" alt="Top-sellers block User Interface"><figcaption><p>Top-sellers block User Interface</p></figcaption></figure>

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

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>When anything apart numbers is saved, resets the value to "0"</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>8</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Determine the number of product to display in this block</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="top-sellers-block.md#products-to-display-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Title of Settings behavior

This title includes the title and settings icon.&#x20;

### Products to display input behavior

This is number input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter number of products to display in front office.

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.
