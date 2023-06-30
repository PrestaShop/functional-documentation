# Add / Edit Search Engine

## Description

This UI lets the administrator edit or add Search Engine value to the list.

<figure><img src="../../../.gitbook/assets/image (20) (2).png" alt=""><figcaption><p>Add or Edit Search Engine User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../ux-ui/common-components/cancel-button.md)
* [E-commerce logo ](../../ux-ui/common-components/back-office-header/prestashop-logo.md)
* [Version number](../../ux-ui/common-components/prestashop-version-number.md)
* [Quick access dropdown ](../../ux-ui/common-components/back-office-header/quick-access-dropdown.md)
* [Search input](../../ux-ui/common-components/search-input-field.md)&#x20;
* [Shop switcher with eye icon](../../ux-ui/common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../ux-ui/common-components/account-icon.md)
* [Language dropdown for input fields](../../ux-ui/common-components/language-dropdown-for-input-fields.md)
* [Save button](../../ux-ui/common-components/save-button.md)
* [Cancel button](../../ux-ui/common-components/cancel-button.md)

### Top UI elements

* **Tabs** - components from [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills). Navigation tabs for Traffic & SEO menu:
  * SEO & URLs.
  * Search Engines- highlighted tab.
  * Referrers.

### Main table UI elements

* **Referrer** - the title of the table.

### **Server**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The server field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">The field name is required at least in your default language.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>34</td><td align="center">This value is too long. It should have 34 characters or less. - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-search-engine.md#server-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **$ GET variable**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The getvar field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">The field name is required at least in your default language.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>6</td><td align="center">This value is too long. It should have 6 characters or less. - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-search-engine.md#usd-get-variable-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### **Server behavior**&#x20;

Required - input, where exact Search Engine associated Server name is defined. It can also be added as a new name. The field has notification errors, once the field is left empty, after submission - _The server field is required._ If the field has invalid characters, the UI will show the error _The server field is invalid._ The field can handle max 34 characters, up to 34 characters are not stored in database.

### **$ GET variable behavior**&#x20;

Required - input, where Search Engine associated Variable name is defined. It can also be added as a new variable name. The field has notification errors, once the field is left empty, after submission - _The getvar field is required._ If the field has invalid characters, the UI will show the error _The getvar field is invalid._ The field can handle max 6 characters, up to 6 characters are not stored in database.

## Multistore functionality

This page is Multistore independent (todo link) page.

Once the entry of Search Engine is added or edited in separate Multistore, it affects all the rest of Multistores in the same way. The management will be done in all Multistores simultaneously.
