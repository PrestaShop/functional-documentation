# Monitoring

## Description

This UI shows the list of features, that needs the attention from administrator.

<figure><img src="../../../../../.gitbook/assets/image (19) (1) (1).png" alt="Monitoring UI"><figcaption><p>Monitoring User Interface</p></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/catalog/monitoring.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md)
* [Cancel button](../../../common-components/cancel-button.md)&#x20;
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [Version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/search-input-field.md)&#x20;
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)&#x20;
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Gear icon](../../../common-components/settings-wheel.md)

## Commercial pop-up block

At the first time, the once page is visited, there is a 808×295.867 pixels pop-up block, right after the Top UI section. The block has a commercial message containing the elements:

* **Closing icon (X)** - once the icon is clicked, the system stores information to Cookies, and the pop-up block is not showing again.
* **Focus on your catalog** - inspirational title of the pop-up block.
* **The text** says _Empty categories, disabled products, items that lack image or price... check the monitoring section to optimize your products management and make sure you forgot nothing._
* **Learn more CTA** - ghost button CTA, linking to a documentation page.

## The names of the sections

There are 7 sections for monitoring purposes. They are:

* **List of empty categories**
* **List of products with combinations but without available quantities for sale**
* **List of products without combinations and without available quantities for sale**
* **List of disabled products**
* **List of products without images**
* **List of products without description and summary**
* **List of products without price**

## Top section elements

### **Title of the section**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>-</td><td align="center">-</td><td></td></tr></tbody></table>

### **Gear icon**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#gear-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Notification**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#notification-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Arranging actions in sections

There are **ID**, **Reference**, **Name**, **Status**, **Actions** (**ID**, **Name**, **Description**, **Displayed**, **Actions** in the **List of empty categories** section) arrangement column titles on the top row of each table. Once those column titles are clicked, the table column will arrange the information using the A-Z and 1-9 scheme, then Z-A and 9-1 method will be shown on second click. This functionality is not affecting **Actions** column title click.

### **ID**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#id-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Reference**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#reference-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Name**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Displayed**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty dropdown</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#displayed-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Filtering actions in sections

### **Search ID field**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#search-id-field-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Search reference**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#search-reference-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Search name**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#search-name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Blank dropdown**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty dropdown</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#blank-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Search CTA**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled button</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Alt text "Search"</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#search-cta-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## The content elements in sections

### **Checkbox**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty checkbox</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#checkbox-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Number**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty checkbox</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#number-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Reference or Name**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#reference-or-name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Description or Name text**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td></td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>The name</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#description-or-name-text-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Enable or Disable toggle switch button**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#enable-or-disable-toggle-switch-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Pen icon**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#pen-icon-behavior">link to the behavior</a></td><td align="center">-</td><td> </td></tr></tbody></table>

### **Three-dot menu**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#three-dot-menu-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Search CTA**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Search</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#search-cta-behavior-2">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Reset (X)**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Not appearing</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="monitoring.md#reset-cta-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Pagination

The element stands in the bottom of all the sections, if there are more than 10 entries, it helps to edit and navigate through the enormous amount of entries in the table.

* **First page number value 1** - when there is the 1st page of the table displayed, the number will be greyed, once the user navigates to the further pages, the first number value becomes active.
* **Left arrow (<)** - initiates navigation through pages backwards.
* **Input field** - setting the desired number of page, clicking Enter or somewhere blank on UI, initiates the page changing.
* **Right arrow (>)** - initiates navigation through pages forward.
* **Biggest page number value** - displays the biggest number of pages in table.
* **Viewing {value}-{value} out of {value} (page {value} / {value})** - displays the current indication in page navigation.
* **Items per page** - displays possibility to change the maximum entries to show in one page - **10**, **20**, **50**, **100**.

## Behaviors descriptions

### **Title of the section behavior**&#x20;

Includes the title and the total number of available entries - those are displayed in brackets.

### **Gear icon behavior**&#x20;

It is a Gear style icon in the corner - top-right position of the section. This icon has a short rotation animation once clicked. Clicking on this icon, leads to dropdown **Refresh list** link with the rotation style icon. It refreshes the whole page.

### **Notification** **behavior**

Only List of empty categories section starts with informative blue-box notification with the information icon, with the text saying _An empty category is a category that has no product directly associated to it. An empty category may however contain products through its subcategories._.

### **ID** **behavior**

Unique identification of the entry. Arrange the list by ID.

### **Reference** **behavior**

Unique entry reference. Arrange the list by Reference. (**Name** - in List of empty categories only)

### **Name** **behavior**

Entry name description text. Arrange the list by Name. (**Description** - in List of empty categories only)

### **Displayed** **behavior**

Enabled toggle button or Disabled toggle button values arrangement. Arrange the list by shown or hidden entries. (**Status** - in List of empty categories only)

### **Search ID field behavior**&#x20;

A text input field with the placeholder _Search ID_, inputting number, clicking Search CTA, will filtrate the numeric results.

### **Search reference behavior**

A text input field with the placeholder _Search reference_, inputting letters, clicking Search CTA will filtrate the appropriate reference results (**Search name** - in List of empty categories only).

### **Search name** **behavior**

A text input field with the placeholder _Search name_, inputting letters, clicking Search CTA will filtrate the appropriate name results (**Search description** - in List of empty categories only)

### **Blank dropdown** **behavior**

A dropdown element, having Blank value by default, YES or NO value.

### **Checkbox** **behavior**

Category marking element which appears if there are more than 1 entries in a list.

### **Number** **behavior**

Unique number of the category.

### **Reference or Name** **behavior**

Unique reference or name displayed.

### **Description or Name text** **behavior**

Individual entry description or name text displayed.

### **Enable or Disable toggle switch button** **behavior**

By default, the button is Enabled on the entries. It enables showing or hiding the entry in Front-Office. Once the button is clicked, the notification will prompt in the top-right corner of the page UI - _The status has been successfully updated._

### **Pen icon** **behavior**

Clicking redirects to the edition of the element entry (**Magnifier icon** - redirects to the categories editing page - in the List of empty categories only).

### **Three-dot menu** **behavior**

Clicking shows dropdown with the options - **Edit**, which leads to entry editing page and **Delete**, which leads to the deletion action (only **Delete** - in List of empty categories section). After clicking **Delete**, the pop-up with confirmation text will appear named _Delete selection Are you sure you want to delete the selected item(s)?_ and two buttons - one ghost button to **Cancel** the action and red CTA button to **Delete** the desired entry. Delete confirmation _Successful deletion._ appears right after clicking the Delete, and pop-up closes right after clicking the Close button.

### **Search CTA** **behavior**

After clicking the button, the search results will be returned in the table. If there are no results found, there will be a black triangle icon with with a white exclamation mark displayed in table, and a small description above - _No records found_. X icon and _Reset_ near Search CTA indicates about resetting the search.

### Reset (X) behavior

Resets the search results back to empty search interface.

## Multistores functionality

This page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.

The listing is displayed separately from all the available Multistores in webshop, because of the separate databases in each Multistore.
