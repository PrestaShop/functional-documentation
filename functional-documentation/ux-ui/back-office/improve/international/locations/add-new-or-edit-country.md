# Add new or edit country

## Description

The purpose of this page is to add new or edit country.

<figure><img src="../../../../../../.gitbook/assets/image (46).png" alt="Add new or edit country User Interface"><figcaption><p>Add new or edit country User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md).
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../common-components/help-button.md) - [Buttons Outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Language dropdown for input fields](../../../../common-components/language-dropdown-for-input-fields.md).
* Shop association block (todo link)
* [Checkmark navigation CTA buttons](../../../../common-components/checkmark-navigation-cta-buttons.md) - [Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons).
* [Cancel button](../../../../common-components/cancel-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).&#x20;

## The UI elements

### Country input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The field name is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Country name - Invalid characters: &#x3C;>;=#{}</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">Your entry in field name (language English (English)) exceeds max length 64 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#country-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### ISO code input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The iso_code field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Two --or three--letter ISO code (e.g. "us" for United States).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#iso-code-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Call prefix input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">The call_prefix field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>International call prefix, (e.g. 1 for United States).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#call-prefix-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Default currency dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Default store currency</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#default-currency-dropdown-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Zone dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Africa</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Geographical region.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#zone-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Does it need Zip/Postal code? toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#does-it-need-zip-postal-code-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Zip/Postal code format input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>N, L, C letters allowed only</td><td align="center">The zip_code_format field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Indicate the format of the postal code: use L for a letter, N for a number, and C for the country's ISO 3166-1 alpha-2 code. For example, NNNNN for the United States, France, Poland and many other; LNNNNLLL for Argentina, etc. If you do not want PrestaShop to verify the postal code for this country, leave it blank.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#zip-postal-code-format-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Address format input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>firstname lastname company <br>vat_number <br>address1 <br>address2 <br>postcode city Country:name <br>phone</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Some countries require different elements than others. Click on the button below to get the valid default address format for this country.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#address-format-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Use the last registered format button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This will restore your last registered address format.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#use-the-last-registered-format-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Use the default format button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This will restore the default address format for this country.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#use-the-default-format-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Use my current modified format button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This will restore your current address format.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#use-my-current-modified-format-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Clear format button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This will delete the current address format.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#clear-format-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Active toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Display this country to your customers (the selected country will always be displayed in the Back Office.)</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#active-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Contains states toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#contains-states-toggle-switch-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Do you need a tax identification number? toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#do-you-need-a-tax-identification-number-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Display tax label (e.g. "Tax incl.") toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-or-edit-country.md#display-tax-label-e.g.-tax-incl.-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Title of Countries** behavior

Countries is the title of new country addition block, it has title and world icon.

### Country input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter country name.&#x20;

### ISO code input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter country ISO code. When try to add a country with an already existing ISO, the following error will show: \
_This ISO code already exists. You cannot create two countries with the same ISO code._

### Call prefix input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter call prefix number.&#x20;

### Default currency dropdown

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) that allows to select a currency from the ones that are enabled on the shop for this country.

### Zone dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) that allows selecting a zone. All the zones are listed in alphabetical order (both enabled and disabled ones).

### Does it need Zip/Postal code? toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows to choose whether a user living in this country must give a zip code or not when signing up to the shop.

### Zip/Postal code format input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter zip/postal code format.

### Address format input behavior

This is input box is displayed with the following default inputs. Under the help text,  there are the 5 following helper tabs, once clicked its elements are displayed and can be selected. When hover mouse pointer on tab, tab becomes outlined and text color changes. These tabs are:

* Customer - it is opened by default. The following parameters can be added to the address format: lastname, firstname, birthday, email, website, company, siret, reset\_password\_token, htmlFields.
* Warehouse - the following parameters can be added to the address format: reference, name, management\_type, htmlFields.
* Country - the following parameters can be added to the address format: iso\_code, name, zip\_code\_format, htmlFields.
* State - the following parameters can be added to the address format: iso\_code, name, htmlFields.
* Address - the following parameters can be added to the address format: company, lastname, firstname, address1, address2, postcode, city, other, phone, phone\_mobile, vat\_number, dni, htmlFields.

There are errors notifications that can be created in Address format input:

* _This key has already been used.: company_ - when used more than one time.
* _This property does not exist in the class or is forbidden.: Address: phonec -_when entered with grammatical error
* _This name is not allowed.: phonec_ _-_ when entered with grammatical error
* _The firstname field (in tab Address) is required._ - when required field is not entered.

### Use the last registered format button behavior

This is outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), when hover mouse pointer on it, buttons color changes. Once clicked opens modal with question: _Are you sure you want to restore the default address format for this country? T_here are also two buttons:

* OK - blue CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)), once clicked will input the address format box with the last registered formats and close modal.
* Cancel - white outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked will cancel address format restoring and close modal.

### Use the default format button behavior

This is outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), when hover mouse pointer on it, buttons color changes. Once clicked opens modal with question: _Are you sure you want to restore the default address format for this country? T_here are also two buttons:

* OK - blue CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)), once clicked will input the address format box with the last registered formats and close modal.
* Cancel - white outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked will cancel address format restoring and close modal.

### Use my current modified format button behavior

This is outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), when hover mouse pointer on it, buttons color changes. Once clicked will restore current address format.

### Clear format button behavior

This is outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), when hover mouse pointer on it, buttons color changes. Once clicked opens modal with question: _Are you sure you want to restore the default address format for this country? T_here are also two buttons:

* OK - blue CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)), once clicked will delete all elements from the address format box and close modal.
* Cancel - white outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked will cancel address format clearing and close modal.

### Active toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows to enable or disable country.

### Contains states toggle switch

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows to select whether the country has states or not.

### Do you need a tax identification number? toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows to select whether the tax identification number is needed or not.

### Display tax label (e.g. "Tax incl.") toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows choosing whether the tax status (included or excluded) should be displayed next to the prices or not.

## Multistores functionality

[Multistores independent](../../../../common-components/multistores-independent.md) page. Multistore functionality depends on Shop association block settings. The shop association block is displayed when the multistore is enabled and if several shops are configured.
