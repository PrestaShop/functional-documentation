# Search

The search widget is positioned in the top interface position and is visible in every Prestashop page in Back-Office.

![Widget input interface](<../../../.gitbook/assets/image (7) (2) (1).png>)

Prestashop search engine helps to find desired information by typing just words, then pressing Enter on the keyboard. The interface will return the search results.

![Search output results interface](<../../../.gitbook/assets/image (2) (7).png>)

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/bo-search-bar.html)

## Common components

* [Heading of the page](../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## Search widget components

The widget wraps 250 x 25 pixels of space in the user interface. The element contains:

* **Bordered oval** - showing the space where to type the text for searching.
* **Magnifier icon** - indicates the searching action here. Once clicked, there will be a dropdown context block, allowing to be more specific on search field:
  * **Everywhere** - choosing this selection, the search field will be all the places in webshop.
  * **Catalog** - search field is only Catalog of webshop.
  * **Customers by name** - search field is only Customers by their names.
  * **Customers by IP address** - search field is only Customers with IP addresses listed.
  * **Orders** - search field is only Orders of webshop.
  * **Invoices** - search field is only Invoices of the webshop.
  * **Carts** - search field is only Carts of the webshop.
  * **Modules** - search field is only Modules that were installed in the webshop
* **Search placeholder** - once there is nothing typed in the search field, there will be only Placeholder named _Search_.

After pressing Enter, to submit the query for searching, after page reload, the input field will have an additional "X" icon, for deleting the input information by one click. After "X" icon is clicked, the input will revert to the default input field with a Placeholder.

## Search results layout

The search results depend on which search field the search engine has hit. If there will be a query, that matches a few multiple search fields, the results will be displayed in separate search field segments.&#x20;

For example, if the search query word is _test_, the output will return some results from module block, customers block, _doc.prestashop.com_, _addons.prestashop.com_ and _prestashop.com forum._

## Search results marking

For the best user experience in finding the desired results, the resulted queries - words, phrases will be highlighted in yellow.

## Default blocks for all search results

There is an additional source for search results in every search field. The search query or queries are sent to the 3 outsource websites.

**Search doc.prestashop.com** - initiates searching in Prestashop documentation by clicking Call-to-action button **Go to the documentation** (opens in a new blank page).

**Search addons.prestashop.com** - initiates searching in Prestashop Addons Marketplace by clicking Call-to-action button **Go to Addons** (opens in a new blank page).

**Search prestashop.com forum** - initiates searching in Prestashop community forums by clicking Call-to-action button **Go to Addons** (opens in a new blank page).

## Catalog block results

The search results include:

* **H2 style phrase, about the results showing** - _{number of matched results} results match your query "{query name}"_.
* **Headline of the search block** - shows the number of matched results and the search field name - category or categories.
* **Path to the category** - lists all the names and all the full paths of the categories. A pen icon indicates, that categories can be edited.

## Customers block results

The search results include:

* **H2 style phrase, about the results showing** - _{number of matched results} results match your query "{query name}"_.
* **Headline of the search block** - shows the number of matched results and the search field name - customer or customers.
* **ID** - shows the Customer identification number in webshop.
* **Social title** - shows the Female or Male gender icon.
* **First name** - shows the first name of the Customer.
* **Name** - shows the last name of the Customer.
* **Email address** - shows the email address referred to the Customer.
* **Company** - shows the Company name.
* **Birth date** - shows the birthdate of the Customer.
* **Registration date** - shows the date when the Customer has registered - in MM/DD/YYY format.
* **Orders** - shows the total number of Orders that Customer has done.
* **Enabled** - shows the Customers, that are confirmed and visible in the webshop. If there will be a red cross icon, it will indicate, that the Customer is disabled for public.
* **Edit and View component** - it is a complex component from [Dropdown Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics). After clicking **Edit**, redirection will be executed to the Customer Edit page. After clicking the dropdown, there will be a **View** option. It will redirect to the Customer profile information page.

## Customers by IP address block results

The search results include:

* **H2 style phrase, about the results showing** - _{number of matched results} results match your query "{query name}"_.
* **Headline of the search block** - shows the number of matched results and the search field name - customer or customers.
* **ID** - shows the Customer identification number in webshop.
* **Social title** - shows the Female or Male gender icon.
* **First name** - shows the first name of the Customer.
* **Name** - shows the last name of the Customer.
* **Email address** - shows the email address referred to the Customer.
* **Company** - shows the Company name.
* **Birth date** - shows the birthdate of the Customer.
* **Registration date** - shows the date when the Customer has registered - in MM/DD/YYY format.
* **Orders** - shows the total number of Orders that Customer has done.
* **Enabled** - shows the Customers, that are confirmed and visible in the webshop. If there will be a red cross icon, it will indicate, that the Customer is disabled for public.
* **Edit and View component** - it is a complex component from [Dropdown Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics). After clicking **Edit**, redirection will be executed to the Customer Edit page. After clicking the dropdown, there will be a **View** option. It will redirect to the Customer profile information page.

## Orders block results

The search results include:

* **H2 style phrase, about the results showing** - _{number of matched results} results match your query "{query name}"_.
* **Headline of the search block** - shows the number of matched results and the search field name - order or orders.
* **Reference** - shows the Order reference code.
* **ID** - shows the Order ID.
* **Customer** - shows the Customer name.
* **Total** - shows the total amount that was spent to make the Order.
* **Payment** - shows the method of the Payment.
* **Status** - shows the status of the Order.
* **Date** - shows when the Order was made.
* **View button (**[**Buttons with Icons UI Kit**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)**)** - the button will redirect to the exact Order details page.

## Invoices block results

User must type exact Invoice identification reference in the search input, then the interface will execute a blank new page with the exact PDF Invoice file straight in the browser.

## Cart block results

Using Carts as the main search field, initiates search results only from Carts, that are listed in the Shopping Carts menu section. Simply typing a Cart ID and submitting the search will return the View Shopping Cart page, with all the Cart details.

## Modules block results

The search results include:

* **H2 style phrase, about the results showing** - _{number of matched results} results match your query "{query name}"_.
* **Headline of the search block** - shows the number of matched results and the search field name - module or modules.
* **Module name** - redirects to Module Catalog section in Back-Office.
* **Description** - the text that is defined from the module description paragraph.

## Error messages

There are the following [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) error messages for the available search fields:

* _This is not a valid IP address: {query name}_
* _No order was found with this ID: {query name}_
* _No invoice was found with this ID: {query name}_
* _No cart was found with this ID: {query name}_
