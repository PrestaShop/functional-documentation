# Supplier list

## Description

When module is enabled and configured, it will displays the possible suppliers accordingly to the settings configured in Front office.

<figure><img src="../../../../../.gitbook/assets/image (117).png" alt="Supplier list module User Interface"><figcaption><p>Supplier list module User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## Common components

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/back-office-header/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../common-components/module-page-specific-component/page-header-call-to-action-buttons-modules.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).&#x20;
* [Configuration block](../../../common-components/configuration-block.md).

## The UI elements

### Type of display dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Use a plain-text list</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="supplier-list.md#type-of-display-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Number of elements to display input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center"></td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>5</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Only apply in plain-text mode</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="supplier-list.md#number-of-elements-to-display-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Title Settings** behavior

Title includes the title and settings icon.

### Type of display dropdown behavior

This is a dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) that allows to choose how suppliers should be listed in Front office. It has these options:

* Use a plain-text list
* Use a drop-down list

### Number of elements to display input behavior

This is an input with helper text ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers)) for the numbers of elements that the module will display in Front office. It should allow only numbers but allows all characters, check the link [here](https://github.com/PrestaShop/PrestaShop/issues/28684).

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.
