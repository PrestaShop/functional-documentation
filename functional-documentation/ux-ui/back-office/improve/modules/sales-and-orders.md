# Sales and orders

## Description

This module does not have any configuration settings, it can only be enabled or disabled. The module itself when is enabled will show up in the back - office section "Stats". The module in the "Stats" section only allows to sort the sales and orders.

<figure><img src="../../../../../.gitbook/assets/image (29).png" alt="Sales and orders in Modules manager page User Interface"><figcaption><p>Sales and orders in Modules manager page User Interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (86).png" alt="Sales and orders in Stats User Interface"><figcaption><p>Sales and orders in Stats User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## The UI elements&#x20;

### From input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numbers allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Depends on time period button that was clicked before</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="sales-and-orders.md#from-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### To input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numbers allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Depends on time period button that was clicked before</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="sales-and-orders.md#to-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Time period buttons group behavior

Sales and orders on top has buttons group of 6 buttons ([Buttons group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--button-group)) and they are:

* **Day** - shows this day data.
* **Month** - shows this month data.
* **Year** - shows this year data.
* **Day -1** - shows last day data.
* **Month -1** - shows last month data.
* **Year -1** - shows last year data.

### From input behavior

This input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) is a date picker widget. It allows to enter period beginning date or to choose it from calendar in popup.

### To input behavior

This input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) is a date picker widget. It allows to enter period ending date or to choose it from calendar in popup.

### Save button behavior

This is CTA button with save icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) once clicked saves button from button group or time period inputs settings. When hover mouse pointer on button, its color changes.

### Yellow notification behavior

This is notification with exclamation mark ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)). It has title: _About order statuses._ This notification contains message and it is:\
_In your back office, you can modify the following order statuses: Awaiting Check Payment, Payment Accepted, Preparation in Progress, Shipping, Delivered, Canceled, Refund, Payment Error, Out of Stock, and Awaiting Bank Wire Payment. These order statuses cannot be removed from the back office; however you have the option to add more._

### Blue notification on the top behavior

This is notification with question mark ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)). This notification contains message and it is:\
_The following graphs represent the evolution of your shop's orders and sales turnover for a selected period. You should often consult this screen, as it allows you to quickly monitor your shop's sustainability. It also allows you to monitor multiple time periods. Only valid orders are graphically represented._

### Filtration behavior

For filtration there is a dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) and Filter CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)).\
The dropdown default value is _all countries_, opened dropdown shows list of all countries in alphabetical order. Once country is selected and clicked Filter button, shows only the statistics from that selected country in diagrams.\
When hover mouse pointer on Filter button, its color changes.

### Orders and products diagram behavior

This diagram shows orders and products data of selected period.

### Sales diagram behavior

This diagram shows sales data of selected period in indicated currency.

### CSV Export button behavior

This is CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked downloads instantly the data in CSV format. When hover mouse pointer on Filter button, its color changes.

### Blue notification on the bottom behavior

This is notification with question mark ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)). This notification contains message and it is:\
_You can view the distribution of order statuses below._

### Sales diagram behavior

This is a pie chart of orders statuses. If there is no orders in that period, instead of pie cart there is notification: _No orders for this period._

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.
