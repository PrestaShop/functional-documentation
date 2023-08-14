# Team - Employees

## Description

In this page the employees of the shop can be set and edited.&#x20;

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2022-09-21 at 17-12-47 Employees • test.png" alt=""><figcaption></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/advanced-parameters/team/employees.html)

## Components description

### Common Components

* [Backoffice header](../../../../common-components/back-office-header/)

### Employees table



|               | Sort rules            | Filter Rules                            | Value         |
| ------------- | --------------------- | --------------------------------------- | ------------- |
| ID            | Numeric\_sorting      | Numeric\_filtering                      | Textfield     |
| First name    | Alphanumeric\_sorting | Alphanumeric\_sorting                   | Textfield     |
| Last name     | Alphanumeric\_sorting | Alphanumeric\_sorting                   | Textfield     |
| Email address | Alphanumeric\_sorting | Alphanumeric\_sorting                   | Textfield     |
| Profile       | Alphanumeric\_sorting | Profiles ( list of profiles available)  | Dropdown list |
| Active        | Boolean\_sorting      | Boolean\_filtering                      | Dropdown list |

#### Edit  ( pencil )

See [Edit CTA](./#edit-cta)

#### Dots&#x20;

Contains 1 entry " delete". See [Delete CTA](./#delete-cta)&#x20;

### Employee options

In this section 2 fields are present:

#### Password regeneration



<table><thead><tr><th width="200">Description</th><th width="203">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">No ( looks like a bug).<br>If you erase the value and save it save as the last value</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>numerical</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>360</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Security: Minimum time to wait between two password changes.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>              -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>             0</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>               ?</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>



#### Memorize the language used in Admin panel forms

This is a toggle switch, by default is set to: "No". A help text below is shown: "Allow employees to select a specific language for the Admin panel form.".

## Behaviors description

### Add new Employee button

This button is used to add new employee : [`Call to action`](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/AC6MLBkSBL33Yd0iYykc/functional-documentation/ux-ui/back-office/configure/advanced-parameters/team-employees#add-new-employeee-cta)

### Settings wheel

This is a [standard component](../../../../common-components/settings-wheel.md) for the list management

#### Bulk actions

Clicking on the _Bulk actions_ button allows users to perform bulk actions for selected features (using the checkboxes). A user can:

* Enable selection: this button will enable all the checkboxes that are selected.
* Disable selection: this button will disable all the checkboxes that are selected.
* Delete selected: This button will delete the selected employees. After clicking on "Delete selected", a modal with the title "Delete selection" is opened asking to confirm or cancel the action: "Are you sure you want to delete the selected item(s)?" (See issue [#14462](https://github.com/PrestaShop/PrestaShop/issues/14462)). The action can be canceled by clicking on the cross or on the cancel button. After clicking on "Delete" button, the selected employee will be deleted, a successful message is displayed "The selection has been successfully deleted."

### CTA buttons

#### Save

when pressed, a message is shown: "Successful update.".



#### **Edit CTA**

&#x20;The user can edit edit the employee as often as necessary.

#### **Delete CTA**

&#x20;An employee can be deleted by clicking this button. After clicking on Delete, a modal with the title "Delete selection" is opened asking to confirm or cancel the action: "Are you sure you want to delete the selected item(s)?" The action can be canceled by clicking on the cross or on the cancel button. After clicking on "Delete" button, the employee is deleted, a successful message is displayed "Successful deletion."

## Behaviors description

Here figma link ( TODO [Tristan Lehot](http://127.0.0.1:5000/u/wxuQ8dEUfYTsCcCBbcFmmedKE5t2 "mention") )



### Add New employee button Call to action <a href="#add-new-employeee-cta" id="add-new-employeee-cta"></a>

Call [add employee page](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/AC6MLBkSBL33Yd0iYykc/functional-documentation/ux-ui/back-office/configure/advanced-parameters/team-employees/add-edit-employee)





