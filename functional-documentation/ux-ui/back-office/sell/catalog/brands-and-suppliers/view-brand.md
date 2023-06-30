# View brand

## Description

This page opens once clicked on certain brand View icon in Brands list. In this page the information about the brand and it's products is displayed.

<figure><img src="../../../../../../.gitbook/assets/image (160).png" alt="Brand View User Interface"><figcaption><p>Brand View User Interface</p></figcaption></figure>

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

## The UI elements

### Edit icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Edit</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="view-brand.md#edit-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Title of Addresses block behavior

It contains title and number of addresses in list in brackets.

### Addresses list behavior

Every created address is shown in separate line in Addresses list. In this list there are 8 columns displayed:

* Name
* Address
* Address (2)
* City
* State
* Home phone
* Mobile phone
* Other

### Edit icon behavior

Once clicked Edit icon opens that Address editing page to make some changes.&#x20;

### Title of Products block behavior

It contains title and number of products in block in brackets.

### Product name behavior

Every product name is a link, once clicked the Product page opens.

### Products  block behavior

Every product is shown in separate section, if it has attributes each attribute is shown in separate line.&#x20;

When product does not have attributes the following product information is provided:

* Ref.:
* EAN13:
* UPC:
* MPN:
* Qty:

Products with Attribute names provide the following information:

* Attribute name
* Reference
* EAN13
* UPC
* MPN
* Available quantity

### Three dot menu icon behavior

Once clicked three dot menu opens options:

* Edit, once clicked redirects to the product editing page.
* Delete, once clicked opens popup with question "Delete _item number_"? The options are:
  * Cancel - it is outlined CTA button ([Buttons outlined UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked cancels deletion and closes popup.
  * Ok - it is CTA button (Buttons basics UI kit), once clicked deletes product, closes popup redirects to Products list and shows notification: _Product successfully deleted._

## Multistores functionality

This is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.
