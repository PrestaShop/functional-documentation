# Shipping locations and costs

<figure><img src="../../../../../../../.gitbook/assets/Capture d’écran 2023-03-06 à 16.32.01.png" alt=""><figcaption></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../../common-components/e-commerce-logo.md).
* [PrestaShop version number](../../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../../../common-components/shop-switcher-with-eye-icon.md).
* [Bell icon](../../../../../common-components/bell-icon.md)-[Toolbar UI KIT](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar)
* [Account icon](../../../../../common-components/account-icon.md).
* [Heading of the page](../../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../../common-components/help-button.md) - [Buttons Outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## The UI elements

### Add handling costs toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Include the handling costs (as set in Shipping > Preferences) in the final carrier price.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shipping-locations-and-costs.md#add-handling-costs-toggle-switch">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Free shipping toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Include the handling costs (as set in Shipping > Preferences) in the final carrier price.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shipping-locations-and-costs.md#free-shipping-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Billing radio buttons

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>According to total weight.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shipping-locations-and-costs.md#billing-radio-buttons-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Tax dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>First tax rule by tax rule list.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shipping-locations-and-costs.md#tax-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Out-of-range behavior dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Apply the cost of the highest defined range.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Out-of-range behavior occurs when no defined range matches the customer's cart (e.g. when the weight of the cart is greater than the highest weight limit is defined by the weight ranges).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shipping-locations-and-costs.md#out-of-range-behavior-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Range Will be applied when the weight or currency is >= input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only.</td><td align="center">This range is not valid.</td><td></td></tr><tr><td>Default value</td><td>0.000000</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shipping-locations-and-costs.md#range-will-be-applied-when-the-weight-or-currency-is-greater-than-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Range Will be applied when the weight or currency is < input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only.</td><td align="center">This range is not valid.</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shipping-locations-and-costs.md#range-will-be-applied-when-the-weight-or-currency-is-less-than-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

##

## Behaviors description

## Shipping locations and costs step behavior

This step has elements:

* [Add handling costs toggle switch](shipping-locations-and-costs.md#add-handling-costs-toggle-switch-behavior)
* [Free shipping toggle switch](shipping-locations-and-costs.md#free-shipping-toggle-switch-behavior)
* [Billing radio buttons](shipping-locations-and-costs.md#billing-radio-buttons-behavior)
* [Tax dropdown](shipping-locations-and-costs.md#tax-dropdown-behavior)
* [Out-of-range behavior dropdown](shipping-locations-and-costs.md#out-of-range-behavior-dropdown-behavior)
* [Range Will be applied when the weight or currency is >=  input](shipping-locations-and-costs.md#range-will-be-applied-when-the-weight-or-currency-is-greater-than-input-behavior)
* [Range Will be applied when the weight or currency is <  input](shipping-locations-and-costs.md#range-will-be-applied-when-the-weight-or-currency-is-less-than-input-behavior)
* [Zones settings](shipping-locations-and-costs.md#zones-settings-behavior)
* [Add new range button](shipping-locations-and-costs.md#add-new-range-button-behavior)
* [Delete button](shipping-locations-and-costs.md#delete-button-behavior)

### Add handling costs toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows choosing if the handling costs are added to the final price or not.

### Free shipping toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that allows choosing if the carrier is free or not.

### Billing radio buttons behavior

There are 2 radio buttons ([Forms radio buttons](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons)) are displayed: "According to total price." and "According to total weight.". When "According to total price" is selected, the ranges are defined by currency. The currency displayed is the default one configured in International > Localization. When "According to total weight" is selected, the ranges are defined by weight. The weight displayed is the one defined in International > Localization.

### Tax dropdown behavior

This is dropdown menu ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) that displays all the enabled tax rules existing in International > Taxes > Taxes rules.

### Out-of-range behavior dropdown behavior

This is dropdown menu ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) that allows to select one of the 2 options: "Apply the cost of the highest defined range" or "Disable carrier". \
If the total weight or total price of the cart is not in one of the defined ranges and if the chosen option is "Disable carrier", then the carrier will be disabled. If the total weight or total price of the cart is not in one of the defined ranges and if the chosen option is "Apply the cost of the highest defined range", then the carrier price will be the one corresponding to the highest range.

### Range Will be applied when the weight or currency  is >= input behavior

This is input ([Forms basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter weight or currency number when range starts.

### Range Will be applied when the weight or currency  is < input behavior

This is input ([Forms basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter weight or currency number when range finishes.\
If one of the ranges overlaps another, the following error message is displayed: "Ranges are overlapping" and the fields for all zones are disabled.

### Zones settings behavior

All the zones existing in International > Locations > Zones are displayed below in alphabetical order to chose zones for the range. \
Each zone has a checkbox ([Forms checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes)) allowing to enable its input field. Only numbers are allowed in zones fields, inputting any other symbol will result in the field being marked in red.\
The disabled zones are marked as inactive. When trying to go to the next step without selecting any zone the following error message is displayed: "Please select at least one zone".&#x20;

### Add new range button behavior

This is CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) once clicked, a new column of range setting is displayed. When hover mouse pointer on button, its color changes.\
When clicking on it and if one of the existing ranges isn't completed, the following message is displayed "Please validate the last range before creating a new one."

### Delete button behavior

This is CTA button ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) it appears under each added range. Once button clicked opens popup that has notification: _Are you sure to delete this range?_ and 2 buttons:

* OK -it is a blue color CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)), once clicked deletes range and closes popup.
* Cancel -it is outlined CTA button ([Buttons outlined UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)), once clicked cancels deletion and closes popup.

When hover mouse pointer on each button, it color changes.
