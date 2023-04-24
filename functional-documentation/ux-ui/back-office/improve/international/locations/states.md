# States

## Description

The purpose of this page is to edit or add a new State, according to the country.

<figure><img src="../../../../../../.gitbook/assets/image (16).png" alt=""><figcaption><p>States User Interface</p></figcaption></figure>

## Components description

### Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [4 table header links](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/u5LiWcNXkcWYIFiEJqil/functional-documentation/ux-ui/common-components/4-table-header-tools)
* [Save button](../../../../common-components/forms/save-button.md)&#x20;
* [Cancel button ](../../../../common-components/forms/cancel-button.md)

### Tabs section

The active selected tab _States_ is highlighted using [Navigation Tab UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/navigation--navigation-tabs).

## The main block&#x20;

### **Header of the block**&#x20;

Named **States** with the numeric value of total counted states in the listing.&#x20;

The second component nearby is from common component [4 table header tools](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/u5LiWcNXkcWYIFiEJqil/functional-documentation/ux-ui/common-components/4-table-header-tools)&#x20;

### Sorting section

The table list can be easily sorted by clicking the arrows at the beginning of the table.&#x20;

**The arrow indicators** - arrow up and arrow down appears, when headers are hovered. A single click will toggle the arrangement from highest to lowest, and another click will sort from lowest to highest table row values. The sorting table headers are:

* **ID**
* **Name**
* **ISO code**
* **Zone**
* **Country**

See [sorting rules](../../../../common-components/grid-component/sorting-rules.md)

### Filtering the table information <a href="#filtering-the-table-information" id="filtering-the-table-information"></a>

There are several input fields and few dropdowns, for filtering the table information.&#x20;

After clicking **Search CTA** ([Buttons with icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), the table returns the filtered results.

If filtered results do not return any information that was searched, there will be an empty table with the placeholder with the black warning triangle sign in the center - _No records found._ Then, a cross icon X with the word Reset, will be shown in the right table position, to reset the filtering and return to full table list. The inputs of the filtering are:

* **Search ID** - Accepts only numbers.
* **Name** - Accepts the numbers and letters.&#x20;
* **ISO code** - Accepts the numbers and letters.
*   **Zone** - Dropdown with the selections (by default, no value selected, single dash symbol):

    * **Africa**
    * **Asia**
    * **Central America/Antilla**
    * **Europe**
    * **Europe (non-EU)**
    * **North America**
    * **Oceania**
    * **South America**


*   **Country** - Dropdown with the selections (by default, no value selected, single dash symbol):

    * **Argentina**
    * **Australia**
    * **Canada**
    * **India**
    * **Indonesia**
    * **Italy**
    * **Japan**
    * **Mexico**
    * **Netherlands**
    * **United** **States**


* **Enabled** - Dropdown with the selections (by default, no value selected, single dash symbol):
  * **Yes**
  * **No**

### Content of the table section

There are the following components from the left to the right:

* **Checkbox (**[**Forms checkboxes UI Kit**](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes)**)** - enabling or disabling the certain entry.
* **Numeric value** - ID number.
* **Name of the State** - two-letter initials or full State name.
* **Two-letter initials** - particular ISO code defined.
* **Continent name** - shows the certain continent name.
* **Country name** - shows the certain country name.
* **Green checkmark or red cross** - indicates that the State is enabled or disabled.
* **Edit (**[**Dropdown with Button split UI Kit**](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)**)**- clicking the CTA button redirects to the States editing page.
  * **Dropdown arrow** - shows an option of Deleting the entry. After clicking Delete, there will ba a small popup with exclamation mark and the text:\
    _Delete selected item?_\
    _Name: {the name of the State}._\
    _Yes - deletes the entry with the alert success message. (_[_Alerts Basics UI Kit_](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)_)_\
    _No - closes the popup with no action._

### Bulk actions behavior

Clicking the CTA button ([Buttons Outline UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) with a small arrow, extends a contextual menu, with the following selections:

* **Select all** - this checkbox can select all entries in the table on that page.
* **Unselect all** - this checkbox can unselect all entries in the table on that page.
* **Enable selection** - enables all the entries in the table on that page.
* **Disable selection** - disables all the entries in the table on that page.
* **Delete selected** - deletes the selected entries in the table on that page.
* **Assign to a new zone** - assigns the selection to a new zone.

### Pagination section

[Pagination from common components ](../../../../common-components/grid-component/pagination.md)

## Multistores functionality

This page is [Multistores dependent](../../../../common-components/multistore-component/multistores-dependent.md) page.



