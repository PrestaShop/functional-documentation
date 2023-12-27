# SEO & URLs

## Description

This page is responsible for the website's URL and SEO settings management.

<figure><img src="../../../../../../.gitbook/assets/image (14).png" alt="SEO &#x26; URLs UI"><figcaption><p>SEO &#x26; URLs User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/trafic-and-seo/seo-and-urls.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)
* [Save button](../../../../common-components/save-button.md)
* Settings wheel (todo link)
* &#x20;[Pagination with input fields](../../../../common-components/pagination-with-input.md)

## Tabs

There are 2 [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills) tabs in the UI:

* **SEO & URLs** (active)
* **Search Engines**

## Add a new page CTA button

[Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics) component. Clicking the button redirects to the Adding a new SEO & URL page.

## Improve your SEO commercial box

After the first visit of the page, there will be a popup with the suggestion to improve the SEO of the webshop. The popup contains:

* **Logo**
* **X** - to close the popup permanently.
* **Improve your SEO** - a title.
* **Edit information about your pages to gain visibility and therefore reach more visitors. We advise you to start with the index page, it stands for your homepage.** - description.
* **Learn more** - CTA button ([Buttons Outline UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) for additional information.

## The page list

There is an alert notification ([Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) text at the beginning of the section:

_You can only display the page list in a shop context._

When there is a certain Multistore selected only, there will be a list showed. If this page is in All Shops context, there will be no list showed.

If a certain shop is selected, there will be an alert notification ([Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) text also:

_To apply specific settings to a store or a group of stores, select the parameter to modify, make your changes and save._

## SEO & URLs section

The section starts with a title _SEO & URLs_ and a total sum of links in the brackets.

### Sorting the table

Sorting the table uses the [Sorting rules](../../../../common-components/sorting-rules.md) functionality. The sorting headers of the table are:

* **ID**
* **Page**
* **Page title**
* **Friendly URL**

### Table filtering

Table uses standard input fields for filtering. The filtering can be made in these inputs:

* **ID**
* **Page**
* **Page title**
* **Friendly URL**

After the filtering has been inputted, CTA button ([Buttons with Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) **Search** can be executed for the search results.

### Unsorted and unfiltered column

**Actions** column can not be filtered or sorted.

### Table content

By the default installation of the webshop, there are 35 entries already saved to the SEO & URL list:

<table><thead><tr><th width="77.33333333333331">ID</th><th width="172">Page</th><th width="263">Page title</th><th>Friendly url</th></tr></thead><tbody><tr><td>1</td><td>pagenotfound</td><td>404 error</td><td>page-not-found</td></tr><tr><td>2</td><td>best-sales</td><td>Best sales</td><td>best-sales</td></tr><tr><td>3</td><td>contact</td><td>Contact us</td><td>contact-us</td></tr><tr><td>4 </td><td>index</td><td>-</td><td>-</td></tr><tr><td>5</td><td>manufacturer</td><td>Brands</td><td>brands</td></tr><tr><td>6</td><td>new-products</td><td>New products</td><td>new-products</td></tr><tr><td>7</td><td>password</td><td>Forgot your password</td><td>password-recovery</td></tr><tr><td>8</td><td>prices-drop</td><td>Prices drop</td><td>prices-drop</td></tr><tr><td>9</td><td>sitemap</td><td>Sitemap</td><td>sitemap</td></tr><tr><td>10</td><td>supplier</td><td>Suppliers</td><td>supplier</td></tr><tr><td>11</td><td>address</td><td>Address</td><td>address</td></tr><tr><td>12</td><td>addresses</td><td>Addresses</td><td>addresses</td></tr><tr><td>13</td><td>authentication</td><td>Login</td><td>login</td></tr><tr><td>14</td><td>registration</td><td>Registration</td><td>registration</td></tr><tr><td>15</td><td>cart</td><td>Cart</td><td>cart</td></tr><tr><td>16</td><td>discount</td><td>Discount</td><td>discount</td></tr><tr><td>17</td><td>history</td><td>Order history</td><td>order-history</td></tr><tr><td>18</td><td>identity</td><td>Identity</td><td>identity</td></tr><tr><td>19</td><td>my-account</td><td>My account</td><td>my-account</td></tr><tr><td>20</td><td>order-follow</td><td>Order follow</td><td>order-follow</td></tr><tr><td>21</td><td>order-slip</td><td>Credit slip</td><td>credit-slip</td></tr><tr><td>22</td><td>order</td><td>Order</td><td>order</td></tr><tr><td>23</td><td>search</td><td>Search</td><td>search</td></tr><tr><td>24</td><td>stores</td><td>Stores</td><td>stores</td></tr><tr><td>25</td><td>guest-tracking</td><td>Guest tracking</td><td>guest-tracking</td></tr><tr><td>26</td><td>order-confirmation</td><td>Order confirmation</td><td>order-confirmation</td></tr><tr><td>35</td><td>module-ps_shoppingcart-ajax</td><td>-</td><td>-</td></tr><tr><td>36</td><td>module-ps_emailsubscription-verification</td><td>-</td><td>-</td></tr><tr><td>37</td><td>module-ps_emailsubscription-subscription</td><td>-</td><td>-</td></tr><tr><td>38</td><td>module-ps_checkpayment-payment</td><td>-</td><td>-</td></tr><tr><td>39</td><td>module-ps_checkpayment-validation</td><td>-</td><td>-</td></tr><tr><td>40</td><td>module-ps_cashondelivery-validation</td><td>-</td><td>-</td></tr><tr><td>41</td><td>module-ps_emailalerts-account</td><td>-</td><td>-</td></tr><tr><td>42</td><td>module-ps_wirepayment-payment</td><td>-</td><td>-</td></tr><tr><td>43</td><td>module-ps_wirepayment-validation</td><td>-</td><td>-</td></tr></tbody></table>

## Set up URLs section

The block starts with the gear-style icon and a title, _Set up URLs_. If this page is set as specific single Multistore, then these particular options will be shown. Each option will have the ability to check or uncheck the checkbox for each row. By default, all the checkboxes on the left will be unchecked.

### Friendly URL

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable this option only if your server allows URL rewriting (recommended).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#friendly-url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Accented URL

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable this option if you want to allow accented characters in your friendly URLs. You should only activate this option if you are using non-Latin characters; for all the Latin charsets, your SEO will be better without this option.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#accented-url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Redirect to the canonical URL

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>302 Moved Temporarily (recommended while setting up your store)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#redirect-to-the-canonical-url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Disable Apache's MultiViews option

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable this option only if you have problems with URL rewriting.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#disable-apaches-multiviews-option-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Disable Apache's mod\_security module

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Some of PrestaShop's features might not work correctly with a specific configuration of Apache's mod_security module. We recommend to turn it off.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#disable-apaches-mod_security-module-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Set shop URL section

The block starts with the gear-style icon and a title, _Set shop URLs_. Next there is an [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) notification, the text is:

_The multistore option is enabled. If you want to change the URL of your shop, you must go to the "Multistore" page under the "Advanced Parameters" menu._

## Schema of URLs section

The block starts with the gear-style icon and a title, _Schema of URLs_. Next, there is a [Buttons Toolbar UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar) component, when hovered, it will display the following text:

_This section enables you to change the default pattern of your links. In order to use this functionality, PrestaShop's "Friendly URL" option must be enabled, and Apache's URL rewriting module (mod\_rewrite) must be activated on your web server.There are several available keywords for each route listed below; note that keywords with \* are required! To add a keyword in your URL, use the {keyword} syntax. If the keyword is not empty, you can add text before or after the keyword with syntax {prepend:keyword:append}. For example {-hey-:meta\_title} will add "-hey-my-title" in the URL if the meta title is set._

Next there is an [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) notification, the text is:

_Before making any changes to the default pattern of your URLs, make sure to meet the following requirements:_

* _The Friendly URL feature must be enabled_
* _URL rewriting must be activated on your web server_
* _All mandatory keywords (\*) must be included in the route_

_You should also comply with the syntax:_

* _Keywords must be in braces {keyword}_
* _All keywords must be separated_
* _As long as a keyword has an associated value, you can use the syntax {prepend:keyword:append} to add text before and after it._

### Route to products

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden single numbers</td><td align="center"><p>Keyword "{id}" required for route "product_rule" (rule: "123456789")</p><p>Keyword "{id_product_attribute}" required for route "product_rule" (rule: "123456789")</p><p>Keyword "{rewrite}" required for route "product_rule" (rule: "123456789")</p></td><td></td></tr><tr><td>Default value</td><td>{category:/}{id}{-:id_product_attribute}-{rewrite}{-:ean13}.html</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Keywords: id*, id_product_attribute*, rewrite*, ean13, category, categories, reference, meta_keywords, meta_title, manufacturer, supplier, price, tags</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#route-to-products-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Route to category

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden single numbers</td><td align="center">Keyword "{id}" required for route "category_rule" (rule: "123456789")</td><td></td></tr><tr><td>Default value</td><td>{category:/}{id}{-:id_product_attribute}-{rewrite}{-:ean13}.html</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Keywords: id*, rewrite, meta_keywords, meta_title</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#route-to-category-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Route to supplier

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden single numbers</td><td align="center">Keyword "{id}" required for route "supplier_rule" (rule: "123456789")</td><td></td></tr><tr><td>Default value</td><td>supplier/{id}-{rewrite}</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Keywords: id*, rewrite, meta_keywords, meta_title</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#route-to-supplier-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Route to brand

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden single numbers</td><td align="center">Keyword "{id}" required for route "manufacturer_rule" (rule: "1234567890")</td><td></td></tr><tr><td>Default value</td><td>brand/{id}-{rewrite}</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Keywords: id*, rewrite, meta_keywords, meta_title</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#route-to-brand-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Route to page

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden single numbers</td><td align="center">Keyword "{id}" required for route "cms_rule" (rule: "123456789")</td><td></td></tr><tr><td>Default value</td><td>content/{id}-{rewrite}</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Keywords: id*, rewrite, meta_keywords, meta_title</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#route-to-page-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Route to page category

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden single numbers</td><td align="center">Keyword "{id}" required for route "cms_rule" (rule: "123456789")</td><td></td></tr><tr><td>Default value</td><td>content/category/{id}-{rewrite}</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Keywords: id*, rewrite, meta_keywords, meta_title</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#route-to-page-category-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Route to modules

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Fill in this field.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden single numbers</td><td align="center"><p>Keyword "{id}" required for route "cms_category_rule" (rule: "module/{module}{/:controller}")</p><p>Keyword "{module}" required for route "module" (rule: "0123456789")</p><p>Keyword "{controller}" required for route "module" (rule: "0123456789")</p></td><td></td></tr><tr><td>Default value</td><td>module/{module}{/:controller}</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Keywords: module*, controller*</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#route-to-modules-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## SEO Options section

The block starts with the gear-style icon and a title, _SEO options_.&#x20;

### Display attributes in the product meta title

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable this option if you want to display your product's attributes in its meta title.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="seo-and-urls.md#display-attributes-in-the-product-meta-title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Robots file generation section

The block starts with the gear-style icon and a title, _Robots file generation_. Next there is an [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) notification, the text is:

_The multistore option is enabled. If you want to change the URL of your shop, you must go to the "Multistore" page under the "Advanced Parameters" menu._

### Generate robots.txt file

[Buttons Basic UI Kit ](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)component. Once clicked, there will be a robots.txt file generated.&#x20;

## Behavior descriptions

### Friendly URL behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Friendly URLs, also known as "pretty" or "clean" URLs, are web addresses that are easy for humans to read and understand. They typically include descriptive words that provide an indication of what the page contains, rather than being a random combination of letters and numbers.

In PrestaShop, friendly URLs are created automatically based on the name of the product or category. For example, if you have a product called "Blue T-Shirt", the friendly URL might be something like "yourstore.com/blue-t-shirt".

### Accented URL behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Accented URL behavior in PrestaShop refers to the ability of the platform to support URLs that contain accented characters, such as é, è, ê, etc.

### Redirect to the canonical URL behavior

[Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics) component. "Redirect to the canonical URL" behavior in PrestaShop refers to the platform's ability to automatically redirect users to the preferred or canonical URL for a particular page, in order to avoid duplicate content issues.

### Disable Apache's MultiViews option behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. The MultiViews option in Apache allows the server to automatically match a URL to a file with the same name, even if the URL doesn't include the file extension. For example, if a user requests the URL "example.com/products", and there is a file called "products.html" in the root directory of the website, the server will return the contents of the "products.html" file.

### Disable Apache's mod\_security module behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Mod\_security is a module that provides web application firewall functionality for the Apache web server. It can be used to detect and prevent a wide range of attacks, including SQL injection, cross-site scripting (XSS), and other web-based attacks.

### Route to products behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. By default, PrestaShop creates URLs for products and categories that include a combination of numbers and symbols, such as "yourstore.com/index.php?id\_product=123\&controller=product". While these URLs work, they are not particularly user-friendly and can make it more difficult for search engines to properly index your site.

### Route to category behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. By default, PrestaShop creates URLs for categories that include a combination of numbers and symbols, such as "yourstore.com/index.php?id\_category=123\&controller=category". While these URLs work, they are not particularly user-friendly and can make it more difficult for search engines to properly index your site.

### Route to supplier behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. By creating search engine friendly URLs for product categories, the "Route to category" feature in PrestaShop helps improve the visibility and ranking of your online store in search engines, which can ultimately drive more traffic and sales to your website.

### Route to brand behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. For example, a brand with the name "Nike" might have a URL like "yourstore.com/nike". This URL includes keywords that describe the brand and make it easier for users to find via search engines.

### Route to page behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. To address this issue, PrestaShop provides a URL rewriting system that creates search engine friendly URLs for custom pages. These URLs typically include keywords and phrases that describe the content of the page, making them easier for users to read and understand, as well as improving search engine rankings.

### Route to page category behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. "Route to page category" in PrestaShop refers to the platform's URL rewriting system, which creates search engine friendly URLs for custom page categories.

### Route to modules behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. "Route to modules" in PrestaShop refers to the platform's URL rewriting system, which creates search engine friendly URLs for modules.

### Display attributes in the product meta title behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. In Prestashop, the "Display attributes in the product meta title" option allows you to include product attributes in the meta title of a product page.

For example, if you have a product called "Women's T-shirt" with the attributes "Color" and "Size," enabling this option will automatically add these attributes to the meta title of the product page. So, if a customer selects a red T-shirt in a size small, the meta title of the product page will be "Women's T-shirt - Red, Small."

## Multistores functionality

This page is [Multistores independent](../../../../common-components/multistores-independent.md) page.
