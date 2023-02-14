# Configure Mail Alerts (ps\_mailalerts)

<figure><img src="../../../../../.gitbook/assets/image (11) (2).png" alt="Mail alerts Configuration UI"><figcaption><p>Mail alerts Configuration User Interface</p></figcaption></figure>

## QA

[Link to the tests.](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## Common components

* [E-commerce logo](../../../common-components/e-commerce-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Search input](../../../common-components/search-input-field.md)
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Account icon](../../../common-components/account-icon.md).
* Bell icon (todo link).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../common-components/page-header-call-to-action-buttons-modules.md).
* [Language dropdown for input fields](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/diff/\~/changes/KjeTPSLSN1LXBZMsI7JI/functional-documentation/ux-ui/common-components/language-dropdown-for-input-fields).
* ​[Save button](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/save-button) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [Configuration block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block).

## Customer notifications block

### Product availability

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Give the customer the option of receiving a notification when an out of stock product is available again.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>-</td><td align="center">-</td><td></td></tr></tbody></table>

### Order edit

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Send a notification to the customer when an order is edited.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>-</td><td align="center">-</td><td></td></tr></tbody></table>

## Merchant notifications block

### New order

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Receive a notification when an order is placed.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>-</td><td align="center">-</td><td></td></tr></tbody></table>

### Out of stock

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES/NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Receive a notification if the available quantity of a product is below the following threshold.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>-</td><td align="center">-</td><td></td></tr></tbody></table>

### Threshold

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Quantity for which a product is considered out of stock.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>-</td><td align="center">-</td><td></td></tr></tbody></table>

### Returns

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Receive a notification when a customer requests a merchandise return.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Email addresses

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All the text values allowed, email list</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>The main email address of the webshop</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>One email address per line (e.g. bob@example.com).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>-</td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Product availability behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Enables or disables the product availability function. The customer will be informed about the item out of stock, and when the item will be restocked.&#x20;

### Order edit behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Customer will be notified about his order edition.

### New order behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Notification when the new order is placed.

### Out of stock behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. The threshold can be set for a product availability. Then the notification will be sent.

### Threshold behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Setting the quantity limit when the product is set as out of stock.

### Returns behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Notification when customer wants a return.

### Email addresses behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. The email list that all the notifications should be sent to.

## Multistores functionality

Page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.
