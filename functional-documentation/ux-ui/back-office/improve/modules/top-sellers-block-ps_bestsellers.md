# Top-sellers block (ps\_bestsellers)

## Description

This is the main configuration page for the module that configures the product items number, that is showed in the top-sellers block.

<figure><img src="../../../../../.gitbook/assets/image (1) (4) (2).png" alt="Top-sellers block UI"><figcaption><p>Top-sellers block User Interface</p></figcaption></figure>

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

## Settings block

### Products to display

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>8</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Determine the number of product to display in this block</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="top-sellers-block-ps_bestsellers.md#products-to-display-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Products to display behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number) component. This small input declares the number of products to display in the top-seller block.

## Multistores functionality

[Multistores dependent](../../../common-components/multistore-component/multistores-dependent.md) page.

####
