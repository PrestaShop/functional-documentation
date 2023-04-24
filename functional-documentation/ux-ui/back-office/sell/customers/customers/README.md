# Customers list



## Description

This page displays the lists of customers who registered or ordered on the shop.

[Customers related tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers.html)

<figure><img src="../../../../../../.gitbook/assets/Capture d’écran 2022-10-07 à 11.26.14.png" alt=""><figcaption></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers.html)

## Components description

This section MUST describe each component one by one

### Common components

* [heading-of-the-page.md](../../../../common-components/heading-of-the-page.md "mention")
* [help-button.md](../../../../common-components/help-button.md "mention")
* [sorting-rules.md](../../../../common-components/sorting-rules.md "mention")

### Components

* An [UI/KIT table](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--with-filters) listing customers
* 2 [UI/KIT buttons with icons](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)
  * 1 to add a new customer (located in the header)
  * 1 to set required fields (located under the UI/KIT table)

## Behaviors description

### Workflow

The **Customers** page is used to manage customers, as it mainly functions as a root for customer management workflows, the Customers page in itself has two true workflows and gives access to four sub-workflows.

True workflows :&#x20;

* Required fields settings
  1. Click on the "Set required fields for this section" button --> this opens a frame under the button and the customers list
  2. Tick one or all checkboxes to select the required fields
  3. Click on the save button at the bottom right of the frame to save the selected required fields
* Customer list filtering
  1. Use the header of the table containing the customers list to apply filter
  2. The table content displayed depends on the filters applied (i.e. : filtering on registered customers between 01/01/2021 and 01/01/2022 will display all customers having registered between those dates)

Sub workflows :&#x20;

* Customer creation --> clicking on the "Add new customer" button triggers a customer creation workflow
* Customer deletion --> clicking on the three dot button in the customer's list then on "Delete" triggers the customer deletion workflow
* Customer edition --> clicking on the pen button in the customer's list trigger the customer edition workflow
* Accessing customer's details --> clicking on the three dot button in the customer's list then on "View" let's you access to the customer's detail

TODO : workflow diagrams

### Behavior description

* The customers list displays both registered customers and guest customers (unregistered customers)
* Quick edit some customer's settings :&#x20;
  * 3 toggles are present on each customer's entry in the customers list
  * each toggle can be interacted with to activate or deactivate their related function
  * each toggle is related to one of the following :
    * Customer's login activation (Business rule)
    * Customer's newsletter registration (Business rule)
    * Customer's partner offers registration (Business rule)
* A new customer appears in the list when :&#x20;
  * You create a new customer from the BO using the "Add new customer" button
  * A customer registers in the Front Office of your shop
  * A customer buys at least an item from the Front Office of your shop and registers
  * A customer buys at least an item from the Front Office of your shop without registering

## Error messages

This section MUST list all errors messages / Exceptions for the page / workflow

## Limitations

This section SHOULD list limitations of the page.
