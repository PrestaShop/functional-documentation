# Outstanding

## Description

In PrestaShop, the Outstanding page is a feature that allows merchants to showcase their top-selling products or most popular products on a dedicated page. This page can be accessed through the main menu of the website and typically displays product images, names, and prices.

The Outstanding page is designed to increase visibility for products that are performing well and to make it easier for customers to find them. This can help increase sales and improve the overall user experience for shoppers on the website.

In order to use the Outstanding page feature in PrestaShop, merchants need to enable it in the backend of their store and select the products they want to feature on the page. They can also customize the layout and appearance of the page to match the look and feel of their website.

This UI is shown after Enabling the _Enable B2B mode_ toggle switch in _CONFIGURE > Customer Settings_, and it allows tracking the B2B customer behavior.

<figure><img src="../../../../../.gitbook/assets/image (6).png" alt="Outstanding User Interface - empty table"><figcaption><p>Outstanding UI - empty table</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (21).png" alt="Outstanding User Interface - filled entries"><figcaption><p>Outstanding UI - filled entries</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers/outstanding.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Configuration block](../../../common-components/configuration-block.md)
* [Cancel button](../../../common-components/cancel-button.md)
* [Pagination](../../../common-components/pagination-with-input.md)

## Outstanding counting

The entries, that stored in this listing page, are produced by Visitor, Customer or Guest using Checkout process from Front-Office or adding a new Order in Back-Office.

## Configuration of the new B2B input fields in Customer edit page

Once the B2B mode is enabled, new input fields are displayed in the Customer edit page by navigating to _Customers > Customers_ and editing the desired Customer. Customer must be registered in Prestashop himself, or added by Administrator. New input fields are the following:

### **Allowed outstanding amount**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values only allowed.</td><td align="center">This field is invalid.</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Valid characters: 0-9</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>19</td><td align="center">{numeric_value}is invalid. Please enter an integer lower than or equal to{numeric_value}</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="outstanding.md#allowed-outstanding-amount-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Maximum number of payment days**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values only allowed.</td><td align="center">This field is invalid.</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Valid characters: 0-9</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">{numeric_value}is invalid. Please enter an integer lower than or equal to{numeric_value}</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="outstanding.md#maximum-number-of-payment-days-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Risk rating**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>None value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="outstanding.md#risk-rating-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Top UI elements of the Outstanding page

The section starts with the title _Outstanding_ and the total entries counted in brackets.

### Filtering of the Outstanding page

The table is from the [Tables Sortable UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--sortable) and the [Tables with Filters UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--with-filters) components.

* **Search ID** - input for searching a certain entry with ID. ([Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal))
* **Date widget** - allows filtering the entries for certain time range. ([Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal))
* **Customer** - ability to search and filter the customers. ([Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal))
* **Company** - ability to search and filter the company. ([Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal))
* **Risk** - dropdown element, allowing to arrange the risk priority values, and show only risk-prioritized Outstanding entries. ([Dropdown Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics))
* **Outstanding allowance** - input for arranging appropriate entries for customers with the Outstanding amount. ([Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal))
* **Current outstanding, Invoice, Actions** - has no filtering function, only titles are displayed.
* **Search CTA button** - a [Button Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics) component. Once there are no entries from none of the filtering fields, the Search CTA button is disabled, once there is at least one filtering value managed, the button becomes enabled.
* **Reset (X)** - after submission of the Filtering, there are the results shown in the table, together with the Reset and X icon. After pressing X, It resets the Filtering form.

### Table row elements of the Outstanding page

* **ID** - numeric ID value.
* **Date** - input with _YYYY-MM-DD HH-MinMin-SecSec_ format.
* **Company** - customer with the company name.
* **Risk label** - the text with colorized outlined label, defining the Risk level of the entry.
* **Outstanding allowance amount** - the value with the numeric amount and currency prefix. Here is the limit displayed, that was set in Customer page and _Outstanding allowance_ field.
* **Current outstanding amount** - the value with the numeric amount and currency prefix. This functionality is working with the logic as follows:
  * All the invoiceable Tax included amount, that Customer has in total is reduced by all the invoiceable amount at the current time, that has Payment accepted status. The rest unpaid amount is displayed in this column. After all the Orders fully completed and accepted, this amount should be equal to 0.
* **Invoice sheet icon** - clicking initiates the download of the PDF invoice file.
* **View lasso icon** - clicking initiates redirection to the Order in Back-Office, that customer has made.

## Behavior descriptions

### **Allowed outstanding amount behavior**

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Input can be filled with valid characters: 0-9 only. Default value is 0. If characters are typed as Latin letters, input erases the wrong text automatically. If there are more than 19 characters in the field, the instant error is displayed below the field - exclamation mark and message _This field is invalid._ Outstanding allowance amount allows setting the maximum purchase amount for the Customer, and to be included into the Outstanding list.

### **Maximum number of payment days behavior**

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Limit for Customer purchases in days. Default value is 0. If characters are typed as Latin letters, there will be a browser-type notification near the field, called _Please enter a number._ If there are more than 10 characters typed in this field, there will be a Prestashop error prompted. This feature allows setting the maximum days limit, in the Outstanding listing, that a Customer can be included in.

### **Risk rating behavior**

[Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component. Dropdown with the Risk values. The values appear as labels in the Outstanding listing table in the Risk column. The risk values are the following:

* **None** - label appearance is with black text and the green outlined color.
* **Low** - label appearance is with the black text and the orange outlined color.
* **Medium** - label appearance is with the white text and the red outlined color.
* **High** - label appearance is with the white text and the red outlined color.

## Multistores functionality

This page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.
