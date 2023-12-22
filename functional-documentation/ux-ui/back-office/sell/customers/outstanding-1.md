# Outstanding

## Description

This UI is shown after Enabling the _Enable B2B mode_ toggle switch in _CONFIGURE > Customer Settings_ and it allows to track the B2B customer behavior.

<figure><img src="../../../../../.gitbook/assets/image (65).png" alt="Outstanding User Interface"><figcaption><p>Outstanding User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../common-components/cancel-button.md)
* [E-commerce logo ](../../../common-components/e-commerce-logo.md)
* [Version number](../../../common-components/prestashop-version-number.md)
* [Quick access dropdown ](../../../common-components/quick-access-dropdown.md)
* [Search input](../../../common-components/search-input-field.md)&#x20;
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../common-components/account-icon.md)
* [Language dropdown for input fields](../../../common-components/language-dropdown-for-input-fields.md)
* [Save button](../../../common-components/save-button.md)
* [Cancel button](../../../common-components/cancel-button.md)
* [Sorting rules](../../../common-components/sorting-rules.md)

## Outstanding counting

The entries, that stored in this listing page, are produced by Visitor, Customer or Guest using Checkout process from Front-Office or adding a new Order in Back-Office.

## Configuration of the new B2B input fields in Customer edit page

Once the B2B mode is enabled, new input fields are displayed in the Customer edit page by navigating to _Customers > Customers_ and editing the desired Customer. Customer must be registered in Prestashop himself, or added by Administrator. New input fields are the following:

### **Allowed outstanding amount**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>0-9 numbers</td><td align="center">This field is invalid. </td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>19</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="outstanding-1.md#allowed-outstanding-amount-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Maximum number of payment days**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">Please enter a number.</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>9</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="outstanding-1.md#search-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Risk rating**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>None value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="outstanding-1.md#risk-rating-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Top UI elements of the Outstanding page

* **Outstanding** - page title.

## Main UI elements of the Outstanding page

### Top table elements

* **Outstanding** - table title with the total sum of outstanding entries.

### Filtering of the Outstanding page

* **Search ID** - input for searching a certain entry with ID.
* **Date widget** - allows filtering the entries for certain time range.
* **Customer** - ability to search and filter the customers.
* **Company** - ability to search and filter the company.
* **Risk** - dropdown element, allowing to arrange the risk priority values, and show only risk-prioritized Outstanding entries.
* **Outstanding allowance** - input for arranging appropriate entries for customers with the Outstanding amount.
* **Current outstanding, Invoice, Actions** - has no filtering function, only titles are displayed.

#### **Search CTA button**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">Please fill at least one field to perform a search in this list.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="outstanding-1.md#search-cta-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

* **Reset (X)** - after submission of the Filtering, there are the results shown in the table, together with the Reset and X icon. After pressing X, It resets the Filtering form.

### Table row elements of the Outstanding page

* **ID** - numeric ID value.
* **Date** - input with YYYY-MM-DD HH-MinMin-SecSec format.
* **Company** - customer with the company name.
* **Risk label** - the text with colorized outlined label, defining the Risk level of the entry.
* **Outstanding allowance amount** - the value with the numeric amount and currency prefix. Here is the limit displayed, that was set in Customer page and _Outstanding allowance_ field.
* **Current outstanding amount** - the value with the numeric amount and currency prefix. This functionality is working with the logic as follows:
  * All the invoiceable Tax included amount, that Customer has in total is reduced by all the invoiceable amount at the current time, that has Payment accepted status. The rest unpaid amount is displayed in this column. After all the Orders fully completed and accepted, this amount should be equal to 0.
* **Invoice sheet icon** - clicking initiates the download of the PDF invoice file.
* **View lasso icon** - clicking initiates redirection to the Order in Back-Office, that customer has made.

### Pagination of the Outstanding page

[Pagination](../../../common-components/pagination.md) type component.

## Behavior descriptions

### **Allowed outstanding amount behavior**&#x20;

Input can be filled with valid characters: 0-9 only. Default value is 0. If characters are typed as Latin letters, input erases the wrong text automatically. If there are more than 19 characters in the field, the instant error is displayed below the field - exclamation mark and message _This field is invalid._ Outstanding allowance amount allows setting the maximum purchase amount for the Customer, and to be included into the Outstanding list. Input is from the [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Maximum number of payment days behavior**&#x20;

Limit for Customer purchases in days. Default value is 0. If characters are typed as Latin letters, there will be a browser-type notification near the field, called _Please enter a number._ If there are more than 10 characters typed in this field, there will be a Prestashop error prompted. This feature allows setting the maximum days limit, in the Outstanding listing, that a Customer can be included in. Input is from the [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Risk rating behavior**&#x20;

Dropdown with the Risk values. Component from the [Dropdown Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics). The values appear as labels in the Outstanding listing table in the Risk column. The risk values are the following:

* **None** - label appearance is with black text and the green outlined color.
* **Low** - label appearance is with the black text and the orange outlined color.
* **Medium** - label appearance is with the white text and the red outlined color.
* **High** - label appearance is with the white text and the red outlined color.

### **Search CTA button behavior**&#x20;

Once there are no entries from none of the filtering fields, the Search CTA button is disabled, once there is at least one filtering value managed, the button becomes enabled. Component is from the [Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).

## Multistores functionality

This page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.
