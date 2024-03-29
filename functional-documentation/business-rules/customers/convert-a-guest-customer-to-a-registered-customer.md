# Convert a guest customer to a registered customer

## Description

A guest customer created in the FO can be transformed in a registered customer in the BO.

When visiting the page [information-about-customer.md](../../ux-ui/back-office/sell/customer-service/add-or-edit-merchandise-returns/information-about-customer.md "mention")of a guest customer, a button "Transform to a customer account" is available.

When clicking on this button :&#x20;

* A random password is generated
* An email is sent to the customer
* The customer is moved from the **Guest** customer's group to the **Customer** customer's group
* The button "Transform to a customer account" disappears from the page [information-about-customer.md](../../ux-ui/back-office/sell/customer-service/add-or-edit-merchandise-returns/information-about-customer.md "mention")

## QA

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers.html)

## Impacted pages

* [customers](../../ux-ui/back-office/sell/customers/customers/ "mention")
* [information-about-customer.md](../../ux-ui/back-office/sell/customer-service/add-or-edit-merchandise-returns/information-about-customer.md "mention")

## Behat test

[Github link](https://github.com/PrestaShop/PrestaShop/blob/develop/tests/Integration/Behaviour/Features/Scenario/Customer/customer\_management.feature)
