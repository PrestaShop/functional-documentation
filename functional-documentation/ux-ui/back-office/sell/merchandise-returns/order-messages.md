# Order Messages

## Description

This UI shows the list of messages, that were sent by webshop customer, who created an Order. By default, _Delay_ message is already created in the list.

<figure><img src="../../../../../.gitbook/assets/image (6) (1).png" alt="Order Messages UI"><figcaption><p>Order Messages User Interface</p></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customer-service/order-messages.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../common-components/cancel-button.md)&#x20;
* [E-commerce logo ](../../../common-components/e-commerce-logo.md)
* [Version number](../../../common-components/prestashop-version-number.md)
* [Quick access dropdown ](../../../common-components/quick-access-dropdown.md)
* [Search input ](../../../common-components/search-input-field.md)
* Shop switcher with eye icon (todo link)
* Bell icon (todo link)
* Trophy icon (todo link)
* Account icon (todo link)

## Top UI section

### **Add new order message CTA button**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Add new order message</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-messages.md#add-new-order-message-cta-button-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Top Order messages section elements

* **Title of the section** - includes the title and the total number of available entries - those are displayed in brackets.
* **Gear icon** - it is a Gear style icon in the corner - top-right position of the section. This icon has a short rotation animation once clicked. Clicking on this icon, leads to dropdown block:
* **Refresh list** - the link with the rotation style icon. It refreshes the whole page.
* **Show SQL query** - the link with double left-right arrows. It prompts the SQL query popup.
* **Export to SQL Manager** - the link with server icon. It redirects to **Prestashop SQL Manager**.
* **Bulk actions dropdown** - it is disabled by default, once there is a Order message element selected, Bulk actions become enabled. The only action is **Delete** action, by clicking **Delete selected** dropdown. After clicking **Delete**, the pop-up with confirmation text will appear named _Delete selection Are you sure you want to delete the selected item(s)?_ and two buttons - one ghost button to **Cancel** the action and red CTA button to **Delete** the desired entry. Delete confirmation _The selection has been successfully deleted._ appears right after clicking the **Delete**, and pop-up closes right after clicking the **Close** button.

## Sorting&#x20;

There are **ID**, **Name**, **Message** arrangement column titles on the top row of the table. Once those column titles are clicked, the table column will arrange the information using the A-Z and 1-9 scheme, then Z-A and 9-1 method will be shown on second click. This functionality is not affecting **Actions** column title click. These components are from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

* **ID** - unique identification of the entry. Arrange the list by ID.
* **Name** - entry name description text. Arrange the list by Name.
* **Message** - the message text content displayed.

## Filtering actions in section

### **Search ID field**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Placeholder</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-messages.md#search-id-field-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Search name**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Placeholder</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-messages.md#search-name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Search CTA**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Search</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-messages.md#search-cta-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## The content element in section

* **Checkbox** - entry marking element.
* **Number** - unique number of the entry.
* **Name** - unique name displayed.
* **Message** - individual entry description or name text displayed.
* **Three-dot menu** - clicking shows dropdown with the option **Delete**, which leads to the deletion action. After clicking **Delete**, the pop-up with confirmation text will appear named _Delete selection Are you sure you want to delete the selected item(s)?_ and two buttons - one ghost button to **Cancel** the action and red CTA button to **Delete** the desired entry. Delete confirmation _Successful deletion._ appears right after clicking the Delete, and pop-up closes right after clicking the Close button.

### ​Pen icon (Edit)

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Edit</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-messages.md#pen-icon-editing-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

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

### **Add new order message CTA button behavior**

This button, with plus icon (+), initiates the redirection to a new page, where a separate Order message creation form is displayed.

### Pen icon (Editing) behavior

Clicking redirects to the edition page of the element entry.

### **Search ID field behavior**

A text input field with the placeholder _Search ID_, inputting number, clicking Search CTA, will filtrate the numeric results. This component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Search name behavior**

A text input field with the placeholder _Search name_, inputting letters, clicking Search CTA will filtrate the appropriate name result. This component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### **Search CTA behavior**&#x20;

By default the button is disabled. Once there is something typed in the Filtering fields, the button becomes active. After clicking the button, the search results will be returned in the table. If there are no results found, there will be a black triangle icon with with a white exclamation mark displayed in table, and a small description above _No records found_. X icon and _Reset_ near Search CTA indicates about resetting the search. This component is from [Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).

## Multistores functionality

This page is Multistore independent page.

The listing is displayed the same for all the available Multistores in webshop, switching the Multistores shows the same Order messages listing.
