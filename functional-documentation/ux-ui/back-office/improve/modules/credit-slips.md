# Credit slips

## Description

An agreement document, generated right after the return of the product. After the merchant receives the product or item back from the buyer, a Credit Slip (sometimes a Credit Note or etc.) must be created. All the Slips are only listed in this section.

<figure><img src="../../../../../.gitbook/assets/image (4) (6).png" alt="Credit Slips User Interface, when there are no Slips"><figcaption><p>Credit Slips User Interface, when there are no Slips</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (2) (4) (1).png" alt="Credit Slips User Interface, when there are at least one Slip"><figcaption><p>Credit Slips User Interface, when there is at least one Slip</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/orders/credit-slips.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/search-input-field.md)
* [Shop switcher](../../../common-components/shop-switcher.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)
* [Settings wheel](../../../common-components/settings-wheel.md)
* [Save button](../../../common-components/save-button.md) - [Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* [Sorting rules](../../../common-components/sorting-rules.md)
* [Language dropdown for input fields](../../../common-components/language-dropdown-for-input-fields.md)

## Credit Slips listing table

The table begins with the table Title, and total Slips counted in the brackets. At the top right position, it is the [Settings Wheel](credit-slips.md#settings-wheel) component.&#x20;

The table is from [Tables Sortable UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--sortable), as well as the filtering is from [Tables With Filters UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--with-filters).

### Sorting the table

Sorting in the table works as [Sorting rules](../../../common-components/sorting-rules.md) functionality. The sorting elements are:

* **ID**
* **Order ID**
* **Date issued**
* **PDF**

### Search ID

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty field with placeholder "Search ID"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="credit-slips.md#search-id-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Order ID

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty field with placeholder "Search order ID"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="credit-slips.md#order-id-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Date issued

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder YY-MM-DD</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="credit-slips.md#date-issued-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Search CTA button

At the first state, the Search CTA is in Disabled button state ([Buttons Disabled UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--disabled)). After typing anything into the input fields in filtering, the Search CTA button becomes Enabled ([Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)).&#x20;

### Download credit slip CTA button

_Download credit slip_ CTA button from the [Buttons With Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). Every entry in the row has this button on the right. Once clicked, it instantly initiates downloading of the PDF document.

## By date section

The block begins with the title _By date_ and a calendar icon near the title.

### From

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Current date</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Format: 2011-12-31 (inclusive).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="credit-slips.md#from-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### To

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Current date</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Format: 2011-12-31 (inclusive).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="credit-slips.md#to-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Generate PDF file by date CTA button

Clicking the button ([Button Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)) initiates the PDF document downloading into the local machine.

## Credit slip options section

The section starts with a title _Credit slip options_ and a gear-type icon nearby.

### Credit slip prefix

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Prefix used for credit slips.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="credit-slips.md#credit-slip-prefix-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Search ID behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Once the input field is filled with the search request, and Search CTA is clicked, the block will return the searched results. If there are no search results returned, there will be a message with an exclamation mark _No records found_. And there will be a Disabled Search CTA and an _X Reset_ link displayed, which resets the search request.

### Order ID behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Once the input field is filled with the search request, and Search CTA is clicked, the block will return the searched results. If there are no search results returned, there will be a message with an exclamation mark _No records found_. And there will be a Disabled Search CTA and an _X Reset_ link displayed, which resets the search request.

### Date issued behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Placeholders inside the inputs with the date formatting and once clicked, it will transform into the YYYY-MM-DD current date format. After click in the date field, the date picker context block will appear, with availability to choose the particular date range.

### From behavior

[Forms Helpers UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers) component. Placeholders inside the inputs with the date formatting and once clicked, it will transform into the YYYY-MM-DD current date format. After click in the date field, the date picker context block will appear, with availability to choose the particular date range.

### To behavior

[Forms Helpers UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers) component. Placeholders inside the inputs with the date formatting and once clicked, it will transform into the YYYY-MM-DD current date format. After click in the date field, the date picker context block will appear, with availability to choose the particular date range.

### Credit slip prefix behavior

[Forms Helpers UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--helpers) component. Availability to add a custom prefix for a Credit Slip filename.&#x20;

## Multistores functionality

This page is [Multistores independent](../../../common-components/multistores-independent.md) page.
