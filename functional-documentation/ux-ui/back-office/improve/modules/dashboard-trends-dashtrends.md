# Dashboard Trends (dashtrends)

This widget is aligned with the module, that has to be installed into the Prestashop. Once the module is active, the chart will be visible in the main Dashboard page.

![Dashboard Trends interface](<../../../../../.gitbook/assets/image (1).png>)

## Redirection to the Dashboard settings page

After the grid wheel is clicked, there will be an additional {LINK} Dashboard settings page, containing the separate blocks. There will be appropriate input fields from [Form Input UI Group Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--input-group).

### Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* Demo mode Call-to-action button - once hovered, there is a helper text:\
  _This mode displays sample data so you can try your dashboard without real numbers._
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

### Average bank fees per payment method

Note, that the fee construction depends on the payment methods, that are installed in the webshop. These are the default payment methods set:

* **Bank transfer (currency)** - choosing a fixed fee for each order. By default, the value is 0.2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a fixed fee for each order placed in USD% with Bank transfer._
* **Bank transfer (percentage)** - choosing a percentage fee for each order. By default, the value is 2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a variable fee for each order placed in USD% with Bank transfer. It will be applied on the total paid with taxes._
* **Bank transfer** **(currency)** - choosing a fee for each order. By default, the value is 0.2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a fixed fee for each order placed with a foreign currency with Bank transfer._
* **Bank transfer** **(percentage)** - choosing a fixed fee for each order. By default, the value is 0.2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a fixed fee for each order placed with a foreign currency with Bank transfer._
* **Payments by check** **(currency)** - choosing a fee for each order. By default, the value is 0.2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a fixed fee for each order placed in USD% with Payments by check._
* **Payments by check** **(percentage)** - choosing a fee for each order. By default, the value is 2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a variable fee for each order placed in USD% with Payments by check. It will be applied on the total paid with taxes._
* **Payments by check** **(currency)** - choosing a fee for each order. By default, the value is 0.2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a fixed fee for each order placed with a foreign currency with Payments by check._
* **Payments by check** **(percentage)** - choosing a fee for each order. By default, the value is 2. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _Choose a variable fee for each order placed with a foreign currency with Payments by check. It will be applied on the total paid with taxes._

**Save CTA** - call-to-action button that saves the input configuration. If the saving attempt is successful, there will be an [Alert Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) notification:\
_The settings have been successfully updated._

### Error messages

Once there are errors in the fields, there will be an [Alert Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) notifications:

_The {payment method} field is invalid._

### Average shipping fees per shipping method

There is an [Alert Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) notification message:

_Method: Indicate the percentage of your carrier margin. For example, if you charge $10 of shipping fees to your customer for each shipment, but you really pay $4 to this carrier, then you should indicate "40" in the percentage field._

The main difference from the input fields, that one field is of a domestic delivery costs and another is of the overseas delivery costs.

* _**{Carrier name}** -_ by default, the value is 0. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the shipping method name:\
  _For the carrier named {carrier name}, indicate the domestic delivery costs in percentage of the price charged to customers._
* _**{Carrier name}** -_ by default, the value is 0. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the shipping method name:\
  _For the carrier named {carrier name}, indicate the overseas delivery costs in percentage of the price charged to customers._

**Save CTA** - call-to-action button that saves the input configuration. If the saving attempt is successful, there will be an [Alert Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) notification:\
_The settings have been successfully updated._

### Error messages

Once there are errors in the fields, there will be an [Alert Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) notifications:

_The {payment method} field is invalid._

### Other settings

* **Average gross margin percentage** - choosing a fee for each order. By default, the value is 40. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _You should calculate this percentage as follows: ((total sales revenue) - (cost of goods sold)) / (total sales revenue) \* 100. This value is only used to calculate the Dashboard approximate gross margin, if you do not specify the wholesale price for each product._
* **Other fees per order** - choosing a fee for each order. By default, the value is 0. Max 10 characters and numeric values are allowed to be submitted. The helper text is, depending on the currency in the webshop:\
  _You should calculate this value by making the sum of all of your additional costs per order._

**Save CTA** - call-to-action button that saves the input configuration. If the saving attempt is successful, there will be an [Alert Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) notification:\
_The settings have been successfully updated._

### Error messages

Once there are errors in the fields, there will be an [Alert Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) notifications:

_The {payment method} field is invalid._

## Tab components

After each tab is clicked, it will be highlighted with different colors and marked as selected. Then the different information in the chart will appear. The widget has the following tabs:

* **Sales** - shows the sales of certain period and has the following explanation hovered text:\
  _Sum of revenue (excl. tax) generated within the date range by orders considered validated._
* **Orders** - shows the orders of certain period and has the following explanation hovered text:\
  _Total number of orders received within the date range that are considered validated._
* **Cart Value** - shows the cart value of certain period and has the following explanation hovered text:\
  _Average Cart Value is a metric representing the value of an average order within the date range. It is calculated by dividing Sales by Orders._
* **Visits** - shows the visits of certain period and has the following explanation hovered text:\
  _Total number of visits within the date range. A visit is the period of time a user is actively engaged with your website._
* **Conversion Rate** - shows the conversion rates of certain period and has the following explanation hovered text:\
  _Ecommerce Conversion Rate is the percentage of visits that resulted in an validated order._
* **Net Profit** - shows the conversion rates of certain period and has the following explanation hovered text:\
  _Net profit is a measure of the profitability of a venture after accounting for all Ecommerce costs. You can provide these costs by clicking on the configuration icon right above here._

## Chart components

* **X coordinates** - the vertical value amplitude.
* **Y coordinates** - the horizontal time based value amplitude.
* **Hovering on the coordinates** - once hovered in any of the coordinates, there will be a small contextual block appearing with the date, value name, color and value count.
