# Summary

## Description

The purpose of this page is to summarize the information of carrier

<figure><img src="../../../../../../../.gitbook/assets/Capture d’écran 2023-03-06 à 16.47.58.png" alt=""><figcaption></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../../common-components/back-office-header/prestashop-version-number.md).
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../../common-components/back-office-header/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../../../common-components/multistore-component/shop-switcher-with-eye-icon.md).
* [Bell icon](../../../../../common-components/back-office-header/bell-icon.md)-[Toolbar UI KIT](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar)
* [Account icon](../../../../../common-components/back-office-header/account-icon.md).
* [Breadcrumbs navigation](../../../../../common-components/back-office-header/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/back-office-header/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../../common-components/back-office-header/help-button.md) - [Buttons Outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## The UI elements

### Enabled toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Enable the carrier in the front office.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="summary.md#enabled-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Summary step behavior

This step has elements:

* [Carrier information block](summary.md#carrier-information-block-behavior)&#x20;
* [Enabled toggle switch](summary.md#enabled-toggle-switch-behavior)

### Carrier information block behavior

The information about the carrier being created are displayed:

The carrier's price, the transit time, if the shipping costs are calculated according to the price or to the weight, the tax rule, the different ranges, the behavior if the weight or the price is higher than the defined ranges, the delivery zones, the customers' groups, and the shops are displayed.

### Enabled toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows to enable or disable created carrier.
