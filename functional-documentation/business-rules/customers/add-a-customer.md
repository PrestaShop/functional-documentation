# Add a customer

## Description

A customer can be added to your shop through multiple avenue. Adding a customer to your shop is related to the "Create" action on the customers database table.

Adding a customer creates an instance of a customer that can be either a **Guest** or a **Registered** customer. If a customer is **Registered**, it's possible to set their status as either _Enabled_ or _Disabled_, meaning they will either be able or unable to login into their customer's account on your shop. A customer created in the BO is automatically considered **Registered.**

A new customer created in the shop's BO must have at least :&#x20;

* A first name -> Only letters and the dot (.) character, followed by a space, are allowed.
* A last name -> Only letters and the dot (.) character, followed by a space, are allowed.
* An email address
* A password
* A group access selected

The fields of the form follow input rules :&#x20;

* A first name -> Only letters and the dot (.) character, followed by a space, are allowed.
* A last name -> Only letters and the dot (.) character, followed by a space, are allowed.
* An email address -> must follow the classic email format "XYZ@ABC.DEF"
* A password -> must have at least a "Strong" security score and be between 8 and 72 characters long
* Birthdate -> must be complete with a year, a month and a day otherwise it will be considered invalid
* A group access selected -> must have at least 1 group checked

When a new customer is created in the shop's FO, a customer will have a delivery/invoice address on top of these informations.

## Impacted pages

* [customers-list.md](../../ux-ui/back-office/sell/customers/customers-list.md "mention")
* [creating-a-new-customer.md](../../ux-ui/back-office/sell/customers/customers/creating-a-new-customer.md "mention")

## Behat test

[Github link](https://github.com/PrestaShop/PrestaShop/blob/develop/tests/Integration/Behaviour/Features/Scenario/Customer/customer\_management.feature)
