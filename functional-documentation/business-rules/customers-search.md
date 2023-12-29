# Customer's search

## Business rule description

The search feature allows users to search for customers with the following criterias :

* Searching for customer(s) is possible by using words that might be found in one of the following fields :&#x20;
  * **Social title**
  * **First name**
  * **Last name**
  * **Email address**
  * **Group**
  * **Company** (Note that this field is only available to edit on customer's profile if B2B features are activated on the shop)

## QA

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers/customers/bo-customers-filter-and-quick-edit.html)

### UX/UI impact of this BR

The search bar being present in the back-office header means that it is accessible on most pages.

### Behat test link

[Github link](https://github.com/PrestaShop/PrestaShop/blob/develop/tests/Integration/Behaviour/Features/Scenario/Customer/search\_customers.feature)
