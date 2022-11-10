# Stats

## Description

This page displays all the Prestashop statistics information.

![Stats interface](<../../../../.gitbook/assets/image (1) (1).png>)

## Components description

### Top UI elements

* [Breadcrumbs navigation](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/vUPfu5uo7Nn5MPR2f1Pm/functional-documentation/ux-ui/common-components/breadcrumbs) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/vUPfu5uo7Nn5MPR2f1Pm/functional-documentation/ux-ui/common-components/heading-of-the-page) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

### Prestashop Metrics block (in some Prestashop versions)

It is a marketing-based description, offering useful link. The text is:\
\
_A new interface for your data_\
_Gather all your data in one place._\
_Follow the evolution of your business at a glance._\
_Control and optimize your KPIs with 100% reliable data._

* **Start the setup now** - A CTA button, leading to PrestaShop Metrics page.

### List of statistic topics

This UI selective component is displayed as [List Group UI element](https://build.prestashop.com/prestashop-ui-kit/?path=/story/list-group--list-group).

* [Available quantities](stats.md#available-quantities)
* [Best categories](stats.md#best-categories)
* ****[Best customers](stats.md#best-customers)
* [Best suppliers](stats.md#best-suppliers)
* [Best vouchers](stats.md#best-vouchers)
* [Best-selling products](stats.md#best-selling-products)
* [Carrier distribution](stats.md#carrier-distribution)
* [Catalog evaluation](stats.md#catalog-evaluation)
* [Catalog statistics](stats.md#catalog-statistics)
* [Customer accounts](stats.md#customer-accounts)
* [Newsletter](stats.md#newsletter)
* [Pages not found](stats.md#pages-not-found)
* [Product details](stats.md#product-details)
* [Registered customer information](stats.md#registered-customer-information)
* ****[Sales and orders](stats.md#sales-and-orders)
* [Shop search](stats.md#shop-search)
* [Stats Dashboard](stats.md#stats-dashboard) (by default, displayed first)

### Empty statistics

If there are no entries collected in table, there will be a single word _Empty_ displayed.

### Available quantities

The table header is named _Evaluation of available quantities for sale._&#x20;

There is a Category dropdown component, with all the webshop Category values listed. This element is from [Dropdowns Basics UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics). Once the value from the dropdown is changed, the page reloads and shows the arranged values in the table.

#### Table content

There are the following column values in the table: **ID**, **Ref.**, **Item**, **Available quantity for sale**, **Price\***, **Value**.

The table is compiled from [Hoverable Table UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable).

* **ID** - numeric value of the category ID.
* **Ref.** - reference value of the quantity entry.
* **Item** - name of the product quantity entry.
* **Available quantity for sale** - shows the available quantity for selling the product.
* **Price\*** - has additional reference meaning at the bottom of the table - _This section corresponds to the default wholesale price according to the default supplier for the product. An average price is used when the product has attributes._&#x20;
* **Value** - shows the value of the product quantity entry.
* **Total quantities** - shows the total sum of the quantity entries at the bottom of the table.
* **Average price** - calculates the total entries of average prices and shows the average price.
* **Total value** - shows the total sum of the value.

### Best categories

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Best categories._

There are the following column values in the table: **Name**, **Total Quantity Sold**, **Total Price**, **Total Margin**, and **Total Viewed**.

The table is compiled from [Hoverable Table UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable).

* **Name** - shows the navigation path of the category, by the following scheme - {folder icon} {Root category name, for e.g. Root} > {Prestashop category name}.
* **Total Quantity Sold** - numeric value, how many items were sold.
* **Total Price** - shows the total price of the entry, in currency output.
* **Total Margin** - shows the total margin of the entry, in currency output.
* **Total viewed** - shows the total categories views number.
* **Displaying {first number} of {the last numeric value of the list}** - indicator, that shows all the entries in the table.
* **CSV Export CTA button (**[**Buttons with Icons UI style**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)**)** - Exports the list of entries in downloadable CSV format.
* **Checkbox** - once marked, the page will reaload and the UI will show the final level categories only, not child included. There is a small text description near the checkbox _Display final level categories only (that have no child categories)._

### Best customers

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Best customers._

**Yellow guide alert box -** There is a word _Guide_ and the following yellow-style notification box, with the exclamation mark icon ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)). The content is:

_Develop clients' loyalty_\
_Keeping a client can be more profitable than gaining a new one. That is one of the many reasons it is necessary to cultivate customer loyalty. Word of mouth is also a means for getting new, satisfied clients. A dissatisfied customer can hurt your e-reputation and obstruct future sales goals. In order to achieve this goal, you can organize:_\
_- Punctual operations: commercial rewards (personalized special offers, product or service offered), non commercial rewards (priority handling of an order or a product), pecuniary rewards (bonds, discount coupons, payback)._\
_- Sustainable operations: loyalty points or cards, which not only justify communication between merchant and client, but also offer advantages to clients (private offers, discounts)._\
_These operations encourage clients to buy products and visit your online store more regularly._

There are the following column values in the table: **Last Name**, **First Name**, **Email**, **Visits**, **Valid orders** and **Money spent {currency initials}**.

The table is compiled from [Hoverable Table UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable).

* **Last Name** - displays the last name of the customer.
* **First Name** - displays the first name of the customer.
* **Email** - displays the email of the customer.
* **Visits** - counts the visits that customer has made.
* **Valid orders** - valids the orders that customer has made.
* **Money spent {currency initials}** - shows the total amount of money the customer has spent.
* **Displaying {first number} of {the last numeric value of the list}** - indicator, that shows all the entries in the table.
* **CSV Export CTA button (**[**Buttons with Icons UI style**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)**)** - Exports the list of entries in downloadable CSV format.

### Best suppliers

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Best suppliers._

The table is compiled from [Hoverable Table UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable).

* **Name** - shows the name of the supplier.
* **First Name** - numeric value, how many items were sold.
* **Email** - shows the total price of the entry, in currency output.
* **Visits** - shows the total margin of the entry, in currency output.
* **Valid orders** - shows the total categories views number.
* **Money spent {currency initials}** - indicator, that shows all the entries in the table.
* **Displaying {first number} of {the last numeric value of the list}** - indicator, that shows all the entries in the table.
* **CSV Export CTA button (**[**Buttons with Icons UI style**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)**)** - Exports the list of entries in downloadable CSV format.

### Best vouchers

First part of the UI - [Filtering Components in Stats](broken-reference).

#### Table content

The table header is named _Best vouchers._

There are the following column values in the table: **Code**, **Name**, **Sales**, and **Total used**.

The table is compiled from [Hoverable Table UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable).

* **Code** - shows the unique code, created by user.
* **Name** - shows the unique name of the voucher.
* **Sales** - shows the total price of sales made using the voucher.
* **Total used** - shows the total number of using the voucher.
* **Displaying {first number} of {the last numeric value of the list}** - indicator, that shows all the entries in the table.
* **CSV Export CTA button (**[**Buttons with Icons UI style**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)**)** - Exports the list of entries in downloadable CSV format.

### Best-selling products

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Best-selling products._

There are the following column values in the table: **Reference**, **Name**, **Quantity sold**, **Price sold**, **Sales**, **Quantity sold in a day**, **Page views**, **Available quantity for sale** and **Active**.

The table is compiled from [Hoverable Table UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable).

* **Reference** - shows the reference of the product**.**
* **Name** - shows the name of the product.
* **Quantity sold** - shows the total amount of products sold.
* **Price sold** - shows the price the product was sold.
* **Sales** - shows the amount of sales that was done with the product.
* **Quantity sold in a day** - shows how many items were sold in 24h hours.
* **Page views** - shows how many views were made, referring to the product.
* **Available quantity for sale** - shows the available number of,&#x20;
* **Active** - shows if the product is active or not.
* **Displaying {first number} of {the last numeric value of the list}** - indicator, that shows all the entries in the table.
* **CSV Export CTA button (**[**Buttons with Icons UI style**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)**)** - Exports the list of entries in downloadable CSV format.

### Carrier distribution

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Carrier distribution._

The table has a dropdown component ([Dropdowns Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics)) and **Filter** CTA button ([Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). The dropdown will list all the available **Order Statuses** in the webshop**.** After selecting the status, clicking Filter - UI should return the pie-style diagram chart with the information, once the chart is hovered. By default, the dropdown is set to value All.

**Alert info box** - there is a blue alert info box with a question sign. It indicates the text - _This graph represents the carrier distribution for your orders. You can also narrow the focus of the graph to display distribution for a particular order status._

**Pie chart** - a UI component with multicolor parts. These parts are divided to the biggest or smallest parts, depending on the number amount of orders. Once the part of the chart is hovered, it will highlight and show the context table divided into two indication parts - the upper one will show the **Carrier** name and the lower one - the amount of **Orders** that were made.

**CSV Export CTA button** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

### Catalog evaluation

First part of the UI - [Filtering Components in Stats](broken-reference).

The table header is named _Catalog evaluation._

This section helps administrator to check, which **Catalog** properties are working good, and which are not. First, the table content has components, that is, like a guiding notifications block. The block is divided by **Not enough** and **Alright** status inputs, that define the requirements of the Catalog evaluation. Both input sides have the same criteria, that can be defined by administrator individually, so that the Catalog list can be valuated with red or green circle dots, as indicators. The inputs are styled by [Input group UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--input-group).

#### Criteria inputs

**Descriptions** - Less than {chars defined, by default it will be 100}, explanation - _chars (without HTML)_.

**Images** - Less than {chars defined, by default it will be 1}, explanation - _images_.

**Sales** - Less than {chars defined, by default it will be 1}, explanation - _orders / month_.

**Available quantity for sale** - Less than {chars defined, by default it will be 1}, explanation - _items_.

Both **Not enough** and **Alright** inputs are the same opposite.

**Save CTA** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). Saves the defined criteria configuration.

#### Table content

The table content starts with arrangement dropdown - **Order by**. The dropdown belongs to [Dropdown Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics). The values are **ID**, **Name**, **Sales**. By default, the value is set to ID.

The table column **headers** and **footers** are:

**ID** - unique numeric value of the entry.

**Item** - item name.

**Active** - circle indicator (red, green) and the numeric value nearby.

**Desc. {language initial letters}** - description criteria.

**Images** - circle indicator (red, green) and the numeric value nearby.

**Sales** - circle indicator (red, green) and the numeric value nearby.

**Available quantity for sale** - numeric indicator.

**Global** - circle indicator (red, green).

### Catalog statistics

The table header is named _Catalog statistics._&#x20;

#### Table content

There is a Category dropdown component, with all the webshop Category values listed. This element is from [Dropdowns Basics UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics). Once the value from the dropdown is changed, the page reloads and shows the arranged values in the table.

The table is created by [Basic Table UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--basic) and the results of the each metric is stored in blue tag-style values on the right side of the table.

There are the following metrics:

**Products available** - shows the number of available products in category.

**Average price (base price)** - calculates the average (base) price in category.

**Product pages viewed** - calculates total number of product pages viewed in category.

**Products bought** - calculates total number of product bought in category.

**Average number of page visits** - calculates average number of page visits in category.

**Average number of purchases** - calculates average number of purchases in category.

**Images available** - calculates, how many images are available in category.

**Average number of images** - calculates the average amount of images in category.

**Products never viewed** - calculates, how many products were not viewed.

**Products never purchased** - calculates, how many products were not viewed.

**Conversion rate** with the description - _Defines the average conversion rate for the product page. It is possible to purchase a product without viewing the product page, so this rate can be greater than 1_.

There is another metric about _Products never purchased._ This table is created by [Hoverable Table UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable). There are the following table headers:

**ID** - shows the product ID.

**Name** - shows the product name.

**Edit/View** - a button named _Edit_ ([Buttons with Icons UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). Edit redirects to the product editing page, and clicking the dropdown triangle, there is a _View_ option, to see the product from Front-Office product page.

### Customer accounts

First part of the UI - [Filtering Components in Stats](broken-reference).

#### Table content

The table header is named _Carrier distribution._

**Alert info box** - ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) there is a blue alert info box with a question sign. It indicates the text - _Number of visitors who stopped at the registering step: {number and percentage}_ \
_Number of visitors who placed an order directly after registration: {number and percentage}_ \
_Total customer accounts: {number}._

**Guide** - small description word.

**Yellow guide alert box** - there is a yellow warning alert box with an exclamation mark ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)). The text is:&#x20;

_Number of customer accounts created. The total number of accounts created is not in itself important information. However, it is beneficial to analyze the number created over time. This will indicate whether or not things are on the right track._&#x20;

**How to act on the registrations' evolution?** - small question.

**Yellow guide alert box** - there is a yellow warning alert box with an exclamation mark ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)). The text is:&#x20;

_If you let your shop run without changing anything, the number of customer registrations should stay stable or show a slight decline. A significant increase or decrease in customer registration shows that there has probably been a change to your shop. With that in mind, we suggest that you identify the cause, correct the issue and get back in the business of making money!_\
_Here is a summary of what may affect the creation of customer accounts:_

_An advertising campaign can attract an increased number of visitors to your online store. This will likely be followed by an increase in customer accounts and profit margins, which will depend on customer "quality." Well-targeted advertising is typically more effective than large-scale advertising... and it's cheaper too!_

_Specials, sales, promotions and/or contests typically demand a shoppers' attentions. Offering such things will not only keep your business lively, it will also increase traffic, build customer loyalty and genuinely change your current e-commerce philosophy._

_Design and user-friendliness are more important than ever in the world of online sales. An ill-chosen or hard-to-follow graphical theme can keep shoppers at bay. This means that you should aspire to find the right balance between beauty and functionality for your online store._

&#x20;__ **X and Y statistics chart** _-_ shows the number of customer accounts created. The horizontal **X** graph shows the time numeration, and the vertical **Y** - the numeric amount of accounts being generated. The agenda near the chart is also included - small colored circle icon with text description _Number of customer accounts created._

**CSV Export CTA button** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

### Newsletter

First part of the UI - [Filtering Components in Stats](broken-reference).

#### Table content

The table header is named _Newsletter._

**X and Y statistics chart** _-_ shows the number of newsletters created. The horizontal **X** graph shows the time numeration, and the vertical **Y** - the numeric amount of newsletters being generated. The agenda near the chart is also included - small colored circle icons with text description:

_Number of customer accounts created._

_customers_

_Visitors_

As well, there is additional agenta with the numbering:

* _Customer registrations: {numeric value}_
* _Visitor registrations: {numeric value}_
* _Both: {numeric value}_

**CSV Export CTA button** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

### Pages not found

First part of the UI - [Filtering Components in Stats](broken-reference).

#### Table content

The table header is named _Pages not found._

**Yellow guide alert box -** There is a word _Guide_ and the following yellow-style notification box, with the exclamation mark icon ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)). The content is:

_404 errors_

_A 404 error is an HTTP error code which means that the file requested by the user cannot be found. In your case it means that one of your visitors entered a wrong URL in the address bar, or that you or another website has a dead link. When possible, the referrer is shown so you can find the page/site which contains the dead link. If not, it generally means that it is a direct access, so someone may have bookmarked a link which doesn't exist anymore._&#x20;

_How to catch these errors?_&#x20;

_If your webhost supports .htaccess files, you can create one in the root directory of PrestaShop and insert the following line inside: "ErrorDocument 404 {host\_name\_URL}/404.php"._\
_A user requesting a page which doesn't exist will be redirected to the following page: {host\_name\_URL}/404.php. This module logs access to this page._

The next following component is from [Hoverable Table UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable). There are clickable URL links listed. Those page URLs are captured in the table with the following table headers:

**Page** - the accessed URL of the 404 page.

**Referrer** - shows the URL, from where the page was redirected.

**Counter** - counts the number of 404 visits executed.

There is ability to delete the URL logs by clicking one of those 2 CTA buttons:

**Empty ALL "pages not found" notices for this period** - deletes the entries for the selected period of time, using the date picker in the top.

**Empty ALL "pages not found" notices** - deletes all of the entries of the all time.

### Product details

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Product details._

**Yellow guide alert box -** There is a word _Guide_ and the following yellow-style notification box, with the exclamation mark icon ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)). The content is:

_Number of purchases compared to number of views_\
_After choosing a category and selecting a product, informational graphs will appear._\
_If you notice that a product is often purchased but viewed infrequently, you should display it more prominently in your Front Office._\
_On the other hand, if a product has many views but is not often purchased, we advise you to check or modify this product's information, description and photography again, see if you can find something better._

There is a **Category dropdown (**[**Dropdown Basics UI Kit**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics)**)**, named Choose a category. Clicking the dropdown, allows to select one of the Category values available in webshop.

**Products available** - the headline of the table section.

The next following table component is from [Hoverable Table UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable). The table has the following headers:

**Reference** - displays the product reference.

**Name** - displays the product name, and the name is clickable link.

**Available quantity for sale** - displays the available quantity of the product.

**CSV Export CTA button** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

### Registered customer information

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Registered customer information._

**Yellow guide alert box -** There is a word _Guide_ and the following yellow-style notification box, with the exclamation mark icon ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)). The content is:

_Target your audience_\
_In order for each message to have an impact, you need to know who it is being addressed to._\
_Defining your target audience is essential when choosing the right tools to win them over._\
_It is best to limit an action to a group -- or to groups -- of clients._\
_Storing registered customer information allows you to accurately define customer profiles so you can adapt your special deals and promotions._\
_You can increase your sales by:_\
_Launching targeted advertisement campaigns._\
_Contacting a group of clients by email or newsletter._

Down below, there are pie-style charts, with different distribution data metrics, according to the selected time range. All of the distribution sections has **CSV Export CTA buttons** - buttons from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

The distributions are the following (descriptions included):

**Gender distribution** - allows you to determine the percentage of men and women shoppers on your store.

**Age ranges** - allow you to better understand target demographics.

**Country distribution** - allows you to analyze which part of the World your customers are shopping from.

**Currency range** - allows you to determine which currency your customers are using.

**Language distribution** - allows you to analyze the browsing language used by your customers.

Hovering the pie chart, displays the context blocks, with the statistics data.

### Shop search

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Shop search._&#x20;

The following next element is a pie-style chart, with the Search statistics data. Once hovered - the context blocks are displayed, with the statistical data, referring the time.

**CSV Export CTA button** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

The next following table component is from [Hoverable Table UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable). The table has the following headers:

**Keywords** - displays the keywords that were typed in searching.

**Occurrences** - displays how many times the keyword was typed.

**Results** - shows how many results were displayed.

### Sales and orders

First part of the UI - [Filtering Components in Stats](broken-reference).

#### Table content

The table header is named _Sales and orders._

**Yellow guide alert box -** There is a word _Guide_ and the following yellow-style notification box, with the exclamation mark icon ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)). The content is:

_About order statuses_\
_In your back office, you can modify the following order statuses: Awaiting Check Payment, Payment Accepted, Preparation in Progress, Shipping, Delivered, Canceled, Refund, Payment Error, Out of Stock, and Awaiting Bank Wire Payment. These order statuses cannot be removed from the back office; however you have the option to add more._

**Blue info alert box -** There is a blue notification message ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) with the defined text:

_The following graphs represent the evolution of your shop's orders and sales turnover for a selected period._\
_You should often consult this screen, as it allows you to quickly monitor your shop's sustainability. It also allows you to monitor multiple time periods._\
_You should often consult this screen, as it allows you to quickly monitor your shop's sustainability. It also allows you to monitor multiple time periods._

There is a _Countries_ dropdown component, with all the available Country values listed. This element is from [Dropdowns Basics UI](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics). Once the value from the Country is selected and the Filter button ([Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) clicked, the page reloads and shows the filtered values in the table. By default  - the table shows **All Countries** content.

There are **two X/Y** graphical charts. The first one reflects the **Orders placed** and **Products bought**. The placeholders can be selected or deselected once clicked on the circle icons agenda - this will show the statistics. There are placeholders as well:

* _Orders placed: {numeric value}_
* _Products bought: {numeric value}_

Once the chart points are hovered, the context box will pop-up

**CSV Export CTA button** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

The second chart reflects the **Sales currency** and the currency code.&#x20;

Then there is **Sales** count in numeric value, and **CSV Export CTA button** - button from [Buttons with Icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). It exports the entries data in CSV format.&#x20;

**Blue info alert box -** There is a blue notification message ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) with the defined text:

_You can view the distribution of order statuses below._

The last chart is pie-style chart, with the Orders distribution partitioning. The chart is divided into separate percentage output. Once the part is hovered, the context box will appear with the statistic data - Order status name and the value of the Order status name.

### Stats Dashboard

First part of the UI - [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md).

#### Table content

The table header is named _Stats Dashboard._&#x20;

There is a blue notification box, showing the text _The listed amounts do not include tax_ ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)).

The table has a dropdown component ([Dropdowns Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics)) named **Time frame**, with values - **Daily, Weekly, Monthly and Yearly.**

All the next following tables components are from [Hoverable Table UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable). There are the following table headers (showed both sides - at the top and bottom of the table section):

**First header** - shows the time range for the output statistical data.&#x20;

**Visits** - shows the total visits that were hit.

**Registrations** - show the tatal amount of registered users.

**Placed orders** - shows the total amount of orders placed.

**Bought items** - shows the total amount of items bought.

**Percentage of registrations** - shows the percantage of the registrations, that were made from all visists.

**Percentage or orders** - shows the percantage of the orders, that were made from all visits.

**Revenue** - displays the full revenue amount with currency.



Other table component is named _Conversion_.

This component is displayed as a conversion workflow diagram. First, the workflow takes at least 90 visitors, as a metric start. Then it shows the percentage that some visitors generate **Accounts** and **Carts**, so that those elements become as **Full carts**. Then the **Carts** become as **Orders**. And registered visitors generate **Orders** as well as **Guest visitors** generate **Orders** too. The main aspect here is the percentage outcome, that defines the effectiveness boost.

**Blue info alert box -** There is a blue notification message ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) with the defined text:

