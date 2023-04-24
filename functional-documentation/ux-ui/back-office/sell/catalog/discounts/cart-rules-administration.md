---
description: >-
  The following specifications are about the Cart Rules administration page. To
  see the page in the software, go to Catalog > Discounts.
---

# Cart Rules' Administration

### Description

Cart Rules are discount rules findable in multiple places across the back office and the front office of any PrestaShop website. As merchants, we can administrate and apply those on orders from the back office.

From the front office, customers can use cart rules by applying them to their cart if they are not already automatically applied according to their parameters.

Merchants need to be able to create and edit discounts for their customers based on specific conditions, such as product quantity or category, combinations, brands, and more (specific conditions are detailed further on this page).

They also need to enable and disable those rules when needed, as they have to be able to delete them. The administration page allows merchants to do every one of those actions.

<figure><img src="../../../../../../.gitbook/assets/Capture d’écran 2022-11-02 à 15.52.54.png" alt=""><figcaption></figcaption></figure>

### [Behat test](https://github.com/PrestaShop/PrestaShop/blob/db00157234bebfdd5f21c4f6cd18b211c63674df/tests/Integration/Behaviour/Features/Scenario/CartRule/cart\_rule.feature)

### Components description

[Back office header](../../../../common-components/back-office-header/) (Digits 1, 2 and 4 are in the header)

<figure><img src="../../../../../../.gitbook/assets/Frame 1.png" alt=""><figcaption></figcaption></figure>

#### 3 – “[Add a cart rule” Button](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/buttons--buttons-with-icons)

| Description              | Value                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------ |
| Mandatory                | -                                                                                    |
| Allowed/Forbidden values | -                                                                                    |
| Default value            | -                                                                                    |
| Help text                | -                                                                                    |
| Tool tips                | -                                                                                    |
| Behavior                 | Clicking on this button opens the cart rule's creation form, on the information tab. |

#### 5 – “[Cart Rules” Tab](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/navigation--navigation-pills)

| Description              | Value                                                                                                                                                                                                                     |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mandatory                | -                                                                                                                                                                                                                         |
| Allowed/Forbidden values | -                                                                                                                                                                                                                         |
| Default value            | -                                                                                                                                                                                                                         |
| Help text                | -                                                                                                                                                                                                                         |
| Tool tips                | -                                                                                                                                                                                                                         |
| Behavior                 | <p>It's the tab selected by default when clicking on “Discounts” in the menu.<br>On click, it opens the Cart Rules' Administration page, or reload it because even if already on this page, the tab stays clickable. </p> |

#### 6 – “[Catalog Prices Rules” Tab](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/navigation--navigation-pills)

| Description              | Value |
| ------------------------ | ----- |
| Mandatory                | —     |
| Allowed/Forbidden values | -     |
| Default value            | -     |
| Help text                | -     |
| Tool tips                | -     |
| Behavior                 |       |

#### 7 – Table

* **a - Header**
* **b - Add Icon**

| Description              | Value                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------ |
| Mandatory                | -                                                                                    |
| Allowed/Forbidden values | -                                                                                    |
| Default value            | -                                                                                    |
| Help text                | -                                                                                    |
| Tool tips                | Add New                                                                              |
| Behavior                 | Clicking on this button opens the cart rule's creation form, on the information tab. |

* **c - Refresh Icon**

| Description              | Value                                             |
| ------------------------ | ------------------------------------------------- |
| Mandatory                | -                                                 |
| Allowed/Forbidden values | -                                                 |
| Default value            | -                                                 |
| Help text                | -                                                 |
| Tool tips                | Refresh list                                      |
| Behavior                 | Clicking on this button reloads the entire page.  |

* **d—SQL request Icon**

| Description              | Value                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------ |
| Mandatory                | -                                                                                    |
| Allowed/Forbidden values | -                                                                                    |
| Default value            | -                                                                                    |
| Help text                | -                                                                                    |
| Tool tips                | Show SQL query                                                                       |
| Behavior                 | Clicking on this button triggers a JavaScript function, but nothing happens visually |

* **e - SQL export Icon**

