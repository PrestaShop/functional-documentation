# Information about customer

## Description

This page displays all informations about a customer, divided into 13 panels

[Customers related tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers.html)

TODO&#x20;

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers.html)

## Components description

This section MUST describe each component one by one

### Common components

* [heading-of-the-page.md](../../../../common-components/heading-of-the-page.md "mention")
* [help-button.md](../../../../common-components/help-button.md "mention")

### Components

Panels are [UI/KIT Tables](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--basic) each representing an information group pertaining to the customer

### **General informations**

#### **Panel Header**

The panel header is divided into two section

1. **The left part** of the header is the panel title. The panel title is composed of the following informations in the presented order :\
   \[Customer's first name]\[Customer's last name]\[\[Customer's ID]] - \[Customer's email address]\
   The customer's email address is clickable and redirects to "mailto:customersemailaddress"
2. **The right part** of the header is an edit button that redirects to \[specs of the add edit customer]\(\{{\<ref "add-edit-customer.md">\}} "Add edit customer")

#### **Panel body**

* Social title: if the title is not input, just shows "Unknown"
* Age: if the birthdate is not input, just shows "Unknown"
* Registration date
* Last visit : date&#x20;
* Shop: shows the shop that the customer is registered on
* Language
* Registrations: shows the possible registrations, Newsletter and Partner Offers
  * the possibles registrations are displayed in a green badge with a white check if the customer is registered
  * the possibles registrations are displayed in a red badge with a white cross if the customer is not registered
* Latest Update
* Status: shows if the customer's account is enabled
  * If the customer's account is enabled a green badge is displayed with a green check and the label "Active"
  * If the customer's account is disabled a red badge is displayed with a white cross and the label "Inactive"
* If the customer is a guest, the button "Transform to a customer account" is present in this panel

### **Orders**

#### **Panel header**

The panel header displays the title **Orders** followed by a blue badge with the total number of orders of the customer.

#### **Panel body**

\
The panel body displays 3 sections :

* A callout with the number of valid and invalid orders. The total amount spent for the valid orders is displayed in the default currency of the shop
* A table of the valid orders
* A table of the invalid orders

Both table have the same following columns :

* ID
* Date
* Payment
* Status
* Products
* Total spent
* Actions (redirects to [orders](../../../orders/ "mention"))

### **Carts**

#### **Panel header**

The panel header displays the title **Carts** followed by a blue badge with the total number of carts of the customer.

#### **Panel body**

\
The panel displays all the customer's carts as a table with the following columns :

* ID
* Date
* Carrier
* Total
* Action (redirects to @carts)

### **Purchased products**

#### **Panel header**

The panel header displays the title **Purchased products** followed by a blue badge with the total number of products purchased by the customer.



#### **Panel body**

\
The panel displays all the products purchased by the customer as a table with the following columns :

* Date : purchase date
* Name : name of the product as a link that redirects to the order containing the product
* Quantity : quantity purchased



### **Viewed products**

#### **Panel header**

The panel header displays the title **Viewed products** followed by a blue badge with the total number of products viewed but not purchased by the customer.

#### **Panel body**

The panel displays all the products viewed but not purchased by the customer as a table with the following columns :

* ID : product's id
* Name : name of the product as a link that redirects to the product's front office page

### **Private note**

#### **Panel header**

The panel header displays the title **Add a private note**

#### **Panel body**

The panel displays :

* A callout with the text "This note will be displayed to all employees but not to customers."
* A text input field
  * If it is empty, a placeholder text is displayed. The placeholder is "Add a note on this customer. It will only be visible to you."
  * If a note was input, it displays the note
* A save button

### **Messages**

#### **Panel header**

The panel header displays the title **Messages** and the number of messages in a blue badge

#### **Panel body**

\
The panel displays a table of messages sent by the customer. The table has the following columns :

* Status : status of the conversation between the customer and you
* Message : preview of the beginning of the message as a link that redirects to the message
* Sent on : displays the date and time the message was sent on\
  If no messages were sent by the customer, displays "\[customer name] has never contacted you" instead of the table.



### **Vouchers**



#### **Panel header**

The panel header displays the title **Vouchers** and the number of vouchers in a blue badge

#### **Panel body**

\
The panel displays a table of vouchers linked to the customer. The table has the following columns :

* ID : voucher ID
* Code : voucher code if a code was defined, empty otherwise
* Name : voucher name
* Status : voucher status, appears as a green check if the status on the voucher page was toggled to Yes. In case of a nominative voucher, the voucher disappears from the list if the status on the voucher page was toggled to No
* Qty available : available quantity usable for a voucher (i.e : 2 means that the voucher can be used twice)
* Actions :
  * Edit button : redirects to the voucher edit page
  * Three points button : opens a menu with the delete option
    * Delete : prompts a pop-up to confirm the delete or exit the voucher delete process

If no vouchers are linked to the customer, displays "\[customer name] has no discount vouchers" instead of the table.

### **Last emails**

#### **Panel header**

The panel header displays the title **Last emails** and the number of vouchers in a blue badge

#### **Panel body**

\
The panel displays a table of emails sent to the customer. The table has the following columns :

* Date : date and time the last email was sent on
* Language : shop language the email is linked to
* Subject : email subject
* Template : email template used to send the email (i.e : payment, invoice, etc.)

If no emails were sent to the customer, displays "No records found" instead of the table.

### **Last connections**

#### **Panel header**

The panel header displays the title **Last connections** and the number of connections in a blue badge

#### **Panel body** 

The panel displays a table of the last connections of the customer. The table has the following columns :

* ID : connection ID
* Date : date of the last connection
* Pages viewed : number of pages viewed during this instance
* Total time : total time spent connected during this instance
* Origin : origin of the connection
* IP address : IP address used to connect to the shop

If the customer has never logged into their account the panel **Last connections** is not present on the page



### **Groups**

#### **Panel header**

The panel header displays the title **Groups** and the number of customer groups the customer is a member of in a blue badge. The right part of the panel header displays an edit button that redirects to \[specs of the add edit customer]\(\{{\<ref "add-edit-customer.md">\}} "Add edit customer")



#### **Panel body** 

The panel displays a table of groups the customer is a member of The table has the following columns :

* ID : group ID
* Name : group name as a link that redirects to the group's edit page



### **Addresses**



#### **Panel header**

The panel header displays the title **Addresses** and the number of addresses of the customer is a member of in a blue badge. The right part of the panel header displays an "+" button that redirects to the customer addresses creation page

#### **Panel body** 

The panel displays a table of the addresses of the customer. The table has the following columns :

* ID : address ID
* Company : customer's company
* Name : customer's name
* Address : customer's address
* Country : address' country
* Phone number : phone number linked to the address
* Actions :
  * Edit button : redirects to the voucher edit page
  * Three points button : opens a menu with the delete option
    * Delete : prompts a pop-up to confirm the delete or exit the voucher delete process

If the customer has no address, the panel displays "\[Customer name] has not registered any addresses yet"

*   **Wishlist**

    The panel header displays the title **Wishlist** and the number of items in the wishlists in a blue badge.

## Behaviors description

### Workflow

This page proposes 3 workflows :&#x20;

* Accessing the [Broken link](broken-reference "mention") page
* [convert-a-guest-customer-to-a-registered-customer.md](../../../../../business-rules/customers/convert-a-guest-customer-to-a-registered-customer.md "mention")(BR)
* Adding a private note to a customer

### Behavior description

* Adding a private note to a customer can be done by inputting text in the resizable text input of the specific panel then clicking save. Private notes will only be visible to employees
