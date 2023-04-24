# Link List (Link Widget)

## Description

This UI shows the Link Widget management UI. It helps to manage and edit various webshop links, that are shown in static Front-Office pages, as well as in Pages section in Back-Office. By default, there is a single Footer widget with the links already installed in the webshop.

<figure><img src="../../../../../.gitbook/assets/image (101).png" alt="Link list User Interface"><figcaption><p>Link list User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/design/link-widget.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher](../../../common-components/shop-switcher.md).
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Sorting rules](../../../common-components/sorting-rules.md).
* [Pagination](../../../common-components/pagination.md).

## The UI elements

### **(+) New block button**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Alt text when hovered -  "New block"</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="link-list-link-widget.md#+-new-block-cta">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### **(+) New block button behavior**&#x20;

This is CTA button ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) which initiates adding a new Widget List (Link List) to the listing.

### Header of the widget table behavior

**Header of the widget table** - it contains the hook name like **displayFooter** and the table functionality name like **Footer** together, with the numbers in brackets, containing, how much entries are there in the single widget.

### Table column headers behavior

* **ID** - shows all the unique numeric values of the block.
* **Name of the block** - shows all the names of the blocks in a single widget.
* **Position** - shows the number of position in a widget.

### Content of the widget table behavior

* **Number** - value, indicating the ID.
* **Name of the block** - unique alphabetic value.
* **Position** - number value of link position.
* **Pen icon** - redirects to the block editing form page.
* **Three-dot menu** - clicking on the dots, the UI shows a dropdown with a **Delete** value. When click on Delete, opens popup with question _Delete selected item?_ and buttons: \
  OK ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)) once clicked deletes the item a message is shown: _Successful deletion_. \
  Cancel ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) once clicked cancels deletion and closes popup.

## Multistores functionality

This page is [Multistores dependent ](../../../common-components/multistores-dependent.md)page. This module does not allowed in all shops context. It should be configured in each shop separately in multistore.
