# Team - Employees

## Description

In this page the employees of the shop can be set and edited.&#x20;

<figure><img src="../../../../.gitbook/assets/Screenshot 2022-09-21 at 17-12-47 Employees • test.png" alt=""><figcaption></figcaption></figure>

## Components description

### Employees sorting

7 rows are presented in this section:

1. ID&#x20;
2. First name
3. Last name
4. Email address
5. Profile
6. Active

All the employees can be sorted using the common component rule which can be found [HERE](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/LBfyCScRUjOVa2zoG5Ub/functional-documentation/ux-ui/common-components/sorting-rule).



### Employees searching

7 rows are presented in this section:

1. ID: when searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
2. First name  when searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
3. Last name: when searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
4. Email address: when searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
5. Profile: searching allows only the following selection from the drop-down (if more roles are added in the shop, they will appear in the drop-down):&#x20;

* SuperAdmin
* Logistician
* Translator
* Salesman

6\. Active : when searching, from the drop-down field the following available options are:

* Yes
* No

### Employee options

In this section 2 fields are present:

1. Password regeneration

By default it is set to: 360. On the right from the field it is shown that the number is measured in: "Minutes". A help text below is shown: "Security: Minimum time to wait between two password changes." Only allowed values are numbers. Entering anything that is not numbers, will show a message: "Please enter a number".

2\. Memorize the language used in Admin panel forms

This is a toggle switch, by default is set to: "No". A help text below is shown: "Allow employees to select a specific language for the Admin panel form.".

## Behaviors description

### Add new Employee button

This button is used to add new employee : [`Call to action`](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/AC6MLBkSBL33Yd0iYykc/functional-documentation/ux-ui/back-office/configure/advanced-parameters/team-employees#add-new-employeee-cta)``

### Settings wheel

This is a [standard component](../../common-components/settings-wheel.md) for the list management

#### Bulk actions

Clicking on the _Bulk actions_ button allows users to perform bulk actions for selected features (using the checkboxes). A user can:

* Enable selection: this button will enable all the checkboxes that are selected.
* Disable selection: this button will disable all the checkboxes that are selected.
* Delete selected: This button will delete the selected employees. After clicking on "Delete selected", a modal with the title "Delete selection" is opened asking to confirm or cancel the action: "Are you sure you want to delete the selected item(s)?" (See issue [#14462](https://github.com/PrestaShop/PrestaShop/issues/14462)). The action can be canceled by clicking on the cross or on the cancel button. After clicking on "Delete" button, the selected employee will be deleted, a successful message is displayed "The selection has been successfully deleted."

### CTA buttons

* Save, when pressed, a message is shown: "Successful update.".
*   Actions (2 CTA buttons)

    **Edit.** The user can edit edit the employee as often as necessary.

    **Delete.** An employee can be deleted by clicking this button. After clicking on Delete, a modal with the title "Delete selection" is opened asking to confirm or cancel the action: "Are you sure you want to delete the selected item(s)?" The action can be canceled by clicking on the cross or on the cancel button. After clicking on "Delete" button, the employee is deleted, a successful message is displayed "Successful deletion."

## Behaviors description

Here figma link ( TODO [Tristan Lehot](https://app.gitbook.com/u/wxuQ8dEUfYTsCcCBbcFmmedKE5t2 "mention") )



### Add New employee button Call to action <a href="#add-new-employeee-cta" id="add-new-employeee-cta"></a>

Call [add employee page](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/AC6MLBkSBL33Yd0iYykc/functional-documentation/ux-ui/back-office/configure/advanced-parameters/team-employees/add-edit-employee)





