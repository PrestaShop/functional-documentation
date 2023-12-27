# Add new SQL query

## Description

This page allows to create or edit SQL query. Created SQL queries are shown in SQL Manager page.

<figure><img src="../../../../../../../.gitbook/assets/image (39) (1).png" alt=""><figcaption><p>Add new SQL query User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../../../common-components/account-icon.md).
* [Shop switcher](../../../../../common-components/shop-switcher.md).
* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* [Cancel button](../../../../../common-components/cancel-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).

## The UI elements

### SQL query name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-sql-query.md#sql-query-name-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### SQL query input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-sql-query.md#sql-query-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### List of MySQL Tables dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>List of MySQL table</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-sql-query.md#list-of-mysql-tables-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Notification message behavior

This is blue alert message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) and it is: \
_Note that this feature is available in all shops context only. It will be added to all your stores._

### SQL query block behavior

This block contains two mandatory input fields:

* [SQL query name input](add-new-sql-query.md#sql-query-name-input-behavior)
* [SQL query input](add-new-sql-query.md#sql-query-input-behavior)

### SQL query name input behavior

This is a field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter SQL query name.&#x20;

### SQL query input behavior

This is a field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter SQL query.&#x20;

### List of MySQL Tables block behavior

This block contains these elements:

* [List of MySQL Tables dropdown](add-new-sql-query.md#list-of-mysql-tables-dropdown-behavior)
* [Add table name to SQL query button](add-new-sql-query.md#add-table-name-to-sql-query-button-behavior)

### List of MySQL Tables dropdown behavior

This is dropdown (Dropdowns basics UI kit) of MySQL tables to select MySQL table.&#x20;

### Add table name to SQL query button behavior

This is CTA button with plus icon ([Buttons with icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), once clicked it adds selected MySQL table title to SQL query input.

### List of attributes for this MySQL table block behavior

By default this block is empty and has blue alert message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) and it is: \
_Please choose a MySQL table_

When select MySQL table in List of MySQL Tables dropdown its attributes are shown in this block list. Each attribute has name, type and Action columns.

## Multistore functionality

[Multistores independent](../../../../../common-components/multistores-independent.md) page.
