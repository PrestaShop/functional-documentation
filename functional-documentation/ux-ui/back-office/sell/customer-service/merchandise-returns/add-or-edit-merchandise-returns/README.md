# Add or Edit Merchandise Returns

## Description

This functionality able to make a return action of purchased goods via Prestashop. It is described as _Return Merchandise Authorization (RMA)_. All the Editing page UI elements are described below.

<figure><img src="../../../../../../../.gitbook/assets/image (13) (1) (4).png" alt="Add or Edit Merchandise Returns UI"><figcaption><p>Add or Edit Merchandise Returns UI</p></figcaption></figure>

## QA <a href="#common-components" id="common-components"></a>

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customer-service/merchandise-returns.html)

## Components description <a href="#common-components" id="common-components"></a>

### Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Save button (todo link)
* Cancel button (todo link)

### **Customer**&#x20;

The details of the customer - first and last name, and link to the Customer profile.

### **Order**&#x20;

&#x20;the exact date when order was created by the customer, as well as link to the exact order in Order page.

### **Customer explanation**&#x20;

Text area, where customer can provide big amount of text as explanation to the PrestaShop administrators.



### **Status**&#x20;

Several statuses, used to give the udpate to the applying customer:&#x20;

The statuses are the following:

* **Waiting for confirmation** - the status is set by default at the first action, when customer requests a return.
* **Waiting for package** - the status, indicating that the Prestashop merchant is waiting for the returning pack from the customer. Once the status is changed, the customer gets notificaiton about the status change.
* **Package received** - the status, indicating that the Prestashop merchant has received the returning pack from the customer. Once the status is changed, the customer gets notificaiton about the status change.
* **Return denied** - the status, indicating that the Prestashop merchant is denied the returning pack from the customer. Once changed, the customer gets notificaiton about the status change.
* **Return completed** - the status, indicating that the Prestashop merchant has completed the return case of the pack from the customer. Once changed, the customer gets notificaiton about the status change.



### **Products**&#x20;

The list of products in the return package displayed in a listing UI. There are :&#x20;

* _Reference_
* _Product name_
* &#x20;_Quantity_,&#x20;
* _Action_ : [Delete CTA ](./#delete)

### **Returns form**&#x20;

specific PDF invoice document, showing the details about the request of the return, appears for downloading, only when the customer requests for a return of the goods, and the Prestashop merchant sets the Status of return to _Waiting for package_. The PDF contains Billing and Delivery Address, message, that Prestashop has logged the return request, the deadline when the package must be returned, return number, date. Items to be returned list, reference, quantity, following conditions declarations, if the conditions are not met.

## Behaviors description

### **Cancel**&#x20;

Cancels all the Edit UI, redirects to the Merchandise Return list.

### **Save**&#x20;

Saves the single Merchandise Return Editing configuration.

* If the editing of the return is successful - once updating the return status - the UI will be prompted with the message:\
  _Successful update._
* If there is a deletion attempt from the Return Package list, when only 1 item is in the list, the UI will be prompted with the message:\
  _You need at least one product._

### **Delete**  <a href="#deletecta" id="deletecta"></a>

Deletes the product from the return list package.



## Multistores compatibility

This page is [Multistores dependent](../../../../../common-components/multistores-dependent.md) page.

Merchandise Editing functionality is separately maintained by each separate multistore shop. It means, that all the Merchandise Returns and Orders are managed separately in each multistore, by switching the Multistore Switcher to the appropriate shop. _All Shops_ view context is also available, it is comfortable to see all the Merchandise Returns in one list from all the shops.
