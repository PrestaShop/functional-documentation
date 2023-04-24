# View supplier

## Description

This page displays the particular product Supplier information.

<figure><img src="../../../../../../.gitbook/assets/image (42).png" alt="View Supplier UI"><figcaption><p>View Supplier User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/catalog/brands-and-suppliers/suppliers.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;

## Tabs

There are 2 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* **Brands**
* **Suppliers** (active)

## Products section

The block starts with the title _Products_, and the sum of the supplied products in brackets.

### Supplier table

Each product, that has Suppliers, has its compatible title, with the specific table columns from the [Forms Table UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--basic). There are the following values:

* **Title of the product** - also is linked to the product editing page.
* **Attribute name** - displays attribute name.
* **Supplier reference** - displays supplier reference.
* **Wholesale price** - displays the wholesale price.
* **Reference** - displays the reference.
* **EAN13** - displays the EAN13 code.
* **UPC** - displays the UPC code.

If the supplied product has no information in specific value, it will be shown as _N/A**.**_

## Multistores functionality

This page is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.

