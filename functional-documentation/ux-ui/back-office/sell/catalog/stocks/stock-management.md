# Stock management

## Description

This page shows all the stock of the products that are in the shop, also it can be configured from this page.

<figure><img src="../../../../../../.gitbook/assets/image (20).png" alt="Stock management User Interface"><figcaption><p>Stock management User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/catalog/stocks.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Sorting rules](../../../../common-components/sorting-rules.md).
* [Pagination](../../../../common-components/pagination.md).

## The UI elements

### Search input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">No product matches your search. Try changing search terms.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Search products (search by name, reference, supplier)</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="stock-management.md#search-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Search a supplier input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Placeholder: Search a supplier</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="stock-management.md#search-by-supplier-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Export icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Export data into CSV</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="stock-management.md#export-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Import icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Go to the import system</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="stock-management.md#import-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Bulk edit quantity input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">Use checkboxes to bulk edit quantities.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numbers allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="stock-management.md#bulk-edit-quantity-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Search input behavior

This is search input with helper ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers)). This input has Search CTA button. All entered words are converted into tags. Search button click splits the tags. Even one symbol can be converted into tag. \
Once clicked Search, it executes the searching action after the fields are set and shows search results in table. \
When hover mouse pointer on it, buttons color changes.

### Advanced filters behavior

It is a drop-table with a placeholder "Advanced filters", when pressed, a table below appears with the following elements:

* Filter by supplier, this section had a search by supplier input, and 2 check boxes ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)). If any of the checkboxes are marked, only the products from those suppliers will be shown, also the selected check box appears as a text box that can be removed in the search bar. By default there are: "Fashion supplier" and "Accessories supplier".
* Filter by categories, this section has an option to expand, and collapse, when collapsed, has the following checkbox:
  * Home\
    When expanded the following additional checkboxes appear: - Clothes - Men - Women - Accessories - Stationery - Home accessories - Art\
    When any of the checkboxes are pressed, below only the selected filtered categories are shown.
* Filter by status,there are three radio buttons ([Forms radio buttons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons)) options, only one can be selected:
  * Enabled (selected by default)
  * Disabled
  * All

### Search by supplier input behavior

This is input field with placeholder ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) for product search by supplier.

### Export icon behavior

When icon clicked, the CSV file can be saved.

### Import icon behavior

When icon clicked, in a new window opens the the window Advanced Parameters -> Import.

### Display products below low stock level first checkbox behavior

On the top of list a checkbox ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)) is shown: Display products below low stock level first, when pressed, re-arranges the products so that the low stock products would be shown first.

### Bulk edit quantity input behavior

On the left there is **Bulk edit quantity** number input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) with checkbox ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)), when the checkbox is marked, all the products get marked. There are also arrows for number increasing or decreasing.

When a number is entered in the field and the checkbox is marked, every product's below "Physical" and "Available" sections have an additional arrow appeared on the right of them with a new number, that the amount would be increased to. The number that will be increased depends on the "Bulk edit quantity" field entered number.

When a number in the "Bulk edit quantity" is entered, **Apply new quantity** button with edit icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) become enabled. When this button clicked, the quantities will be added to the products, with a message shown: _Stock successfully updated_.

### Products list behavior

There are these products elements in the each row of the list:

* Checkbox -  ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)) to mark product for bulk actions. When marked in product row, also become marked Bulk edit quantity checkbox.
* ID - shows product ID number.
* Product name - shows picture and the name of the product.
* Reference - shows reference of the product.
* Supplier - shows the supplier of product.
* Status - shows if product is disabled or enabled.
* Physical - shows physical quantity of product.
* Reserved - shows reserved quantity of product.
* Available - shows available quantity of product.
* Edit quantity - input field ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) for a number of quantity editing. Has 2 arrows for increasing and decreasing.

## Multistores functionality

[Multistores dependent](../../../../common-components/multistores-dependent.md) page.