| Description              | Value                                                                                                                                                                     |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mandatory                | -                                                                                                                                                                         |
| Allowed/Forbidden values | -                                                                                                                                                                         |
| Default value            | -                                                                                                                                                                         |
| Help text                | -                                                                                                                                                                         |
| Tool tips                | Export to SQL Manager                                                                                                                                                     |
| Behavior                 | Clicking on this button sends to the SQL Manager's page (Advanced Parameters > Database > SQL Manager), displaying the SQL query corresponding to the list of Cart Rules. |

* **f - Search by ID field**

| Description              | Value                                                          |
| ------------------------ | -------------------------------------------------------------- |
| Mandatory                | No                                                             |
| Allowed/Forbidden values | Allowed : Letters, numbers, special characters / Forbidden : - |
| Default value            | -                                                              |
| Help text                | -                                                              |
| Tool tips                | -                                                              |
| Behavior                 | -                                                              |

* **g - Search by name**

| Description              | Value                                                |
| ------------------------ | ---------------------------------------------------- |
| Mandatory                | No                                                   |
| Allowed/Forbidden values | Letters, numbers, special characters / Forbidden : - |
| Default value            | -                                                    |
| Help text                | -                                                    |
| Tool tips                | -                                                    |
| Behavior                 | -                                                    |

* **h - Search by priority**

| Description              | Value                                                |
| ------------------------ | ---------------------------------------------------- |
| Mandatory                | No                                                   |
| Allowed/Forbidden values | Letters, numbers, special characters / Forbidden : - |
| Default value            | -                                                    |
| Help text                | -                                                    |
| Tool tips                | -                                                    |
| Behavior                 | -                                                    |

* **i - Search by code**

| Description              | Value                                                |
| ------------------------ | ---------------------------------------------------- |
| Mandatory                | No                                                   |
| Allowed/Forbidden values | Letters, numbers, special characters / Forbidden : - |
| Default value            | -                                                    |
| Help text                | -                                                    |
| Tool tips                | -                                                    |
| Behavior                 | -                                                    |

* **j - Search by quantity**

| Description              | Value                                                |
| ------------------------ | ---------------------------------------------------- |
| Mandatory                | No                                                   |
| Allowed/Forbidden values | Letters, numbers, special characters / Forbidden : - |
| Default value            | -                                                    |
| Help text                | -                                                    |
| Tool tips                | -                                                    |
| Behavior                 | -                                                    |

* **k - Search by expiration dates**

| Description              | Value                                                                                                                              |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| Mandatory                | No                                                                                                                                 |
| Allowed/Forbidden values | Allowed : Date                                                                                                                     |
| Default value            | -                                                                                                                                  |
| Help text                | -                                                                                                                                  |
| Tool tips                | -                                                                                                                                  |
| Behavior                 | Clicking on this field opens a date picker. The “From” date can be set on a later date than the “To” date, there is no limitation. |

* **l - Search by status**

| Description              | Value                                                       |
| ------------------------ | ----------------------------------------------------------- |
| Mandatory                | No                                                          |
| Allowed/Forbidden values | Boolean or empty                                            |
| Default value            | Empty                                                       |
| Help text                | -                                                           |
| Tool tips                | -                                                           |
| Behavior                 | Clicking on this field opens the list of available options. |

* **m -** [**Search Button**](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/buttons--outline)

| Description              | Value                                                                                                                                                                                                                                                       |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mandatory                | -                                                                                                                                                                                                                                                           |
| Allowed/Forbidden values | -                                                                                                                                                                                                                                                           |
| Default value            | -                                                                                                                                                                                                                                                           |
| Help text                | -                                                                                                                                                                                                                                                           |
| Tool tips                | -                                                                                                                                                                                                                                                           |
| Behavior                 | Clicking on this button triggers a filtering request based on the search field's value. If nothing has been entered in those fields, the table is just refreshed. If some cart rules match, the button search stays clickable and the Reset Button appears. |

* [**Reset Button**](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/buttons--basics)

| Description              | Value                                                                |
| ------------------------ | -------------------------------------------------------------------- |
| Mandatory                | -                                                                    |
| Allowed/Forbidden values | -                                                                    |
| Default value            | -                                                                    |
| Help text                | -                                                                    |
| Tool tips                | -                                                                    |
| Behavior                 | Clicking on this button refresh the table to display all cart rules. |

