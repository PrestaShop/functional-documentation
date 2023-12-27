# Preferences

## [Advanced parameters](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/663/functional-documentation/ux-ui/back-office/configure/advanced-parameters)Description

In the payment preferences page merchant is allowed to choose which payment method should be available to customers depending on the currency, the country, the group or the carrier.

<figure><img src="../../../../../.gitbook/assets/image (54).png" alt="Preferences User Interface"><figcaption><p>Preferences User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

{% content-ref url="../../../advanced-parameters/" %}
[advanced-parameters](../../../advanced-parameters/)
{% endcontent-ref %}

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Shop switcher](../../../common-components/shop-switcher.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).

## Behaviors description

### Alert notification behavior

This is notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) on top of the page and it is: \
_This is where you decide what payment modules are available for different variations like your customers' currency, group, and country._\
_A check mark indicates you want the payment module available. If it is not checked then this means that the payment module is disabled._

### Title of Currency restrictions block behavior

It contains title and euro icon.

### Currency restrictions block behavior

Under the block title there is helper text: _Please select available currencies for every payment module._

In this block Currency restrictions row is firstly shown (below are the currencies installed on the shop as well as customer currency and shop default currency). On the top right side by default there are these columns:

* Bank transfer
* Payments by check

Any custom payment method added will be shown as well in one more column. \
Each payment method in each row has checkboxes ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)). Settings in this block can be saved by clicking block's Save button.

### Title of Group restrictions block behavior

It contains title and people icon.

### Group restrictions block behavior

Under the block title there is helper text: _Please select available payment modules for every customer group._

In this block Group restrictions row is firstly shown, below are the customer groups shown - Visitor, Guest, Customer. On the top right side by default there are these columns:

* Bank transfer
* Payments by check

Any custom payment method added will be shown as well in one more column. \
Each payment method in each row has checkboxes ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)). Settings in this block can be saved by clicking block's Save button.

### Title of Country restrictions block behavior

It contains title and world icon.

### Country restrictions block behavior

Under the block title there is helper text: _Please mark each checkbox for the country, or countries, in which you want the payment module(s) to be available._

In this block Country restrictions row is firstly shown, below are all the countries listed in alphabetical order. On the top right side by default there are these columns:

* Bank transfer
* Payments by check

Any custom payment method added will be shown as well in one more column. \
Each payment method in each row has checkboxes ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)). Settings in this block can be saved by clicking block's Save button.

### Title of Carrier restrictions block behavior

It contains title and wan icon.

### Carrier restrictions block behavior

Under the block title there is helper text: _Please select available payment modules for every carrier._

In this block Carrier restrictions row is firstly shown, below are all the carriers listed, by default there are:&#x20;

* 1 - Click and collect (Pick up in-store)
* 2 - My carrier (Delivery next day!)
* 3 - My cheap carrier (Buy more to pay less!)
* 4 - My light carrier (The lighter the cheaper!).&#x20;

On the top right side by default there are these columns:

* Bank transfer
* Payments by check

Any custom payment method added will be shown as well in one more column. \
Each payment method in each row has checkboxes ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)). Settings in this block can be saved by clicking block's Save button.

## Multistores functionality

[Multistore dependent](../../../common-components/multistores-dependent.md) page.&#x20;

Payment modules can be configured only in each multistore shop separately. When page opened in All shops context, appear alert notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)): \
_Note that this page is available in a single shop context only. Switch context to work on it._
