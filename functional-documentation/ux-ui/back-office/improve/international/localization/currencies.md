# Currencies

The page contains webshop Currencies list.&#x20;

![Currencies interface](<../../../../../../.gitbook/assets/image (2).png>)

## Common components

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## Adding new currency

There is a separate Call-to-action button in the top-right position of the page, to add new currency.

## Tabs section

The active selected tab is highlighted using [Navigation Tab UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/navigation--navigation-tabs).

## Currency table components

Table header is **Currencies**. The header defines the numeric value of the entries in the currency table. The **Settings wheel** in the header **** has available dropdown functions as well. The table is generated from [Tables Hoverable UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable).

**Bulk actions dropdown** - by default, it is displayed as inactive, but once there is a random entry selected, the dropdown becomes active. Bulk action has 3 options:

* **Enable selection** - enables the selected Currency. After the action finishes, success notification is shown in the interface - _The status has been successfully updated_. It comes from the [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics).
* **Disable selection** - disables the selected Currency. After the action finishes, success notification is shown in the interface - _The status has been successfully updated_. It comes from the [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics).
* **Delete selection** - deletes the selected Currency. After the action initiates, there will be a pop-up with the text:\
  _Delete selection_\
  _Are you sure you want to delete the selected item(s)?_\
  __**Close** - closes the pop-up, **Delete** - finishes the action.

After the action finishes, success notification is shown in the interface - _The status has been successfully updated_. It comes from the [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics).&#x20;

**ID** - header indicating the ID of the Currency.

**Currency** - header indicating the Currency name.

**Symbol** - shows the symbolic expression of the Currency.

**ISO code** - shows the initials of the Currencies.

**Exchange rate** - shows the last official exchange rate of the Currency.

**Enabled** - displays the enabled or disabled toggle switch buttons - if Currency enabled or disabled.

**Actions** - displays the **Edit** or **Delete** actions for certain Currency.

### Filtering the table information

There are several input fields and a dropdown, for filtering the table information. If filtering results do not return any information that was searched, there will be an empty table with the placeholder  with the black warning triangle sign in the center - _No records found._ Then, a cross icon X with the word Reset, will be shown in the right table position, to reset the filtering and return to full table list.

**Search ID** - input with a placeholder. Accepts only numbers.

**Currency** - input with a placeholder. Accepts the numbers and letters.&#x20;

**Symbol** - input with a placeholder. Accepts the numbers and letters.

**ISO code** - input with a placeholder. Accepts the numbers and letters.

**Empty, Yes, No dropdown** - by default, the dropdown is set to empty. But it can arrange the currencies by Enabled or Disabled in webshop.

**Search call-to-action** - by default, the button is disabled, but once there is something typed in the filter inputs, the button becomes active.

### Sorting the table information

The table list can be easily sorted by clicking on the headers of the table. The arrow indicators - arrow up and arrow down appears, when headers are hovered. A single click will toggle the arrangement from highest to lowest, and another click will sort from lowest to highest table row values. The sorting table headers are:

* **ID**
* **ISO code**
* **Exchange rate**
* **Enabled**

## Error notifications

Once, there is an unsuccessful attempt to delete the Currency, [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) error notification will be prompted:

_An error occurred while deleting this selection.: {currency name}_

## Exchange rate table

The main function of the table is to update the Currency rate for all the Currencies in webshop list.

**Live exchange rates toggle switch button** - required button - it works only when the cronjobs module is installed into the Prestashop. Small description text tells _Please install the cronjobs module before using this feature_.

**Update exchange rates Call-to-action button** - once clicked, the exchange rates will be updated up to the latest exchange rate day. The success notification will tell _Successful update_ from [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics).

## Multistores

This page is [Multistore dependent](../../../../common-components/multistores-dependent.md) page.
