# Edit / Add feature page

## Description

This page is responsible for existing Feature editing or the adding of the new Feature.

<figure><img src="../../../../../../../.gitbook/assets/image (6).png" alt="Add or Edit UI"><figcaption><p>Add or Edit Feature User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/catalog/attributes-and-features/attributes.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../../common-components/account-icon.md)&#x20;
* [Cancel button](../../../../../common-components/cancel-button.md)
* [Checkmark navigation CTA buttons](../../../../../common-components/checkmark-navigation-cta-buttons.md)

## Tabs

There are 2 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* **Attributes**
* **Features** (active)

## Feature section

The block starts with an information-styled icon and a title _Feature_.

### Name

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field public_name is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Forbidden values</td><td>&#x3C;>;=#{}”</td><td align="center">The name field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Your internal name for this attribute. Invalid characters &#x3C;>;=#{}” </td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>128</td><td align="center">Your entry in field name (language English (English)) exceeds max length 128 chars (incl. HTML tags).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-feature-page.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### URL

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">Tht e field name is required at  least in "<em>default language</em>”</td><td>Error message if not allowed</td></tr><tr><td>Forbidden values</td><td>&#x3C;>;=#{}”</td><td align="center">The name field is invalid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>When the Faceted Search module is enabled, you can get more detailed URLs by choosing the word that best represent this attribute. By default, PrestaShop uses the attribute's name, but you can change that setting using this field.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Invalid characters: &#x3C;>;=#{}_</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-feature-page.md#url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Meta title

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>When the Faceted Search module is enabled, you can get more detailed page titles by choosing the word that best represent this attribute. By default, PrestaShop uses the attribute's name, but you can change that setting using this field.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-feature-page.md#meta-title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Indexable

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Use this attribute in URL generated by the Faceted Search module.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-add-feature-page.md#behaviors-description">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Name behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding a Feature name.

### URL behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding the URL for Feature.

### Meta title behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For editing or adding the Meta title name.

### Indexable behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Enabling or disabling the Indexable functionality for the Feature.

### Shop association behavior

This association block lets user choose, which Multistores can be affected with the settings changes. This component uses a [Checkmark navigation CTA buttons](../../../../../common-components/checkmark-navigation-cta-buttons.md) common component.

## Multistores functionality

This page is [Multistores independent](../../../../../common-components/multistores-independent.md) page.
