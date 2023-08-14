# New & Experimental Features

## Description

This page allows to test new and experimental features in store.

<figure><img src="../../../../../../../.gitbook/assets/image (35).png" alt="New &#x26; Experimental Features in single store User Interface"><figcaption><p>New &#x26; Experimental Features in single store User Interface</p></figcaption></figure>

<figure><img src="../../../../../../../.gitbook/assets/image (3) (1).png" alt="New &#x26; Experimental Features in multi store User Interface"><figcaption><p>New &#x26; Experimental Features in multi store User Interface</p></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/advanced-parameters/experimental-features.html)

## **Common components**

* [​Breadcrumbs navigation](../../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Help button](../../../../../common-components/help-button.md) - [Buttons outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* ​[Save button](../../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../../common-components/back-office-header/quick-access-dropdown.md)&#x20;
* [Search input](../../../../../common-components/search-input-field.md)
* [Shop switcher](../../../../../common-components/shop-switcher.md)
* Bell icon (todo link)
* [Account icon](../../../../../common-components/account-icon.md)&#x20;

## The UI elements

### New product page - Single store toggle switch

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>This page benefits from increased performance and includes new features such as a new combination management system.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="new-and-experimental-features.md#new-product-page-single-store-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### New product page - Multi store toggle switch

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Access the new product page, even in a multistore context. This is a work in progress and some features are not available.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="new-and-experimental-features.md#new-product-page-multi-store-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Title of Experimental features section behavior

This title includes the title and settings icon.&#x20;

### **Yellow alert message behavior**

On the top of the Experimental features section is an alert message ([Alerts basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/docs/alerts--basics)) and it is: _Testing a feature before its official release can be exciting. However, you must be aware of the potential risks of such experiments:_

* _Experimental features are still under development. Enabling them could therefore have unintended consequences and cause data loss._
* _In any case, you should never experiment in production._

### New product page - Single store toggle switch behavior

This is on-off toggle switch ([Forms switch story UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story)). \
When toggle switch state is enabled, Save button is activated.

### New product page - Multi store toggle switch behavior

This is on-off toggle switch ([Forms switch story UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story)). \
When toggle switch state is enabled, Save button is activated.

### Disabled text behavior

In single store there is shown disabled text in Experimental features section and it is:\
_New product page - Multi store. Access the new product page, even in the multistore context. This is a work in progress and some features are not available._

In multi store there is shown disabled text in New features section and it is:\
_New product page - Single store. This page benefits from increased performance and includes new features such as a new combination management system._

## Multistores behavior

This page is available in all shops contexts only. If this page is opened in one shop context, it is changed to all shops. Also, there is alert message ([Alerts basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/docs/alerts--basics)) and it is:\
_Note that this page is available in all shops context only, this is why your context has just switched._
