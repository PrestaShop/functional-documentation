# Localization

## Description

Localization page enables to configure the units used for products. There are four settings block in the page: Import a localization pack, Configuration,  Local units  and Advanced.

<figure><img src="../../../../../../.gitbook/assets/image (95).png" alt="Localization User Interface"><figcaption><p>Localization User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/international/localization/localization.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../common-components/back-office-header/quick-access-dropdown.md).
* [Search input](../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md).
* [Shop switcher](../../../../common-components/shop-switcher.md).
* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).

## The UI elements

### Localization pack you want to import dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Algeria (First country in alphabetical order)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#localization-pack-you-want-to-import-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Content to import checkboxes

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Marked: States, Taxes Currencies, Languages, Units (e.g. weight, volume, distance). Unmarked: Change the behavior of the price display for groups.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#content-to-import-checkboxes-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Download pack data toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>If set to yes then the localization pack will be downloaded from prestashop.com. Otherwise the local xml file found in the localization folder of your PrestaShop installation will be used.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#download-pack-data-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Default language dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>English (English)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The default language used in your shop.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#default-language-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Set language from browser toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set browser language as default language.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#set-language-from-browser-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Default country dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The default country used in your shop.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#default-country-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Set default country from browser language toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set country corresponding to browser language.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#set-default-country-from-browser-language-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Default currency dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Euro (EUR)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The default currency used in your shop.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#default-currency-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Time zone dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#time-zone-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Weight unit input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>kg</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The default weight unit for your shop (e.g. "kg" for kilograms, "lbs" for pound-mass, etc.).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#weight-unit-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Distance unit input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>km</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The default distance unit for your shop (e.g. "km" for kilometer, "mi" for mile, etc.).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#distance-unit-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Volume unit input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>cl</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The default volume unit for your shop (e.g. "L" for liter, "gal" for gallon, etc.).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#volume-unit-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Dimension unit input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>cm</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The default dimension unit for your shop (e.g. "cm" for centimeter, "in" for inch, etc.).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#dimension-unit-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Language identifier input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>en</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The ISO 639-1 identifier for the language of the country where your web server is located (en, fr, sp, ru, pl, nl, etc.).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#language-identifier-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Country identifier input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The ISO 3166-1 alpha-2 identifier for the country/region where your web server is located, in lowercase (us, gb, fr, sp, ru, pl, nl, etc.).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="localization.md#country-identifier-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Title of Import a localization pack block behavior

It contains title and globe icon.

### Import a localization pack block behavior

This block contains these elements:

* [Localization pack you want to import dropdown](localization.md#localization-pack-you-want-to-import-dropdown-behavior)
* [Content to import checkboxes](localization.md#content-to-import-checkboxes-behavior)
* [Download pack data toggle switch](localization.md#download-pack-data-toggle-switch-behavior)
* [Import button](localization.md#import-button-behavior)

### Localization pack you want to import dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)), in it there are all countries listed in alphabetical order.

### Content to import checkboxes behavior

There are checkboxes ([Stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes)) to choose what content to import.

### Download pack data toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that enable or disable downloading pack data.&#x20;

### Import button behavior

This is CTA button with import icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), once clicked selected data, after a moment appears notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)): _Localization pack imported successfully._ \
When hover mouse pointer on it, button color changes.

### Title of Configuration block behavior

It contains title and setting wheel icon.

### Configuration block behavior

This block contains these elements:

* [Default language dropdown](localization.md#default-language-dropdown-behavior)
* [Set language from browser toggle switch](localization.md#set-language-from-browser-toggle-switch-behavior)
* [Default country dropdown](localization.md#default-country-dropdown-behavior)
* [Set default country from browser language toggle switch](localization.md#set-default-country-from-browser-language-toggle-switch-behavior)
* [Default currency dropdown](localization.md#default-currency-dropdown-behavior)
* [Time zone dropdown](localization.md#time-zone-dropdown-behavior)

### Default language dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)), in it there are all languages listed by Localizations -> Languages list ID number.

### Set language from browser toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that enable or disable language setting from browser.&#x20;

### Default country dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)), in it there are all countries listed in alphabetical order.

### Set default country from browser language toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that enable or disable default country setting from browser language.&#x20;

### Default currency dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)), in it there are all currencies listed by Localizations -> Currencies list ID number.

### Time zone dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)), in it there are all time zones by location.

### Title of Local units block behavior

It contains title and globe icon.

### Local units block behavior

This block contains these elements:

* [Weight unit input](localization.md#weight-unit-input-behavior)
* [Distance unit input](localization.md#distance-unit-input-behavior)
* [Volume unit input](localization.md#volume-unit-input-behavior)
* [Dimension unit input](localization.md#dimension-unit-input-behavior)

### Weight unit input behavior

This is unput with helper text ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter weight unit.

### Distance unit input behavior

This is unput with helper text ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter distance unit.

### Volume unit input behavior

This is unput with helper text ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter volume unit.

### Dimension unit input behavior

This is unput with helper text ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter dimension unit.

### Title of Advanced block behavior

It contains title and setting wheel icon.

### Advanced block behavior

This block contains these elements:

* [Language identifier input](localization.md#language-identifier-input-behavior)
* [Country identifier input](localization.md#country-identifier-input-behavior)

### Language identifier input behavior

This is unput with helper text ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter language identifier.

### Country identifier input behavior

This is unput with helper text ([Forms helpers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter country identifier.

## Multistores functionality

[Multistore dependent](../../../../common-components/multistores-dependent.md) page.&#x20;
