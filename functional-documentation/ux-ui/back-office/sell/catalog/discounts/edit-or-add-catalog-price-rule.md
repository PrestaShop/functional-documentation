# Edit or Add catalog price rule

## Description

Catalog price rules enable to assign price reductions by category, brand, supplier, attribute or feature. Catalog price rule, as its name implies, applies discount to a range of products.&#x20;

<figure><img src="../../../../../../.gitbook/assets/image (127).png" alt="Add new Catalog price rule User Interface"><figcaption><p>Add new Catalog price rule User Interface</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (25).png" alt="Add new Catalog price rule Conditions User Interface"><figcaption><p>Add new Catalog price rule Conditions User Interface</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (93).png" alt="Add new Catalog price rule Condition group User Interface"><figcaption><p>Add new Catalog price rule Condition group User Interface</p></figcaption></figure>

## Common components

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../common-components/save-button.md) - [Buttons Basics UI Kit.](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)
* [Cancel button](../../../../common-components/cancel-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../../common-components/e-commerce-logo.md)&#x20;
* [PrestaShop version number ](../../../../common-components/prestashop-version-number.md)
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)&#x20;
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;

## Catalog price rules creation input fields

### Name

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The name field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-catalog-price-rule.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### From quantity

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The from_quantity field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">The from_quantity field is invalid.</td><td></td></tr><tr><td>Default value</td><td>                   1</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   10</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-catalog-price-rule.md#from-quantity-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Price (tax excl.)

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">The price field is invalid.</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-catalog-price-rule.md#price-tax-excl.-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### From

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-catalog-price-rule.md#from-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## To

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-catalog-price-rule.md#to-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Reduction

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The reduction field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">The reduction field is invalid.</td><td></td></tr><tr><td>Default value</td><td>0.000000</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-catalog-price-rule.md#reduction-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Name behavior**

Text input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) is a mandatory field to enter the name of the Catalog price rule.

### **Shop** dropdown behavior

This dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) lists the multistore shops. The catalog price rule is applied to the selected shop.&#x20;

### Currency dropdown **behavior**

This dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) lists all the shop's currencies and "All currencies". By default, the Currency dropdown is set for "All currencies". If the "All currencies" option is set, Prestashop will execute reductions using the Default Prestashop currency that is set in configuration settings.

### Country dropdown behavior

Using this dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) a specific country can be set for the Catalog price rules. For example, it can be set that only German customers could see the certain price rules, Germany should be set in the dropdown. By default, the Country dropdown will be set for "All countries".

### Group dropdown behavior

Group dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) allows to choose customer group. Prestashop provides specific customer groups. By default, there are Visitor, Guest and Customer. Appropriate group can be selected, in order to show the price rules for that certain group of visitors in website. By default, the Group dropdown will be set for "All countries".

### **From quantity**  behavior

This is numeric input field ([Forms numbers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)). It can be typed, for example, 50 and it will mean, that all the catalog items with quantity up to 50 will get the certain catalog discount rule.&#x20;

### **Price (tax excl.)** behavior

This is numeric input field ([Forms numbers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)). In it can be typed, for example, 10 and it will mean, that all the catalog items with the prices up to 10 will get the certain catalog discount rule. By default, the field is gray and disabled, however if the **Leave initial price** checkbox is disabled, the field will be instantly enabled.\
**Leave initial price** is a checkbox ([Forms checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes)) for certain needs. If it is checked, customers would get the catalog price rules from the initial original item price. By default, the checkbox is enabled.

### **From** behavior

It is just simple date and time selection picker widget. Select the year, month, day and the time from when the catalog price rule will be executed and displayed for Prestashop items. By default, the field is empty, once clicked opens calendar in popup.

### **To** behavior

It is just a simple date and time selection picker widget. Select the year, month, day and the time the price rule existence should be exceeded for Prestashop items. By default the field is empty, once clicked opens calendar in popup.

### Reduction type dropdown behavior

Reduction type dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) - certain discount affection will be expressed as Percentage or Amount in the Prestashop items. It can be selected by one of the types in the dropdown. By default, the field is set to "Amount".

### Reduction with or without taxes dropdown behavior

Reduction with or without taxes dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics))  - if the prices should be discounted from the prices with taxes of without taxes. So as a result, it may be different deductions from the catalog prices. By default, the field is set to "Tax excluded".

### **Reduction** behavior

This is an Amount or Percentage type of input field ([Forms numbers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)). It can be set as certain digits here for the catalog prices to be shown.&#x20;

### Add a new condition group button behavior

It is CTA button ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) once clicked it opens Conditions form. It allows to create  additional and extended Catalog price rules combinations that can be specified for Catalog items. If no conditions are set, the price rule will be applied to all products of catalog. There are these dropdowns:

* **Category** - the merchant can choose to apply discount only on products which belong to the chosen category. By default, the dropdown category is set to Home. Next to dropdown is **Add condition** CTA button with plus icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). Once clicked it adds chosen category condition to Conditions group.
* **Brand** - the merchant can choose to apply a discount on a specific brand only. By default, the dropdown is set to default Prestashop brand Graphic Corner. Next to dropdown is **Add condition** CTA button with plus icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). Once clicked it adds chosen brand condition to Conditions group.
* **Supplier** - the merchant can choose to apply a discount on a specific supplier only. By default, the dropdown is set to Accessories supplier. Next to dropdown is **Add condition** CTA button with plus icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). Once clicked it adds chosen supplier condition to Conditions group.
* **Attributes** - the merchant can choose to apply a discount on a specific attribute only. To do so,  needs to choose the attribute type and a specific value. By default the dropdown value is set to Color and the next dropdown is set to Grey. Next to dropdowns is **Add condition** CTA button with plus icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). Once clicked it adds chosen attribute condition to Conditions group.
* **Features**  - the merchant can choose to apply a discount on a specific feture only. To do so, needs to choose the feature type and a specific value. By default the dropdown value is set to Composition and the next dropdown is set to Ceramic. Next to dropdowns is **Add condition** CTA button with plus icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). Once clicked it adds the chosen feature condition to the Conditions group.

AND : is an operator, which indicates that the conditional group elements are working together

OR : is an operator, which indicates the combining fact between two conditional groups.

It is possible to add several sets of conditions in the same group, but also to create different condition groups in the same rule.

1. When adding different criteria to the same group, this works as an AND relation. Ex : Category Women and Brand Nike - the rule will only apply to product which belong to the women category and whose brand is Nike.
2. When adding different condition groups to the same rule, this work as an OR relation between all groups. Ex : Group 1 : Category Men and Group 2 : Brand Adidas - the rule will apply to all products which belong to the men category or to the Adidas brand.

## Multistores functionality

This page is Multistores independent (todo link) page.
