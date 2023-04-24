# Add or Edit Tax Rule

## Description

This page interface allows editing existing or add a brand new Tax Rule to the Prestashop Tax system.

<figure><img src="../../../../../../.gitbook/assets/Capture d’écran du 2023-04-24 10-28-18.png" alt=""><figcaption><p>Add / Edit tax</p></figcaption></figure>



<figure><img src="../../../../../../.gitbook/assets/Screenshot 2022-11-14 at 17-04-43 Tax Rules Add new • ps_1780.png" alt="Add or Edit Tax Rules UI"><figcaption><p>Add / Edit Tax ( LABEL : multishop )  </p></figcaption></figure>

## QA <a href="#common-components" id="common-components"></a>

[Link to test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/international/taxes/tax-rules.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Save and stay button (todo link)
* Save button (todo link)
* Cancel button (todo link)

## Top elements

* **Add New or Edit:{edited Tax Rule name}** - page title.
* **Add new tax rule button** - toggles the expanding or subtracting the Tax rule creating and editing section below.
* **Help** - a side-bar with the helpful information, how to navigate in this page.
* **Tabs: Taxes and Tax Rules** - navigation tabs for taxes and tax rules.

## Navigating to the Add or Edit Tax Rules form

The form can be accessed in 2 ways:

* Add new Tax Rules group button must be clicked from the Tax Rules listing.
* Clicking on the Edit button of a Tax Rules item in the listing.

## Tax Rules Editing form

* **Name** label - mandatory - text field for naming the specific Tax Rule. Once hovered, there is a tooltip text prompted - _Invalid characters: <>;=#{}_.

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field name is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td><em>Invalid characters: &#x3C;>;=#{}</em></td><td align="center">(text)  is invalid</td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">Add : empty<br>Edit : Taxe rule name</td><td></td></tr><tr><td>Help text</td><td>Tax name to display in carts and on invoices (e.g. "VAT"). Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td><em>Invalid characters: &#x3C;>;=#{}</em></td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>

* **Enable** - toggle - allows to Enable or Disable tax rule. By default - Tax rule toggle is disabled.



* **Shop association**  ( LABEL MULTISTORE ) - a widget, that allows to select the desired Multistores or Shop Groups, where Tax Rules could be applied. The widget contains 4 buttons:
  * **Collapse all** ( LABEL MULTISTORE ) - subtracts the Multistores and Shop groups tree.
  * **Expand all** ( LABEL MULTISTORE ) - expands the Multistores and Shop groups tree.
  * **Check all** ( LABEL MULTISTORE ) - checkmarks all the Multistores and Shop groups items in tree.
  * **Uncheck all** ( LABEL MULTISTORE ) - unchecks all the Multistores and Shop groups items in tree.
* **Cancel** - button cancels the Tax editing form.
* **Save and stay** - button saves the configured form and redirects to the same page.

## New Tax Rule panel (appears after submitting the Tax Rules main form)

<figure><img src="../../../../../../.gitbook/assets/Capture d’écran du 2023-04-24 11-01-14.png" alt=""><figcaption></figcaption></figure>

* **Country** - dropdown, allows the selection of country for specific Tax Rule. By default it is set to All.
* **Zip/Postal code range** - input, defines the zip or postal code for Tax Rule.

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">TODO</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td><em>Depending on which region is used</em></td><td align="center">(text)  is invalid</td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">Add : 0<br>Edit: the current ZipCode</td><td></td></tr><tr><td>Help text</td><td>            -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>             <em>-</em></td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>



* **Behavior** - dropdown, allows the Tax rule to have a specific behavior, when address matches multiple rules. Once hovered, there is an explanation prompted:

_You must define the behavior if an address matches multiple rules:_\
_This tax only: Will apply only this tax_\
_Combine: Combine taxes (e.g.: 10% + 5% = 15%)_\
_One after another: Apply taxes one after another (e.g.: 100 + 10% => 110 + 5% = 115.5)_

The Behavior dropdown values are the following:&#x20;

* **This tax only** - rule applies only one current tax.&#x20;
* **Combine** - rule combines the current tax with another tax.&#x20;
* **One after another** - rule combines the current tax, and then after the combination result it combines the next rule.



* **Tax** - dropdown, allows to apply specific Tax from the list. Once hovered, there will be a text prompted _(Total tax: 9%)_.
* **Description** - input field allows to type specific description of the Tax Rule.
*



<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center"></td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                  - </td><td align="center">(text)  is invalid</td><td></td></tr><tr><td>Default value</td><td><p>Add: empty </p><p>Edit: Current value</p></td><td align="center"></td><td></td></tr><tr><td>Help text</td><td>              - </td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>             <em>-</em></td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>



* **Save and stay** - button saves the configured form and redirects to the same page with the green success notification _Successful update._

## Country panel

If there are specific countries added, after clicking **Save and stay**, the lower panel will appear with the countries list. The table has the following headers:

<figure><img src="../../../../../../.gitbook/assets/Capture d’écran du 2023-04-24 11-37-35.png" alt=""><figcaption></figcaption></figure>

**Table country**&#x20;

* **Country** - displays the country name.
* **State** - if defined country has a state, it can be displayed.
*   **Zip/Postal code** - if there is available Zip or Postal code, it can be displayed here. If the field is typed with the invalid characters, there will be an error notification prompted:

    _There are 2 errors. The Zip/Postal code is invalid. It must be typed as follows: 0000 for Afghanistan. zipcode\_from is invalid._
* **Behavior** - displays the Tax behavior selected for specific country.
* **Tax** - displays the Tax rule code.
* **Description** - displays the specific description for the Tax rule.
* **Edit** - redirects to the same page for editing the current Tax rule.
* **Dropdown > Delete** - delete the specific country Tax rule from list. After clicking the **Delete**, there is a pop-up prompted with the exclamation error sign and text _Delete selected item?_ and possible values - **Yes** or **No**. No leads to closing the pop-up, Yes - deletes the country tax rule, with the page reloading and the success message _Successful update._
* **Bulk actions widget** - if there are more than 1 currency Tax rule in the list, some of them can be selected by checkboxes separately, or can be **Selected all** or **Unselected all**. After the selections, **Delete selected** will delete the selected Tax rules from the list (confirmation pop-up will be prompted as well).
