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



### Add new Contact button

[Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics) component. Clicking the button redirects to the Contact adding page.

### Contacts section

The section starts with the title _Manage_ _Contacts_ and the sum of the whole contacts in the brackets.

### Contacts table

|                 | Sort rules            | Filter Rules                                  | Value         |
| --------------- | --------------------- | --------------------------------------------- | ------------- |
| ID              | Numeric\_sorting      | Numeric\_filtering                            | Textfield     |
| Social title    | Alphanumeric\_sorting | Social Title (list of social title available) | Dropdown list |
| First name      | Alphanumeric\_sorting | Alphanumeric\_sorting                         | Textfield     |
| Last name       | Alphanumeric\_sorting | Alphanumeric\_sorting                         | Textfield     |
| Email address   | Alphanumeric\_sorting | Alphanumeric\_sorting                         | Textfield     |
| Group           | Alphanumeric\_sorting | Group ( list of groups available)             | Dropdown list |
| Sales           | Numeric\_sorting      | Numeric\_filtering                            | Textfield     |
| Enabled         |                       |                                               |               |
| Newsletter      |                       |                                               |               |
| Partener offers |                       |                                               |               |
| Registration    |                       |                                               |               |
|                 |                       |                                               |               |



#### &#x20;ID&#x20;

**Sorting** the table uses the [Sorting rules](../../../../common-components/sorting-rules.md) functionality.

**Filter rules** &#x20;



<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center"></td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numerical</td><td align="center">This value is not valid.</td><td></td></tr><tr><td>Default value</td><td>           -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>           -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>           -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>          0</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>     </td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="contacts.md#behaviors-description">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Sorting the table

Sorting the table uses the [Sorting rules](../../../../common-components/sorting-rules.md) functionality. The sorting headers of the table are:

* **ID**
* **Title**
* **Email address**
* **Description**

### Table filtering

Table uses standard input fields for filtering. The filtering can be made in these inputs:

* **ID**
* **Title**
* **Email address**
* **Description**

After the filtering has been inputted, CTA button ([Buttons with Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) **Search** can be executed for the search results.

### Unsorted and unfiltered column

**Actions** column can not be filtered or sorted.

### Table content

By the default installation of the webshop, there are 2 entries already saved to the contacts list:

| ID | Title            | Email address       | Description                                   |
| -- | ---------------- | ------------------- | --------------------------------------------- |
| 1  | Webmaster        | demo@prestashop.com | If a technical problem occurs on this website |
| 2  | Customer service | demo@prestashop.com | For any question about a product, an order    |

The rest of the content:

* **Checkbox** - [Forms Checkboxes UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes) element. Marks or unmarks the desired selection of entry.
* **ID** - displays the ID name.
* **Title** - displays the name of the Contact.
* **Email address** - displays the email of the Contact.
* **Description** - displays the description of the Contact.
* **Pen icon** - once clicked, the Edit Contact page will be displayed.
*   **Three-dot-button** - clicking the button, Delete button will appear. Clicking the Delete, will show a modal pop-up with a confirmation text:\
    \
    _**Delete selection**_

    _Are you sure you want to delete the selected item(s)?_\
    _Cancel Delete_\
    \
    **Cancel** and **X** button closes the popup modal, and **Delete** will execute the deletion action and the Contact entry will be deleted from the list.

### Bulk actions

Clicking on the _Bulk actions_ button allows users to perform bulk actions for selected features (using the checkboxes). A user can:

* **Enable selection** - this button will enable all the checkboxes that are selected.
* **Disable selection** - this button will disable all the checkboxes that are selected.
* **Delete selected** - This button will delete the selected employees. After clicking on "Delete selected", a modal with the title "Delete selection" is opened, asking to confirm or cancel the action: "Are you sure you want to delete the selected item(s)?" (See issue [#14462](https://github.com/PrestaShop/PrestaShop/issues/14462)). The action can be canceled by clicking on the cross or on the cancel button. After clicking on "Delete" button, the selected employee will be deleted, a successful message is displayed "The selection has been successfully deleted."

If nothing is selected, and the execution is made, there will be an [Alert Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) message:

_You must select at least one element to delete._

## Multistores functionality

This page is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.
