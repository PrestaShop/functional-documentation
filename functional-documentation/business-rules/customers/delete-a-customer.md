# Delete a customer

## Description

A customer can be deleted from the BO.

Deleting a customer allows the user to remove a customer from the shop with 2 options :

* Complete deletion -> A complete deletion allows the customer to register on the shop again
* Soft deletion -> A soft deletion removes the customer from the list but they won't be able to register with the same email address again as it is kept in the database

## Impacted pages

* [customers](../../ux-ui/back-office/sell/customers/customers/ "mention")

## Behat test

[Github link](https://github.com/PrestaShop/PrestaShop/blob/develop/tests/Integration/Behaviour/Features/Scenario/Customer/customer\_management.feature)
