# Add or Edit Taxes

## Description

This interface provides the ability to add customized tax or edit the existing tax of the Prestashop tax list.

<figure><img src="../../../../../../.gitbook/assets/image (5) (1).png" alt="Add or Edit Taxes UI"><figcaption><p>Add or Edit Taxes User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Save button (todo link)
* Cancel button (todo link)
* E-commerce logo (todo link)
* Version number (todo link)
* Quick access dropdown (todo link)
* Search input (todo link)
* Shop switcher with eye icon (todo link)
* Bell icon (todo link)
* Trophy icon (todo link)
* Account icon (todo link)

## Navigating to the Add or Edit Taxes form

The form can be accessed in 2 ways:

* Adding a new Tax, Add new tax button must be clicked.
* Clicking on the Edit button of an item in the list

## Tax Editing form

If the webshop is on All shops context, there will be a blue notification message _Note that this feature is available in all shops context only. It will be added to all your stores._

### **Name**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden symbols &#x3C;>;=#{}$</td><td align="center">This field is invalid, it must contain numeric values</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Tax name to display in carts and on invoices (e.g. "VAT"). Invalid characters: &#x3C;>;=#{}.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-taxes.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Rate**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden symbols &#x3C;>;=#{}$</td><td align="center">This field is invalid, it must contain numeric values</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Format: XX.XX or XX.XXX (e.g. 19.60 or 13.925)</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-taxes.md#rate-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-taxes.md#rate-behavior-1">link to the behavior</a></td><td align="center">-</td><td> </td></tr></tbody></table>

## Behaviors descriptions

### Name behavior

Text field for naming the specific Tax with a Language selector. The help text is _Tax name to display in carts and on invoices (e.g. "VAT"). Invalid characters: <>;=#{}_. If the webshop has multiple languages installed, the language dropdown switcher will appear. Different Names can be saved on the different languages, by changing the dropdown value, and clicking Save. If the Name field is left empty after submission, there will be an error below the Name field - _The field name is required at least in your default language._ If the Name is typed with more than 32 characters, the interface will be prompted with the error - _This field cannot be longer than 32 characters - Language: {the language of the name}_. If the invalid characters are typed, the interface will prompt _{invalid string} is invalid - Language: {the language of the name}_. This component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### Rate behavior

Numeric input field, allows setting the Rate of the tax. The help text is - _Format: XX.XX or XX.XXX (e.g. 19.60 or 13.925)_. Range must be typed as a single numbers or single numbers with decimals. If there is an empty Rate field after submission, there will be a browser error notification, requesting to fill the empty field. If the Rate is typed with more than 6 characters, the interface will be prompted with the error - _This field cannot be longer than 6 characters_. If the field is typed with character letters, the error will be _This field is invalid, it must contain numeric values_. This component is from [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal).

### Enable behavior

Allows to Enable or Disable tax. This component is from [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

## Notifications after submissions

If there are some invalid characters typed in the name after submission, there will be an error below the Name field - _"{invalid character}" is invalid - Language: {the language of the name}_.
