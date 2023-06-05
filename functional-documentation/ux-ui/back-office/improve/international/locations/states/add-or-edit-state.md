# Add or Edit State

## Description

This page is for editing the existing or adding a new one State to the webshop localization.

<figure><img src="../../../../../../../.gitbook/assets/image (3) (2).png" alt="Add or Edit State UI"><figcaption><p>Add or Edit State User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/international/locations/states.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../../common-components/account-icon.md)&#x20;
* [Cancel button](../../../../../common-components/cancel-button.md)
* [Save button](../../../../../common-components/save-button.md)

## Zones / Countries / States Tabs

There are 3 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* **Zones**
* **Countries**&#x20;
* **States** (active)

## Notifications

If the webshop is on All shops context, there will be a blue notification message ([Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) _Note that this feature is available in all shops context only. It will be added to all your stores._

## States section

The block starts with the globe-style icon and the title _States_.

### Name

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The name field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty field.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Provide the state name to be displayed in addresses and on invoices.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limi</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-state.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### ISO code

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The iso_code field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Symbols like @#$ etc. are forbidden.</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled address name.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>1 to 4 letter ISO code. You can prefix it with the country ISO code if needed.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limi</td><td>Max 4 characters</td><td align="center">The iso_code field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-state.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Country

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Argentina, or other editing value.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Country where the state is located. Only the countries with the option "contains states" enabled are displayed.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limi</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-state.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Zone

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Africa, or other editing value.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Geographical region where this state is located.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limi</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-state.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Status

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-state.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Name behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows naming the State.

### ISO code behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows naming the ISO code.

### Country behavior

[Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component. This input field allows defining the country for the State.

### Zone behavior

[Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component. This input field allows defining the zone for the State.

### Status behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This component Enables or Disables the State showing in the webshop.

## Multistores functionality

This page is [Multistores dependent](../../../../../common-components/multistores-dependent.md) page.
