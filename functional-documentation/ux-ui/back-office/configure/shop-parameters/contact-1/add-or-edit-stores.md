# Add or Edit Stores

## Description

The "Add or Edit Stores" feature in Prestashop allows you to manage multiple stores from a single dashboard. You can use this feature to add new stores, edit existing store details, and configure the settings for each store.

When you add a new store, you can specify the store name, URL, and other relevant information. You can also select the language and currency that will be used for that store.

If you need to edit an existing store, you can modify the store's name, URL, language, and other settings. You can also manage the products, categories, and other content that is specific to that store.

Overall, the "Add or Edit Stores" feature in Prestashop makes it easy to manage multiple stores and customize the settings for each store. This is useful if you have different stores targeting different regions, or if you want to offer different product lines in each store.

<figure><img src="../../../../../../.gitbook/assets/image (113).png" alt="Add or Edit stores UI"><figcaption><p>Add or Edit stores User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/contact/stores.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../../common-components/e-commerce-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;
* [Cancel button](../../../../common-components/cancel-button.md)
* [Checkmark navigation CTA buttons](../../../../common-components/checkmark-navigation-cta-buttons.md)

## Contacts / Stores Tabs

There are 2 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* **Contacts**
* **Stores** (active)

## Stores block

The block starts with a house-style icon, and the title _Stores_.

### Name

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">The field name is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric and latin characters allowed only with spaces and %s</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled address name.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Store name (e.g. City Center Mall Store). Allowed characters: letters, spaces and %s</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limi</td><td>255</td><td align="center">Your entry in field name (language English (English)) exceeds max length 255 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Address

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field address1 is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All symbols like $%# etc. are forbidden.</td><td align="center">The address1 field is invalid.</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">Your entry in field address1 (language English (English)) exceeds max length 255 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#address-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Address (2)

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All symbols like $%# etc. are forbidden.</td><td align="center">The address2 field is invalid.</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">Your entry in field address2 (language English (English)) exceeds max length 255 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#address-2-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Zip/Postal code

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">A Zip/Postal code is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values only allowed.</td><td align="center">Your Zip/Postal code is incorrect. It must be entered as follows: 00000</td><td></td></tr><tr><td>Default value</td><td>Prefilled zip of the random address.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>4</td><td align="center">Your Zip/Postal code is incorrect. It must be entered as follows: 00000</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#zip-postal-code-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### City

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any characters, but not symbols like $#@ etc.</td><td align="center">This field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">The city field is too long (64 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#city-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Country

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#country-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### State (if country has states)

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">An address located in a country containing states must have a state selected.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#state-if-country-has-state-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Latitude / Longitude

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Latitude and longitude are required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values only allowed.</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled numeric / latin characters input.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Store coordinates (e.g. 45.265469/-47.226478).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>13</td><td align="center">The latitude field is too long (13 chars max).<br>The longitude field is too long (13 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#latitude-longitude-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Phone

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values only allowed.</td><td align="center">The phone field is invalid.</td><td></td></tr><tr><td>Default value</td><td>Random prefilled phone number or empty.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>16</td><td align="center">The phone field is too long (16 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#phone-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Fax

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Random prefilled fax number or empty.</td><td align="center">The fax field is invalid.</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>16</td><td align="center">The fax field is too long (16 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#fax-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Email address

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">The email field is invalid.</td><td></td></tr><tr><td>Default value</td><td>Random prefilled email or empty field.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">The email field is too long (255 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#email-address-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Note

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric or any other characters allowed.</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty of prefilled from the earlier entries.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#note-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Active

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Whether or not to display this store.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#active-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Picture

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>gif, jpg, jpeg, jpe, png, webp are allowed only.</td><td align="center">Image format not recognized, allowed formats are: gif, jpg, jpeg, jpe, png, webp</td><td></td></tr><tr><td>Default value</td><td>Uploaded thumbnail already, or no thumbnail.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>File size 8.779kb</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Storefront picture.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-stores.md#picture-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Hours and weekdays

Example text _e.g. 10:00AM - 9:30PM_ and Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday input fields.

## Behavior descriptions

### Name behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the name of the store.

### Address behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the address of the store.

### Address (2) behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the second address of the store.

### Zip/Postal code behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the postal code of the store.

### City behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the city name of the store.

### Country behavior

[Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component. This input field allows filling the country name of the store.

### State (if country has state) behavior

[Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component. This input field allows filling the country's state of the store.

### Latitude / Longitude behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the latitude or longitude coordinates of the store.

### Phone behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the phone number of the store.

### Fax behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the fax number of the store.

### Email address behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling the email address of the store.

### Note behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. This input field allows filling additional information note of the store.

### Active behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This component Enables or Disables the store's information displaying.

### Picture behavior

Browse input field, where a file can be added directly from the local machine computer. Clicking the Add file button ([Buttons With Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) or the input field itself, shows the window from the local machine, with the file selection window modal.

### Shop association behavior

This association block lets user choose, which Multistores can be affected with the settings changes. This component uses a [Checkmark navigation CTA buttons](../../../../common-components/checkmark-navigation-cta-buttons.md) common component.behavior

### Hours and weekday behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) components. Many input fields, all the representing the weekday working hourly range.

## Multistores functionality

This configuration page is [Multistores independent](../../../../common-components/multistores-independent.md) page.
