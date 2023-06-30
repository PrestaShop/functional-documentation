# Add or Edit Merchandise Returns

## Description

This functionality able to make a return action of purchased goods via Prestashop. It is described as _Return Merchandise Authorization (RMA)_. All the Editing page UI elements are described below.

## Components description <a href="#common-components" id="common-components"></a>

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customer-service/merchandise-returns.html)

## Components description <a href="#common-components" id="common-components"></a>

<figure><img src="../../../../../../../.gitbook/assets/image (83).png" alt="Add or Edit Merchandise Return User Interface"><figcaption><p>Add or Edit Merchandise Return User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customer-service/merchandise-returns.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md)
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md)
* [Quick access dropdown](../../../../../common-components/back-office-header/quick-access-dropdown.md)
* [Search input](../../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../../common-components/account-icon.md)&#x20;
* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [Cancel button](../../../../../common-components/cancel-button.md) -  [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## The UI elements&#x20;

### Status dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Current return status </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Merchandise return (RMA) status.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#status-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Customer** behavior

Shows the details of the customer - first and last name, and _View details on the customer page_ link to the Customer profile.

### **Order behavior**&#x20;

Shows the exact date when order was created by the customer, as well as _View details on the order page_ link to the exact order in Order page.

### **Customer explanation** behavior

Shows the explanation for the return that was entered by customer when requested the return.

### **Status** dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with several statuses, used to give the update to the applying customer. By default is shown the current return status.

The statuses are the following:

* **Waiting for confirmation** - the status is set by default at the first action, when customer requests a return.
* **Waiting for package** - the status, indicating that the PrestaShop merchant is waiting for the returning pack from the customer. Once the status is changed, the customer gets notification about the status change.
* **Package received** - the status, indicating that the PrestaShop merchant has received the returning pack from the customer. Once the status is changed, the customer gets notification about the status change.
* **Return denied** - the status, indicating that the PrestaShop merchant is denied the returning pack from the customer. Once changed, the customer gets notification about the status change.
* **Return completed** - the status, indicating that the PrestaShop merchant has completed the return case of the pack from the customer. Once changed, the customer gets notification about the status change.

### **Products** behavior

The list of products in the return package displayed in a listing UI. Under list is helper text: _List of products in return package_. \
There are these elements in the list:&#x20;

* _Reference_
* _Product name_
* _Quantity_
* _Action_ : [Delete button](./#delete-button-behavior)

### Delete button behavior&#x20;

This is CTA button with X icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). When hover mouse pointer on it, button's color changes. Once clicked button deletes the product from the list.\
If there is a deletion attempt from the Return Package list, when only 1 item is in the list, redirects the user to Merchandise returns list page with the notification message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)): _You need at least one product._

### **Returns form** behavior

This is specific PDF invoice document, showing the details about the request of the return, appears for downloading, only when the customer requests for a return of the goods, and the PrestaShop merchant sets the Status of return to _Waiting for package_. The PDF contains Billing and Delivery Address, message, that PrestaShop has logged the return request, the deadline when the package must be returned, return number, date. Items to be returned list, reference, quantity, following conditions declarations, if the conditions are not met.\
There is helper text under document: _The link is only available after validation and before the parcel gets delivered._

## Multistores compatibility

This page is [Multistores dependent](../../../../../common-components/multistores-dependent.md) page.

Merchandise Editing functionality is separately maintained by each separate multistore shop. It means, that all the Merchandise Returns and Orders are managed separately in each multistore, by switching the Multistore Switcher to the appropriate shop. _All Shops_ view context is also available, it is comfortable to see all the Merchandise Returns in one list from all the shops.
