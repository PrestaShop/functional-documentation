# Search Engines

## Description

This UI lists the Prestashop Search Engines entries.

<figure><img src="../../../../../../.gitbook/assets/image (18) (2).png" alt="Search Engines User Interface"><figcaption><p>Search Engines User Interface</p></figcaption></figure>

## QA <a href="#common-components" id="common-components"></a>

[Link to test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/trafic-and-seo/search-engines.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../../common-components/cancel-button.md)
* [E-commerce logo ](../../../../common-components/back-office-header/prestashop-logo.md)
* [Version number](../../../../common-components/prestashop-version-number.md)
* [Quick access dropdown ](../../../../common-components/quick-access-dropdown.md)
* [Search input](../../../../common-components/search-input-field.md)&#x20;
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)
* [Language dropdown for input fields](../../../../common-components/language-dropdown-for-input-fields.md)
* [Save button](../../../../common-components/save-button.md)
* [Cancel button](../../../../common-components/cancel-button.md)
* [Sorting rules](../../../../common-components/sorting-rules.md)

### Meaning of this page

Once the visitors are accessing the webshop, some of them come from Search Engines, like Google. Google Search Engine is added in the listing by default, after the Prestashop installation. The purpose of this page is to gather all the available Search Engines, that Prestashop can recognize. Then the shop administrators can manage those queries, and can be informed, where the visitors are coming from.

### Default Search Engines

There are 38 default Search Engines stored in Prestashop already:

* Google
* Aol
* Yandex
* Ask.com
* Nhl.com
* Yahoo
* Baidu
* Lycos
* Exalead
* Search.live
* Voila
* Altavista
* Bing
* Daum
* Eniro
* Naver
* Msn
* Netscape
* Cnn
* About
* Mamma
* Alltheweb
* Virgilio
* Alice
* Najdi
* Mama
* Seznam
* Onet
* Szukacz
* Yam
* Pchome
* Kvasir
* Sesam
* Ozu
* Terra
* Mynet
* Ekolay
* Rembler

### Top UI elements

* **(+) Add new search engine** - CTA button for adding a new Search Engine entry. Component is from [Button Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* **Tabs** - component is from [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) and for Traffic & SEO menu:
  * SEO & URLs.
  * Search Engines - highlighted tab.
  * Referrers.

### Middle elements - Search Engines table

This parent component is containing a [4 table header tools Common Component](search-engines.md#description)&#x20;

* **Search Engines** - table title with.
* **Numeric value** - total sum of Search Engines identified.
* **Plus icon** - the same as **(+) Add new search engine** CTA button in top-right UI - adds new Search Engine entry.
* **Export icon** - when clicked, a file is generated with all **displayed** Search Engines from the data list in CSV format.
* **Refresh** - once clicked, the whole page reloads to display the latest data.

### Filtering

* **ID** - input field, for searching and filtering specific Search Engine by ID.
* **Server** - input field, for searching and filtering specific Search Engine Server by name.
* **GET variable** - input field, for searching and filtering specific GET request variable by name.

### **Search button**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">Please fill at least one field to perform a search in this list.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="search-engines.md#search-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

* **Reset** - resets the filtering, shows all the unfiltered Search Engines entries.

### Listing

* **Number** - ID of the entry.
* **Server name** - name of the Search Engine.
* **Letter or other string** - specific value, included in request syntax.
* **Edit button with dropdown** - allows to edit the Search Engine or delete it.

### Bulk Actioning

Dropdown actions contain:

* **Select all** - selecting all the Search Engine items.
* **Unselect all** - unselecting all the Search Engine items.
* **Delete selected** - deletes the certain selected Search Engine items.

A screenshot for the new checkbox : ![](<../../../../../../.gitbook/assets/image (13).png>)&#x20;

### Pagination

This page contains [Pagination](../../../../common-components/pagination.md) common component details.

The pagination can be selected by using the navigation widget, with the numbers and left and right sided arrows on the bottom-right of the UI. Search Engines lists can be displayed as 20, 50, 100, 300 and 1000 entries in a one page, by using a dropdown at the bottom-center of the UI.

## Behavior descriptions

### Search button behavior

Executes the filtering action, shows the results. If the button is clicked without filling the filter inputs, the UI will be prompted with the warning message _Please fill at least one field to perform a search in this list._

## Multistores functionality

This page is Multistores independent page. (todo link)

Once the entry of Search Engine is added in separate Multistore, it affects all the rest of Multistores in the same way. The management will be done in all Multistores simultaneously.
