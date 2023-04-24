# Link Widget (Link Widget)

## Description

This UI shows the Link Widget management UI. It helps to manage and edit various webshop links, that are shown in static Front-Office pages, as well as in Pages section in Back-Office. By default, there is a single Footer widget with the links already installed in the webshop.

<figure><img src="../../../../../.gitbook/assets/image (2) (6) (1).png" alt="Link Widget (Link Widget) User Interface"><figcaption><p>Link Widget (Link Widget) User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Save button (todo link)
* Save and Stay button (todo link)
* Cancel button (todo link)
* E-commerce logo (todo link)
* Version number (todo link)
* Quick access dropdown (todo link)
* Search input (todo link)
* Shop switcher with eye icon (todo link)
* Bell icon (todo link)
* Trophy icon (todo link)
* Account icon (todo link)

## Top UI elements

### **(+) New block**&#x20;

### &#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Alt text when hoverd -  "New block"</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="link-widget-link-widget.md#+-new-block-cta">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

The widgets are displayed as 2 in a one row. Each widget has its specific UI elements.

## Widget UI elements

### Header of the table

* **Header of the widget table** - it contains the hook name and the table functionality name together, with the numbers in brackets, containing, how much entries are there in the single widget.

### Table column headers

* **ID** - shows all the unique numeric values of the block.
* **Name of the block** - shows all the names of the blocks in a single widget.
* **Shop** - shows all the webshop shop names, separated in comma, if there are multpile.

Sorting Tules can be found [HERE](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/LBfyCScRUjOVa2zoG5Ub/functional-documentation/ux-ui/common-components/sorting-rule)

### Content of the widget

* **Number** - value, indicating the ID.
* **Name of the block** - unique alphabetic value.
* **Shop name** - alphabetic value of the shop names, that are maintained in the webshop.
* **Pen icon** - redirects to the block editing form page.
* **Three-dot menu** - clicking on the dots, the UI shows a dropdown with a **Delete** value.

### Bottom of the widget

Pagination stands in the bottom of the sections, if there are more than 10 entries, it helps to edit and navigate through the enormous amount of entries in the table.

* **First page number value 1** - when there is the 1st page of the table displayed, the number will be greyed, once the user navigates to the further pages, the first number value becomes active.
* **Left arrow (<)** - initiates navigation through pages backwards.
* **Input field** - setting the desired number of page, clicking Enter or somewhere blank on UI, initiates the page changing.
* **Right arrow (>)** - initiates navigation through pages forward.
* **Biggest page number value** - displays the biggest number of pages in table.
* **Viewing {value}-{value} out of {value} (page {value} / {value})** - displays the current indication in page navigation.
* **Items per page** - displays possibility to change the maximum entries to show in one page - **10**, **20**, **50**, **100**.

## Behavior descriptions

### **(+) New block CTA behavior**&#x20;

Initiates adding a new Widget List (Link List) to the listing.

## Multistores functionality

This page is [Multistores dependent ](../../../common-components/multistores-dependent.md)page.
