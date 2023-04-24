# Contacts

## Description

This page shows the available webshop contacts list. Those contacts can be managed in various ways.



<figure><img src="../../../../../../.gitbook/assets/Capture d’écran du 2023-04-24 12-12-08.png" alt=""><figcaption><p>Manage your customer  </p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/contact/contacts.html)

## Components description <a href="#common-components" id="common-components"></a>

### Common components <a href="#common-components" id="common-components"></a>

* [Back Office Header](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/functional-documentation/ux-ui/common-components/back-office-header)
* Settings wheel (todo link)



### Bulk dropdown

This [Dropdown](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) UI Kit is enable when at least one contact have been selected\
This dropdown contains 3 entries :&#x20;

* Enabled
* Disabled
* Delete

See [Bulk action CTA](contacts.md#bulk-ctas)

### Add new Contact button

[Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics) component. Clicking the button redirects to the Contact adding page.

### Contacts section

The section starts with the title _Manage_ _Contacts_ and the sum of the whole contacts in the brackets.

### Contacts table

|                 | Sort rules            | Filter Rules                                  | Value          |
| --------------- | --------------------- | --------------------------------------------- | -------------- |
| ID              | Numeric\_sorting      | Numeric\_filtering                            | Textfield      |
| Social title    | Alphanumeric\_sorting | Social Title (list of social title available) | Dropdown list  |
| First name      | Alphanumeric\_sorting | Alphanumeric\_sorting                         | Textfield      |
| Last name       | Alphanumeric\_sorting | Alphanumeric\_sorting                         | Textfield      |
| Email address   | Alphanumeric\_sorting | Alphanumeric\_sorting                         | Textfield      |
| Group           | Alphanumeric\_sorting | Group ( list of groups available)             | Dropdown list  |
| Sales           | Numeric\_sorting      | Numeric\_filtering                            | Textfield      |
| Enabled         | Boolean\_sorting      | Boolean\_filtering                            | Dropdown list  |
| Newsletter      | Boolean\_sorting      | Boolean\_sorting                              | Dropdown list  |
| Partener offers | Boolean\_sorting      | Boolean\_sorting                              | Dropdown list  |
| Registration    | Timestamp\_sorting    | Between 2 Timestamp                           | 2 dates picker |
| Last visit      | Timestamp\_sorting    | N/A                                           | N/A            |



The rest of the content:

* **(De)Select all :** [Forms Checkboxes UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes) element. Select all or deselect all element of the table
* **Checkbox** - [Forms Checkboxes UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes) element. Marks or unmarks the desired selection of entry.
* **Pen icon** - once clicked, the Edit Contact page will be displayed.
* **Three-dot-button** - clicking the button, Delete button will appear :&#x20;
  * Clicking the Delete : [Delete CTA](contacts.md#delelte-cta)
  * View : the Contact page will be display&#x20;

##

## Components behaviors

### Delelte CTA&#x20;

It  will show a modal pop-up with a confirmation text:\
\
_**Delete selection**_

_Are you sure you want to delete the selected item(s)?_\
_Cancel Delete_\
\
**Cancel** and **X** button closes the popup modal, and **Delete** will execute the deletion action and the Contact entry will be deleted from the list.

### Bulk CTAs

Clicking on the _Bulk actions_ button allows users to perform bulk actions for selected features (using the checkboxes). A user can:

* **Enable selection** - this button will enable all the checkboxes that are selected.
* **Disable selection** - this button will disable all the checkboxes that are selected.
* **Delete selected** - This button will delete the selected employees. After clicking on "Delete selected", a modal with the title "Delete selection" is opened, asking to confirm or cancel the action: "Are you sure you want to delete the selected item(s)?" (See issue [#14462](https://github.com/PrestaShop/PrestaShop/issues/14462)). The action can be canceled by clicking on the cross or on the cancel button. After clicking on "Delete" button, the selected employee will be deleted, a successful message is displayed "The selection has been successfully deleted."

If nothing is selected, and the execution is made, there will be an [Alert Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) message:

_You must select at least one element to delete._

## Multistores functionality

This page is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.
