# Customer accounts (statsregistrations)

## Description

This module does not have any configuration settings, it can only be enabled or disabled. The module itself when is enabled will show up in the Back-Office section "Stats". The module in the "Stats" section only allows sorting the customer accounts by date.

The certain Customer accounts section is selected by navigating the menu on the left.

<figure><img src="../../../../../.gitbook/assets/image (31).png" alt="Customer accounts in Stats UI"><figcaption><p>Customer accounts in Stats User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/modules/statsregistrations.html)

## Common components

* [Filtering components in stats](../../../common-components/filtering-components-in-stats.md)
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* Search input (todo link)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;

## Customer accounts block

The section starts with the [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) blue message:

* _Number of visitors who stopped at the registering step: {number}_
* _Number of visitors who placed an order directly after registration: {number}_
* _Total customer accounts: {number}_

### Guide

The section starts with the [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) yellow message:

_**Number of customer accounts created**_

_The total number of accounts created is not in itself important information. However, it is beneficial to analyze the number created over time. This will indicate whether or not things are on the right track._

### **How to act on the registrations' evolution?**

The section starts with the [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) yellow message:

_If you let your shop run without changing anything, the number of customer registrations should stay stable or show a slight decline. A significant increase or decrease in customer registration shows that there has probably been a change to your shop. With that in mind, we suggest that you identify the cause, correct the issue and get back in the business of making money!_\
_Here is a summary of what may affect the creation of customer accounts:_

* _An advertising campaign can attract an increased number of visitors to your online store. This will likely be followed by an increase in customer accounts and profit margins, which will depend on customer "quality." Well-targeted advertising is typically more effective than large-scale advertising... and it's cheaper too!_
* _Specials, sales, promotions and/or contests typically demand a shoppers' attentions. Offering such things will not only keep your business lively, it will also increase traffic, build customer loyalty and genuinely change your current e-commerce philosophy._
* _Design and user-friendliness are more important than ever in the world of online sales. An ill-chosen or hard-to-follow graphical theme can keep shoppers at bay. This means that you should aspire to find the right balance between beauty and functionality for your online store._

### X and Y chart

The chart represents the statistics data, of number of customer accounts created. If the mouse pointer is hovered on the chart and especially on the particular coordinate, the contextual box will appear in the UI, showing the more accurate results.&#x20;

### Download data CTA button CSV Export

The component is from the [Buttons With Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). The button has a cloud-styled icon and the title CSV Export. Once clicked, the user's computer will get the download popup dialog, and will download the CSV file, with the Customer accounts listed data.

## Multistore functionality

The page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.

