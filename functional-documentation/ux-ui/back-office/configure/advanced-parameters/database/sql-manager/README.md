# SQL Manager

## Description

This is page that allows to explore a database using the SQL language.

<figure><img src="../../../../../../../.gitbook/assets/image (27).png" alt="SQL Manager User Interface"><figcaption><p>SQL Manager User Interface</p></figcaption></figure>

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

## The UI elements

### Add new SQL query button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Add new SQL query</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#add-new-sql-query-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Setting wheel icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Settings</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#setting-wheel-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Select your default file encoding dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>utf-8</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#select-your-default-file-encoding-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Add new SQL query button behavior

This is CTA button with plus icon ([Buttons with icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), once clicked it opens new SQL query creation page. When hover mouse pointer on it, button color changes.

### Blue alert message behavior

This is blue alert message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) and it is: \
_How do I create a new SQL query?_

* _Click "Add new SQL query"._
* _Fill in the fields and click "Save"._
* _You can then view the query results by clicking on the "View" action in the dropdown menu._
* _You can also export the query results as a CSV file by clicking on the "Export" button._

### Yellow alert message behavior

This is yellow alert message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) and it is: \
_When saving the query, only the "SELECT" SQL statement is allowed._

### Title of SQL Manager list behavior

It contains title and number of SQL queries in brackets. by default number in brackets is 0, because no SQL queries are created. In the block instead of list is notification: _No records found._

### Setting wheel icon behavior

Once clicked this icon opens po up with these options:&#x20;

* Refresh list
* Show SQL query
* Export to SQL Manager

### Title of Settings block behavior

It contains title and setting wheel icon.

### Select your default file encoding dropdown behavior

This is dropdown (Dropdowns basics UI kit) choose default file encoding option. There are 2 options in dropdown: utf-8 and iso-8859-1.

## Multistores functionality

[Multistores dependent](../../../../../common-components/multistores-dependent.md) page.
