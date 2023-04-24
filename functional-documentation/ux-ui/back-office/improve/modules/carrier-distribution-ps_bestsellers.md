# Carrier distribution (ps\_bestsellers)

## Description

This module does not have any configuration settings, it can only be enabled or disabled. The module itself when is enabled will show up in the back - office section "Stats". The module in the "Stats" section only allows sorting the carrier distribution by date, and export the data.

<figure><img src="../../../../../.gitbook/assets/image (29).png" alt="Carrier distribution in Stats UI"><figcaption><p>Carrier distribution in Stats User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo.html)

## Common components

* [Filtering components in stats](../../../common-components/filtering-components-in-stats.md)
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* Search input (todo link)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;

## Carrier distribution block

The block starts with the [Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component for the filtering and has the following values (statuses) by default:

* **All**
* **Awaiting bank wire payment**
* **Awaiting Cash On Delivery validation**
* **Awaiting check payment**
* **Canceled**
* **Delivered**
* **On backorder (not paid)**
* **On backorder (paid)**
* **Payment accepted**
* **Payment error**
* **Processing in progress**
* **Refunded**
* **Remote payment accepted**
* **Shipped**

The next CTA button component is from the [Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics) named _Filter_. Clicking the button reloads the whole page and refreshes the statistical UI.

### Message

There is a message alert component from the [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics):

_This graph represents the carrier distribution for your orders. You can also narrow the focus of the graph to display distribution for a particular order status._

### Pie chart

The chart represents the statistics data, of number of carrier distributions created. If the mouse pointer is hovered on the chart, the contextual box will appear in the UI, showing the more accurate results.&#x20;

### Download data CTA button CSV Export

The component is from the [Buttons With Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). The button has a cloud-styled icon and the title CSV Export. Once clicked, the user's computer will get the download popup dialog, and will download the CSV file, with the Customer accounts listed data.

## Multistore functionality

The page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.

##
