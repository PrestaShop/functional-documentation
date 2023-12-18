# Edit / Add Page

## Description

This page is responsible for Editing or Adding a new Design Page to the whole webshop.

<figure><img src="../../../../../../.gitbook/assets/image (81).png" alt="Add new or Edit Page UI"><figcaption><p>Add new or Edit Page User Interface</p></figcaption></figure>

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
* [Text Editing Tools list](../../../../common-components/text-editing-tools-list.md)

## Page section

Page section starts with the title _Pages_ only.

### Page category

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Home</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#page-category-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Title

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field "Title" is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Used in the h1 page tag, and as the default title tag value. Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>255</td><td align="center">This field cannot be longer than 255 characters - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### SEO preview

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>SEO preview block UI</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#seo-preview-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta title

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td><em>0 of 70 characters used (recommended)</em><br>Used to override the title tag value. If left blank, the default title value is used. Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#meta-title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta description

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td><em>0 of 160 characters used (recommended)</em><br>Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#meta-description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta keywords

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input, placeholder "Add tag"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>To add tags, click in the field, write something, and then press the "Enter" key. Invalid characters: &#x3C;>={}</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#meta-keywords-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Friendly URL

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field "Friendly URL" is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Various symbols like etc. @#$@#$ are not allowed.</td><td align="center">"@#$@#$%@%@#$%#@$%" is invalid. - Language: English (English)</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Only letters and the hyphen (-) character are allowed.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#friendly-url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Page content

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Prefilled or empty input values</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td><em>0 of 21844 characters allowed</em></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#page-content-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Indexation by search engines

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#indexation-by-search-engines-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Displayed

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-page.md#displayed-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Save and preview CTA button

[Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics) component. Almost the same as [Save and stay](../../../../common-components/save-and-stay-button.md) button from Common components.

## Behavior descriptions

### Page category behavior

UI block with the [Forms Radio Buttons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons) components. Ability to choose the desired category for the Page.

### Title behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to add or edit a Title for the Page.

### SEO preview behavior

UI block with the preview of SEO UI. Uses [Texts UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/texts--texts) components.&#x20;

### Meta title behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Meta title text for the Page.

### Meta description behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Meta description text for the Page.

### Meta keywords behavior

[PS Tags UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/ps-tags--ps-tags) component. Ability to edit or add Meta keywords (separated by comma) for the Page.

### Friendly URL behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Friendly URL text for the Page.

### Page content behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Ability to edit or add Content text for the Page.

### Indexation by search engines behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Ability to disable or enable the SE (like Google, etc.) indexation for the Page.

### Displayed behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Ability to disable or enable the whole Page appearance in the webshop.

## Multistores functionality

This page is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.



