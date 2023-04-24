# Update a customer

## Description

A customer can be updated from the BO.

Updating a customer allows the user to modify the customer's information. The fields follow the same rules as they do in the BR [add-a-customer.md](add-a-customer.md "mention") :

* A first name -> Only letters and the dot (.) character, followed by a space, are allowed.
* A last name -> Only letters and the dot (.) character, followed by a space, are allowed.
* An email address -> must follow the classic email format "XYZ@ABC.DEF"
* A password -> must have at least a "Strong" security score and be between 8 and 72 characters long
* Birthdate -> must be complete with a year, a month and a day otherwise it will be considered invalid
* A group access selected -> must have at least 1 group checked

## Impacted pages

* [customers.md](../../ux-ui/back-office/sell/customers/customers.md "mention")
* [editing-customer.md](../../ux-ui/back-office/sell/customers/customers/editing-customer.md "mention")

## Behat test

[Github link](https://github.com/PrestaShop/PrestaShop/blob/develop/tests/Integration/Behaviour/Features/Scenario/Customer/customer\_management.feature)
