# Products in the same category (ps\_categoryproducts)

## Description

The module when enabled shows products for the customers in the Front office as recommended products which are in the same category.

<figure><img src="../../../../../.gitbook/assets/image (133).png" alt="Products in the same category User Interface"><figcaption><p>Products in the same category User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## Common components

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/back-office-header/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).&#x20;
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../common-components/module-page-specific-component/page-header-call-to-action-buttons-modules.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).&#x20;
* [Configuration block](../../../common-components/configuration-block.md).

## The UI elements

### Display products' prices toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Show the prices of the products displayed in the block.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="products-in-the-same-category-ps_categoryproducts.md#display-products-prices-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Number of product to display input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td></td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>16</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Show the prices of the products displayed in the block.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="products-in-the-same-category-ps_categoryproducts.md#number-of-product-to-display-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Title Settings** behavior

Title includes the title and settings icon.

### Display products' prices toggle switch behavior

This is a toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)), to enable or disable products' prices showing in the block.&#x20;

### Number of product to display input behavior

This is an input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter the number of products to display in block.  There only numbers should be allowed, trying to save with any other characters will result in error: [https://github.com/PrestaShop/PrestaShop/issues/28454](https://github.com/PrestaShop/PrestaShop/issues/28454)\
No error messages are presented, but when an incorrect character is entered, a message is shown when saving: "The settings have been updated." and the value is set to "0".

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.
