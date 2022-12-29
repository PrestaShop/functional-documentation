# Customer's search

## Business rule description

The search feature allows users to search for customers with the following criterias :

* Searching for customer(s) is possible by using words that might be found in one of the following fields :&#x20;
  * **First name**
  * **Name**
  * **Email address**
  * **Company** (Note that this field is only available to edit on customer's profile if B2B features are activated on the shop)
* It is not possible to search for customers using their birthdate
* It is not possible to search for customers using their social title

### UX/UI impact of this BR

The search bar being present in the back-office header means that it is accessible on most pages.

### Behat test link

[Github link](https://github.com/PrestaShop/PrestaShop/blob/develop/tests/Integration/Behaviour/Features/Scenario/Customer/search\_customers.feature)