* **n - Table item**

| Description              | Value                                                               |
| ------------------------ | ------------------------------------------------------------------- |
| Mandatory                | -                                                                   |
| Allowed/Forbidden values | -                                                                   |
| Default value            | -                                                                   |
| Help text                | -                                                                   |
| Tool tips                | -                                                                   |
| Behavior                 | Clicking on a table item open the related cart rule's edition page. |

* **o -** [**Checkbox**](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/forms--checkboxes)

| Description   | Value                                                                                             |
| ------------- | ------------------------------------------------------------------------------------------------- |
| Mandatory     | NO                                                                                                |
| Default value | Unchecked                                                                                         |
| Help text     | -                                                                                                 |
| Tool tips     | -                                                                                                 |
| Behavior      | Clicking on a checkbox changes the selection status. When selected, bulk actions affect the item. |

* **p - Status Icon**

| Description   | Value                                                                          |
| ------------- | ------------------------------------------------------------------------------ |
| Mandatory     | YES                                                                            |
| Default value | Enabled                                                                        |
| Help text     | -                                                                              |
| Tool tips     | Status : Enabled / Disabled                                                    |
| Behavior      | Clicking on the status icon changes the item status, between enabled (default) |

*   **q -** [**Edit Dropdown**](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/dropdowns--with-button-split)



    | Description              | Value                                                                                                                                                                                                                                                                                                                                                                                                                               |
    | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | Mandatory                | -                                                                                                                                                                                                                                                                                                                                                                                                                                   |
    | Allowed/Forbidden values | -                                                                                                                                                                                                                                                                                                                                                                                                                                   |
    | Default value            | -                                                                                                                                                                                                                                                                                                                                                                                                                                   |
    | Help text                | -                                                                                                                                                                                                                                                                                                                                                                                                                                   |
    | Tool tips                | -                                                                                                                                                                                                                                                                                                                                                                                                                                   |
    | Behavior                 | <p>Edit Dropdown has 2 options:</p><p><strong>Edit –</strong> When clicking on that option, the related Cart Rule’s edition form opens. <br><strong>Delete –</strong> When clicking on that option, a popup opens with the text: <br><em>Delete selected item?</em> <br><em>Name: Name of the cart rule</em> <br><em><strong>Yes –</strong> finishes the action, <strong>No –</strong> closes the pop-up without deletion.</em></p> |
*   **r -** [**Bulk Actions Dropdown**](https://build.prestashop-project.org/prestashop-ui-kit/?path=/docs/dropdowns--with-button-split)\


    | Description              | Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
    | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | Mandatory                | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
    | Allowed/Forbidden values | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
    | Default value            | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
    | Help text                | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
    | Tool tips                | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
    | Behavior                 | <p>Bulk action has 5 options:<br><strong>Select all</strong> - select every item from the table. When clicking on that option, the bulk action menu is closed and all checkboxes are selected.<br><strong>Unselect all</strong> - unselect every item from the table. When clicking on that option, the bulk action menu is closed and all checkboxes are unselected.<br><strong>Enable selection</strong> - enables the selected Cart Rules. After the action finishes, success notification is shown in the interface - <em>The status has been successfully updated</em>. It comes from the <a href="https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics">Alerts Basics UI Kit</a>.<br><strong>Disable selection</strong> - disables the selected Cart Rules. After the action finishes, success notification is shown in the interface - <em>The status has been successfully updated</em>. It comes from the <a href="https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics">Alerts Basics UI Kit</a>.<br><strong>Delete selected</strong> - deletes the selected Cart Rules. After the action initiates, there will be a navigator pop-up with the text: <br><em>Delete selected item?</em><br><em><strong>Cancel</strong> - closes the pop-up, <strong>OK</strong> - finishes the action.</em></p> |

###

### Error messages

**“You must select at least one item to perform a bulk action.”** - When clicking on “Enable selection” / “Disable selection” or “Deleted selected” in the Bulk actions' menu, if nothing has been selected, this error message is displayed. The error message UI comes from the [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics).
