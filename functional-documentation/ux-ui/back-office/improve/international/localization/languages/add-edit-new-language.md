# Add / Edit New Language

## Description

This page lets the administrator Add or Edit new Language for the whole webshop.

<figure><img src="../../../../../../../.gitbook/assets/image (44).png" alt="Add or Edit Language UI"><figcaption><p>Add or Edit Language User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/international/localization/languages.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../../common-components/account-icon.md)
* [Cancel button](../../../../../common-components/cancel-button.md)
* [Save button](../../../../../common-components/save-button.md)

## Tabs

There are 4 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* **Localization**
* **Languages** (active)
* **Currencies**
* **Geolocation**

## Languages section

The section starts with the globe-style icon and title _Languages_.

### Name

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>32</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### ISO code

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden numbers and symbols.</td><td align="center">For example "12" is invalid"</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Two-letter ISO code (e.g. FR, EN, DE).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>2</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#iso-code-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Language code

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden symbols and numbers.</td><td align="center">For example "12345" is invalid</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>IETF language tag (e.g. en-US, pt-BR).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>5</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#language-code-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Date format (full)

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden various symbols like "%$@#"</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or prefilled input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Short date format (e.g., Y-m-d).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#date-format-full-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Flag

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Upload the country flag from your computer.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#flag-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### "No-picture" image

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Image is displayed when no picture is found.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#no-picture-image-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### RTL language

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable if this language is read from right to left.(Experimental: your theme must be compliant with RTL languages).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#rtl-language-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Status

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Activate this language.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-new-language.md#status-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Shop association behavior

This association block lets user choose, which Multistores can be affected with the settings changes. This component uses a [Checkmark navigation CTA buttons](../../../../../common-components/checkmark-navigation-cta-buttons.md) common component.

### Name behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a language name.

### ISO code behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a ISO code name.

### Language code behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Language code name.

### Date format (full) behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a full format date.

### Flag behavior

Browsing the image file from the UI modal, that appears from the local machine for user. By default, _Choose file(s)_ placeholder appears in the component.

### "No-picture" image behavior

Browsing the image file from the UI modal, that appears from the local machine for user. By default, _Choose file(s)_ placeholder appears in the component.

### RTL language behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. For the text reading orientation, to set the reading from right to left.

### Status behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Enabling or disabling this particular Language.

## Multistores behavior

This page is [Multistores dependent](../../../../../common-components/multistores-dependent.md) page.
