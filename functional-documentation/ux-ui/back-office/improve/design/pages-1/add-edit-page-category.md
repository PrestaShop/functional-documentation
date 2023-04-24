# Add / Edit Page Category

## Description

In this page, the administrators can edit the existing or add absolutely new CMS Category in the webshop system.

<figure><img src="../../../../../../.gitbook/assets/image (8) (3).png" alt="Adding or Editing new page category UI"><figcaption><p>Adding or Editing new page category User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/design/pages.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)
* [Save button](../../../../common-components/save-button.md)
* [Cancel button](../../../../common-components/cancel-button.md)

## Page section

Page section starts with the title _CMS Category_ only.

### Name

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Symbols like "#$%@" etc. are forbidden</td><td align="center">"@$@#$@#$@" is invalid - Language: English (English)</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters:&#x3C;>;=#{}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Displayed

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#displayed-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Parent category

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Home</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#parent-category-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Description

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input values</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td><em>-</em></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta title

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters:&#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">This field cannot be longer than 255 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#meta-title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta description

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters:&#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>512</td><td align="center">This field cannot be longer than 512 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#meda-description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta keywords

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input, placeholder "Add tag"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Invalid characters:&#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">This field cannot be longer than 255 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#meta-keywords-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Friendly URL

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field friendly_url is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Various symbols like etc. @#$@#$ are not allowed.</td><td align="center">"@#$@#$%@%@#$%#@$%" is invalid. - Language: English (English)</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Unless the 'Accented URL' option is enabled (in Shop parameters > Traffic &#x26; SEO), only letters, numbers, underscores (_), and hyphens (-) are allowed.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">This field cannot be longer than 64 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-edit-page-category.md#friendly-url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Name behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add the Name of the CMS Category.

### Displayed behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Ability to disable or enable the whole Page appearance in the webshop.

### Parent category behavior

UI block with the [Forms Radio Buttons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons) components. Ability to choose the desired Parent category for the CMS Category page.

### Description behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Description text for the CMS Category Page.

### Meta title behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Meta title text for the CMS Category Page.

### Meda description behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Meta description text for the CMS Category Page.

### Meta keywords behavior

[PS Tags UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/ps-tags--ps-tags) component. Ability to edit or add Meta keywords (separated by comma) for the Page.

### Friendly URL behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Friendly URL text for the Page.

## Multistores functionality

This page is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.