_A simple statistical calculation lets you know the monetary value of your visitors:_\
_On average, each visitor places an order for this amount: **{webshop calculates the average value with currency}.**_\
_****On average, each registered visitor places an order for this amount: **{webshop calculates the average value with currency}**._

__

There is a section named _Payment distribution_.

**Blue info alert box -** There is a blue notification message ([Alerts Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) with the defined text:

_The amounts include taxes, so you can get an estimation of the commission due to the payment method._

The next table has a dropdown component ([Dropdowns Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics)) named **Zone**, with values - **Africa, Asia, Central America/Antilla, Europe, Europe (non-EU), North America, Oceania, South America**. As well, there is a default state **-- No filter --**.

There are the following table headers in the Payment distribution table:

**Module** - shows the module name.&#x20;

**Orders** - shows the total orders that were made.

**Sales** - shows the tatal amount of sum generated, with certain currency.

**Average cart value** - shows the average cart amount made, with certain currency.



There is a next section named _Category distribution_.

The next table has a dropdown component ([Dropdowns Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics)) named **Zone**, with values - **Africa, Asia, Central America/Antilla, Europe, Europe (non-EU), North America, Oceania, South America**. As well, there is a default state **-- No filter --**.

There are the following table headers in the Category distribution table:

**Category** - shows the category name.&#x20;

**Products sold** - shows the total products that were sold.

**Sales** - shows the tatal amount of sum generated, with certain currency.

**Percentage of products sold** - shows the average percentage of products sold, with certain currency.

**Percentage of sales** - shows the average percentage of sales, with certain currency.

**Average price** - shows the average price, with certain currency.&#x20;



There is a next section named _Language distribution_.

There are the following table headers in the Language distribution table:

**Language** - shows the language name as 2 language initial letters.&#x20;

**Sales** - shows the tatal amount of sum generated, referring to the country, with certain currency.&#x20;

**Percentage** - shows the percentage of products sold, with certain currency. There are the progress indicators next to the column. The indicators can be green and pointed up, meaning, that the percentage is ascending. And red arrow pointed down - if percentage is descending.

**Growth** - shows the growth in plus or minus percentage metrics.



There is a next section named _Zone distribution_.

There are the following table headers in the Zone distribution table:

**Zone** - shows the zone name.&#x20;

**Orders** - shows total orders made in zone.&#x20;

**Sales** - shows the percentage of products sold, with certain currency.&#x20;

**Percentage of sales** - shows the part of zone sales in percentage metrics.



There is a next section named _Currency distribution_.

The next table has a dropdown component ([Dropdowns Basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics)) named **Zone**, with values - **Africa, Asia, Central America/Antilla, Europe, Europe (non-EU), North America, Oceania, South America**. As well, there is a default state **-- No filter --**.

There are the following table headers in the Currency distribution table:

**Currency** - shows the currency name.&#x20;

**Orders** - shows total orders made in zone.&#x20;

**Sales (converted)** - shows the total of products converted, with certain currency.&#x20;

**Percentage of orders** - shows the part of zone orders in percentage metrics.

**Percentage of sales** - shows the part of zone sales in percentage metrics.



There is a last section named _Attribute distribution_.

There are the following table headers in the Attribute distribution table:

**Group** - shows the group name.&#x20;

**Attribute** - shows the attribute name.&#x20;

**Quantity of products sold** - shows the quantity of products sold referring to the attributes.&#x20;

## Error messages

Once the Date format is filled incorrectly, in the [Filtering Components in Stats](../../common-components/filtering-components-in-stats.md) UI component, the error message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) is prompted in the front-end:

_The specified date is invalid._

## Multistoring functionality&#x20;

[Multistores dependent](../../common-components/multistores-dependent.md) page.
