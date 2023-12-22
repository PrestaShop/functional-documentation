# Payment methods

## Description

In this page there are show payment methods and their modules.

<figure><img src="../../../../../.gitbook/assets/image (22).png" alt="Payment Methods User Interface"><figcaption><p>Payment Methods User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/payment/payment-methods.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/e-commerce-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Shop switcher](../../../common-components/shop-switcher.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).

## Behaviors description

### Title of Active payment behavior

It contains title and credit card icon.

### Payment module behavior

Payment modules in this page is shown with these elements:

* Module logo - each module has its own logo on top of module block.
* Module name - is next to module logo written as black color text.
* Module version number and author - they are in grey color text on the right side from module name.
* Short module description - is written in grey color text under module name, version number and author.
* [Configure button](payment-methods.md#configure-button-behavior).

### Configure button behavior

It is outlined CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked redirects to that module settings page. When hover mouse pointer on it, button color changes. \
Cash on delivery (COD) module does not have Configure button, this module only can be enabled or disabled in Modules manager page.

## Multistores functionality

[Multistore dependent](../../../common-components/multistores-dependent.md) page.&#x20;

Payment modules can be configured only in each multistore shop separately. When page opened in All shops context, appear alert notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)): \
_Note that this page is available in a single shop context only. Switch context to work on it._
