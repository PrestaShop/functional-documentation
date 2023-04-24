# Invoices

## Description

This UI displays the Invoices configuration page and allows generating the appropriate PDF invoices.

<figure><img src="../../../../../.gitbook/assets/image (102).png" alt="Invoices configuration User Interface"><figcaption><p>Invoices configuration User Interface</p></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/orders/invoices.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../common-components/cancel-button.md)
* [E-commerce logo ](../../../common-components/back-office-header/prestashop-logo.md)
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

## Top UI elements block

* **Invoices** - H1 class title for the page.

## By date block

This UI block provides the ability to download the PDF invoices of the selected range of time. After the download, the invoices are displayed page by page in a single document, if there are multiple PDF invoices.

* **Calendar icon and title By date** - title of the UI block.
* **Generate PDF file by date CTA** - once clicked, the PDF download will be executed.

### **From and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Format: 2011-12-31 (inclusive).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#from-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **To and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Format: 2011-12-31 (inclusive).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#to-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Date picking widget inputs with the calendar icons**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Current date displayed.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#date-picking-widget-inputs-with-the-calendar-icons-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## By order status block

This UI block provides the ability to download the PDF invoices of the selected order statuses. After the download, the invoices are displayed page by page in a single document, if there are multiple PDF invoices. Also, there are following components:

* **Clock icon and title By date** - title of the UI block.
* **Generate PDF file by status CTA** - once clicked, the PDF download will be executed.

### **Order statuses and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No checkboxes selected.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>You can also export orders which have not been charged yet.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#order-statuses-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Gear icon and Invoice options

No length limits for characters and no limits for special symbols are set on all configure input fields.

### **Enable invoices and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#behaviors-description">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Enable tax breakdown and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>If required, show the total amount per rate of the corresponding tax.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#enable-tax-breakdown-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Enable product image and **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Adds an image in front of the product name on the invoice.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#enable-product-image-and-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Invoice prefix and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>#IN</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Freely definable prefix for invoice number (e.g. #IN00001). </td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#invoice-prefix-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Add current year to invoice number**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#add-current-year-to-invoice-number-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Reset sequential invoice number at the beginning of the year

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#reset-sequential-invoice-number-at-the-beginning-of-the-year-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Position of the year date**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Radiobutton "After the sequential number"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#position-of-the-year-date-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Invoice number and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">Invalid invoice number.</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>The next invoice will begin with this number, and then increase with each additional invoice. Set to 0 if you want to keep the current number (which is #76).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#invoice-number-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Legal free text and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Use this field to show additional information on the invoice, below the payment methods summary (like specific legal information).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#legal-free-text-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Footer text and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This text will appear at the bottom of the invoice, below your company details.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#footer-text-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Invoice model and tooltip **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Value "invoice"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Choose an invoice model.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#invoice-model-and-tooltip-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Use the disk as cache for PDF invoices and **_**i**_** icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Saves memory but slows down the PDF generation.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="invoices.md#use-the-disk-as-cache-for-pdf-invoices-and-i-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### **From and tooltip **_**i**_** icon behavior**&#x20;

Once hovered, the tooltip is with the white-colored text in the dark box _Format: 2011-12-31 (inclusive)_. Component is from [Forms Input Gtoup UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group).

### **To and tooltip **_**i**_** icon behavior**

Once hovered, the tooltip is with the white-colored text in the dark box _Format: 2011-12-31 (inclusive)_. Component is from [Forms Input Gtoup UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group).

### **Date picking widget inputs with the calendar icons behavior**&#x20;

Once clicked on the date numbers, there will be a date picking widget pop-up.

### **Order statuses and tooltip **_**i**_** icon behavior**&#x20;

Once hovered, the tooltip is with the white-colored text in the dark box, _You can also export orders which have not been charged yet._ **Checkboxes, square icons with red or green backgrounds, and numeric values in the squares, Order status names** - the square background color indicates if there are some invoices in total counted for the certain Order status - square with green background. Or there are no invoices in total for the certain Order status - red square. The **total number of the invoices** are displayed in the squares. Checkboxes are from the [Forms Checkboxes UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes).

### **Enable invoices and tooltip **_**i**_** icon** behavior

Enables or disables Invoices, once the tooltip is hovered, there is a text in the dark box _If enabled, your customers will receive an invoice for the purchase._ Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Enable tax breakdown and tooltip **_**i**_** icon behavior**&#x20;

Enables or disables showing the Tax details in the Invoice, once the tooltip is hovered, there is a text in the dark box _If required, show the total amount per rate of the corresponding tax._ Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Enable product image and **_**i**_** icon** behavior

Enables or disables showing the product image in the Invoice, once the tooltip is hovered, there is a text in the dark box _Adds an image in front of the product name on the invoice_. Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Invoice prefix and tooltip **_**i**_** icon behavior**&#x20;

Input field where specific prefix, for Invoice can be set. The prefix will be displayed in the first characters of the Invoice file name and in the beginning of the Invoice number displayed. Once the tooltip is hovered, there is a text in the dark box _Freely definable prefix for invoice number (e.g. #IN00001)._ There is a dropdown with the arrow-down icon, where the prefix can be set for different languages. Component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Add current year to invoice number behavior**&#x20;

Adds a year to the Invoice number. Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### Reset sequential invoice number at the beginning of the year behavior

Adds sequential invoice number after year changes to the new. Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Position of the year date** behavior

And two radio button positions **After the sequential number** and **Before the sequential number** triggers the year date position display in Invoices. Component is from the [Forms Radio Buttons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons).

### **Invoice number and tooltip **_**i**_** icon behavior**&#x20;

Input field, where the numeric value can be typed. The typed number will indicate the beginning number of the Invoices numbers arrangement. Once the tooltip is hovered, there is a text in the dark box _If the value is 0, then the arrangement will remain the default. The next invoice will begin with this number, and then increase with each additional invoice. Set to 0 if you want to keep the current number (which is #25)._ Component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Legal free text and tooltip **_**i**_** icon behavior**&#x20;

Input field where additional fee explanation text can be added. Once the tooltip is hovered, there is a text in the dark box _Use this field to show additional information on the invoice, below the payment methods summary (like specific legal information)._ Also, different texts for different languages can be saved, by using the language dropdown. Component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Footer text and tooltip **_**i**_** icon** behavior

Input field, where footer text can be displayed. Once the tooltip is hovered, there is a text in the dark box _Use this field to show additional information on the invoice, below the payment methods summary (like specific legal information)._ Also, different texts for different languages can be saved, by using the language dropdown. Component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Invoice model and tooltip **_**i**_** icon** behavior

Dropdown field, where 2 types of Invoices can be selected - **invoice** or **invoice-b2b**. Once the tooltip is hovered, there is a text in the dark box, _Choose an Invoice model._ Component is from the [Forms Selects UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--selects).

### **Use the disk as cache for PDF invoices and **_**i**_** icon behavior**&#x20;

Enable or Disable the function, to use the host capacity to cache the PDF invoices. Once the tooltip is hovered, there is a text in the dark box _Once the tooltip is hovered\_Saves memory but slows down the PDF generation._ Component is from the [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.

Each Multistore has its separate webshop databases. It means, one configuration on one Multistore or Shop group will not affect the other Multistore or Shop group.
