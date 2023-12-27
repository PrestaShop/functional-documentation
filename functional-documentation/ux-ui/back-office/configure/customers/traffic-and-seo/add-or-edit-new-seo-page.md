# Add or Edit new SEO page

## Description

This UI represents the function of adding / editing a SEO & URL page, which is dedicated to Meta Tags section.

<figure><img src="../../../../../../.gitbook/assets/image (40).png" alt="Adding or Editing SEO User Inteface"><figcaption><p>Adding or Editing SEO &#x26; URL page User Inteface</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (9) (1).png" alt="SEO &#x26; URL listing User Interface"><figcaption><p>SEO &#x26; URL listing User Interface</p></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/trafic-and-seo/seo-and-urls.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../../common-components/cancel-button.md)
* [E-commerce logo ](../../../../common-components/back-office-header/prestashop-logo.md)
* [Version number](../../../../common-components/prestashop-version-number.md)
* [Quick access dropdown ](../../../../common-components/quick-access-dropdown.md)
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)
* [Language dropdown for input fields](../../../../common-components/language-dropdown-for-input-fields.md)
* [Save button](../../../../common-components/save-button.md)
* [Cancel butt](../../../../common-components/cancel-button.md)

## Top UI section

* **Tabs** - there are 3 tabs in the Traffic & SEO section:
  * **SEO & URLs** - the current opened tab.
  * **Search Engines**

## Table UI section

### **Meta tags**&#x20;

Table title, identifying the name of the table.

### **Page name**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>first SEO page name (attachment)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Name of the related page.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-new-seo-page.md#page-name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Page title**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">This value is not valid.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Title of this page. Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-new-seo-page.md#page-title-behavior">link to the behavior</a></td><td align="center">-</td><td> </td></tr></tbody></table>

### **Meta description**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>A short description of your shop. Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-new-seo-page.md#meta-description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Meta keywords**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">This value is not valid.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder with the name "Add tag"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>List of keywords for search engines. To add tags, click in the field, write something, and then press the "Enter" key. Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-new-seo-page.md#meta-keywords-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Rewritten URL**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field url_rewrite is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>For instance, "contacts" for http://example.com/shop/contacts to redirect to http://example.com/shop/contact-form.php Only letters and hyphens are allowed.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-or-edit-new-seo-page.md#rewritten-url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### **Page name behavior**

This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group). Required field - there is a dropdown selection, of available page names, that can be selected for SEO edition. Once the dropdown is clicked, a box is dropped-down with the list of page names, and the text input field, for searching the desired page name. If there are few letters typed, the search will show the appropriate results according to the input. The search result strings are generated from 2 segments divided with the dash "-" character:

* **Module name**
* **Page name string** There is an explanation placeholder _Name of the related page._ right below the input field. By default, the first page name _pdf-invoice_ is automatically selected in this field.

### **Page title behavior**

This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group). By default, this field is empty. A new page Title can be stored in this text field. The text can be stored in different languages, according to ones that are installed in the webshop. The language can be selected using the **language dropdown**, where all the available languages are listed. This input field has no character limit.&#x20;

### Meta description behavior

This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group). By default this field is empty. A new Meta description can be stored in this text field. The text can be stored in different languages, according to ones that are installed in the webshop. The language can be selected using the **language dropdown**, where all the available languages are listed. This input field has no character limit. There is a small description, _A short description of your shop. Invalid characters: <>={}_ right down the input field, indicating, what this field is used for and what characters should be used.

### Meta keywords behavior

This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group). By default this field is empty. Only a placeholder _Add tag_ is displayed in the input field. New Meta tags can be stored continuously, each separated by typing a single comma "," character or just pressing Enter in the keyboard. The text can be stored in different languages, according to ones that are installed in the webshop. The language can be selected using the **language dropdown**, where all the available languages are listed. This input field has no character limit. There is a small description _List of keywords for search engines. To add tags, click in the field, write something, and then press the "Enter" key. Invalid characters: <>={}_ right down the input field, indicating, what this field is used for and what characters should be used.

### Rewritten URL behavior

This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group). Required field - by default, this field is empty. The URL can be changed with a new URL for a specific Page name, so that the URL will be shown as rewritten in the URL path. The text can be stored in different languages, according to ones that are installed in the webshop. The language can be selected using the **language dropdown**, where all the available languages are listed. This input field has no character limit. There is a small description _For instance, "contacts" for_ [_http://example.com/shop/contacts_](http://example.com/shop/contacts) _to redirect to_ [_http://example.com/shop/contact-form.php_](http://example.com/shop/contact-form.php) _Only letters and hyphens are allowed._ right down the input field, indicating, what this field is used for and what characters should be used. Once, there is a mistake or invalid character typed in the URL, after the form submission, the user will be notified by the red-texted error below the _Rewrite URL_ field - _"{invalid text}" is invalid. - {showing the language, where the error is coming from}_. When this field is left empty after submission, there is a red-texted error _The field url\_rewrite is required at least in your default language._ prompted below the field.

## Multishop functionality

This page is [Multistore dependent](../../../../common-components/multistores-dependent.md) page.

There is a blue information message in the Top UI of the page, containing the message _You can only display the page list in a shop context._, meaning, that the SEO URL edition can be done in All Shops context, but if there is a need to **Edit** the existing SEO URL, it can be Edited by switching the content to single shop context.
