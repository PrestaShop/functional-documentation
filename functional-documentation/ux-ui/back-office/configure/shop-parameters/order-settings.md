# Order Settings

This page gathers all the General and Gift options settings, referring to the main Order functionalities behavior.&#x20;

<figure><img src="../../../../../.gitbook/assets/image (1) (1) (2).png" alt=""><figcaption><p>Order Settings User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Save button (todo link)

## Tabs section

The active selected tab _Order settings_ is highlighted using [Navigation Tab UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/navigation--navigation-tabs).

## The main block&#x20;

### **Header of the block**&#x20;

Named **General** with the gear icon nearby.&#x20;

### Enable final summary toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Display a summary of all relevant order data (payment method, adresses, dispatch and cart) above the order button.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-settings.md#enable-final-summary-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable guest checkout toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Allow guest visitors to place an order without registering.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-settings.md#enable-guest-checkout-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Disable reordering option toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Disable the option to allow customers to reorder in one click from the order history page (required in some European countries).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-settings.md#disable-reordering-option-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Minimum purchase total required in order to validate the order input field

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Empty field.</td><td align="center">Minimum purchase total required in order to validate the order</td><td></td></tr><tr><td>Default value</td><td>Empty 0.00 numbers.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set to 0 to disable this feature.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-settings.md#minimum-purchase-total-required-in-order-to-validate-the-order-input-field-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Recalculate shipping costs after editing the order toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Automatically updates the shipping costs when you edit an order.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="order-settings.md#recalculate-shipping-costs-after-editing-the-order-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Delayed shipping toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>It allows you to delay shipping if your customers request it.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Terms of service toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Require customers to accept or decline terms of service before processing an order.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Terms and conditions dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Choose the page which contains your store's terms and conditions.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

## Components behaviors

### Save button CTA

Save button CTA. (todo link)

## Gift options block

### **Header of the block**

Named **Gift options** with the candle on cake icon nearby.&#x20;

### Offer gift wrapping toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Suggest gift-wrapping to customers.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Gift-wrapping price input field

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty 0.00 numbers.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set a price for gift wrapping.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Gift-wrapping tax dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>None value.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set a tax for gift wrapping.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Offer recycled packaging toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Suggest recycled packaging to customer.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Save button CTA

Save button CTA. (todo link)

## Behaviors descriptions

### Enable final summary toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. Enables additional summary information above the order button in the latest checkout step. _Edit_ CTA link appears for each title, allowing to edit each checkout information. Viewing from the first to the last, the following segments are:

* Title _Please check your order before payment;_
* Addresses;
* Shipping Method;
* ORDER ITEMS, UNIT PRICE, QUANTITY, TOTAL PRODUCTS;

As well, by default the cart summary contains the values in the box:

* Product image;
* Product name with the particular link to the Product page;
* Unit price value;
* Quantity value;
* Total sum value;
* Subtotal value;
* Shipping value;
* Value of total of all products in cart;
* Taxes value;

### Enable guest checkout toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. When this feature is switched on, it allows the guest users to finalize the checkout.

### Disable reordering option toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. When this feature is Disabled, there will be ability to do a reorder in once click.

### Minimum purchase total required in order to validate the order input field behavior

There is an input field ([Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group)), defining the minimum value required to validate and finalize the order in checkout. The input shows the currency symbol and the taxing status - tax included or not.&#x20;

The yellow information block will be displayed in the first step of the checkout - cart summary, above the _PROCEED TO CHECKOUT_ button. The text is:

_A minimum shopping cart total of {numeric value with currency} (tax excl.) is required to validate your order. Current cart total is {numeric value with currency} (tax excl.)._

### Recalculate shipping costs after editing the order toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. This functionality works in Order editing page. When this function is Enabled, the shipping taxes will be updated automatically in the order shipping cost block in the Order page, once the carrier is changed. And if this function is Disabled, no carrier cost changes will be visible in the Order, and the blue alert message ([Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) will appear in Edit shipping details popup, meaning that changes can be set in Order settings page:

_Please note that carrier change will not recalculate your shipping costs, if you want to change this please visit Shop Parameters > Order Settings_

### Delayed shipping toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. When this option is Enabled, the orders in Front-Office are split, with ones with the stock and others without of the stock.

### Terms of service toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. When this feature is Enabled, users have to mark the Terms and Conditions agreement checkbox in the Checkout final stage.

### Page for terms and conditions dropdown behavior

[Input with dropdown UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown) element. It allows setting a particular page, that contains Terms and conditions information.

### Offer gift wrapping toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. When this feature is Enabled, there will be an additional checkbox marking in the third step of the Checkout, with the text:

_I would like my order to be gift wrapped (additional cost of {the price with tax included or excluded}.)_

After the checkbox is marked, there will an additional text box with the helper text and Continue CTA:

_If you'd like, you can add a note to the gift:_

### Gift-wrapping price input behavior

[Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group) element. There can be a particular price added for the Gift-wrapping message, in the third step of the Checkout.

### Gift-wrapping tax dropdown behavior

[Forms Input with dropdown UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown) element. This dropdown defines the Tax for Gift-wrapping function in Checkout.

### Offer recycled packaging toggle switch behavior

[Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) element. This option can define, that customer wants an item with recycled packaging. The text appears in the third step of the checkout and with the checkbox nearby:

_I would like to receive my order in recycled packaging._

## Multistores functionality

This page is [Multistores dependent](../../../common-components/multistore-component/multistores-dependent.md) page.
