# Best categories (statsbestcategories)

## Description

This module does not have any settings, it can only be either enabled or disabled.

<figure><img src="../../../../../.gitbook/assets/image (37).png" alt="Best categories in Stats UI"><figcaption><p>Best categories in Stats User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/modules/statsbestcategories.html)

## Common components

* [Filtering components in stats](../../../common-components/stats-page-specific-component/filtering-components-in-stats.md)
* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/back-office-header/quick-access-dropdown.md)&#x20;
* Search input&#x20;
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* [Bell icon ](http://localhost:5000/o/6xEtMtELrAxy06GNiu8U/s/vC6mdBD5H2USRjmzInGX/)
* [Account icon](../../../common-components/account-icon.md)&#x20;

## Best categories section

The block starts with the table component from the [Tables Hoverable UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--hoverable). The table columns contain:

* **Name** - the name and the navigational path of the Category, with the folder-style icons.
* **Total Quantity sold** - calculation of total quantity sold.
* **Total Price** - calculation of total quantity price.
* **Total Margin** - calculation of total margin created in prices.
* **Total Viewed** - calculation of how many users saw the categories.

### Paginationing

Showing the _Displaying {lowest number} - {highest number} of {total number}_ pagination style sentence. It depends on listed items in total.

### Download data CTA button CSV Export

The component is from the [Buttons With Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). The button has a cloud-styled icon and the title CSV Export. Once clicked, the user's computer will get the download popup dialog, and will download the CSV file, with the Customer accounts listed data.

### Final level displaying

There is a component named _Display final level categories only (that have no child categories)_ and from the [Forms Checkboxes UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes). Once the checkbox is marked, the page reloads, with the updated results - shows only the final level path of the categories. Once the checkbox is marked again, the categories show the old results with the full category's path.

## Multistore functionality

The page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.



