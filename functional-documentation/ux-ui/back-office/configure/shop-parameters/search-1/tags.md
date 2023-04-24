# Tags

## Description

This useful feature lets creating specific tags and associating them to the products. Webshop users will find the products more easily.

<figure><img src="../../../../../../.gitbook/assets/image (28).png" alt="Tags UI"><figcaption><p>Tags User Interface - Empty table</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (57).png" alt=""><figcaption><p>Tags User Interface - Filled table</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/search/tags.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;
* [Configuration block](../../../../common-components/configuration-block.md)
* 4 table header tools (todo link)

## Add new tag CTA button

Button from the [Buttons with icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). Clicking the button redirects to the adding a new Tag page.

## Tabs navigation

The page has a navigation component from the [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills). The tabs are:

* **Search**
* **Tags** (active tab)

## Tags block

The section starts with a table and a title _Tags_ and a number of tags in the numeric value. The table is from the [Tables Hoverable UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--hoverable). Other table components:

* **No records found (otpionally displayed)** - if the table is empty, there is a warning with the exclamation mark in the middle of the table.
* **ID** - displays the ID number of the tag.
* **Language** - shows the tag origin language.
* **Name** - shows the tag name.
* **Products** - shows how many products are associated with the tag.
* **Edit or Delete dropdown** - [Dropdowns With Button Split UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split) component, that lets delete or edit the certain Tag.

## Multistores dependent

This page is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.
