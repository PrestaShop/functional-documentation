# Advanced Parameters > Multistore > Add new / edit shop group

This page allows adding additional Shop Group in existing Multistore functionality. The certain options and fields can configure both in the Adding or Editing Shop Group functionality.

![Add or Edit Shop Group User Interface](<../../../../../../.gitbook/assets/image (10).png>)

### Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Save Button (todo link)
* Cancel Button (todo link)
* Color picker (todo link)

## Multistore tree block

The section contains the tree segmentation icon, title _Multistore tree,_ additional buttons from [Buttons with icons UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons) and the tree content.

* **Icon** - identifies the section theme.
* **Multistore tree** - unique name of the section.
* **Collapse All** - button, once clicked, collapses all the Multistore tree interface scheme.
* **Expand All** - button, once clicked, expands all the Multistore tree interface scheme.
* **Content of the tree** - it is displayed in this hierarchic structure:\

* _Folder name (with the folder icon);_
  * _Prestashop Multistore name (bolded text);_
    * _URL of Multistore (bolded text);_

## Shop group block

Block begins with a blue [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics). The text content in this component is:

_Warning: Enabling the "share customers" and "share orders" options is not recommended. Once activated and orders are created, you will not be able to disable these options. If you need these options, we recommend using several categories rather than several shops._

### Shop group name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The name field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty field/Last stored name</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>64</td><td align="center">The name field is too long (64 chars max).</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="advanced-parameters-greater-than-multistore-greater-than-add-new-edit-shop-group.md#behavior-of-the-shop-group-name-input">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of the Shop group name input

The Shop group can be specified and stored by individual name, after clicking Save button.

### Color input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Symbols @#$ ect.</td><td align="center">The color field is invalid.</td><td></td></tr><tr><td>Default value</td><td>Empty field/Last stored name</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>It will only be applied to this group of shops, each store will keep its individual color.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Choose a color with the color picker, or enter an HTML color (e.g. "lightblue", "#CC6600").</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="advanced-parameters-greater-than-multistore-greater-than-add-new-edit-shop-group.md#behavior-of-the-color-input">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of the Color input

The HTML color codes can be typed in for certain color setting, and the color will be displayed in the top of each Multistore dropdown switcher.

### Color picker

Color picker (common component todo link)

### Share customers toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled and inactive toggle button</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Once this option is enabled, the shops in this group will share customers. If a customer registers in any one of these shops, the account will automatically be available in the others shops of this group. Warning: you will not be able to disable this option once you have registered customers.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="advanced-parameters-greater-than-multistore-greater-than-add-new-edit-shop-group.md#behavior-of-the-share-customers-toggle-switch">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of the Share customers toggle switch

Shared customers can only be enabled, once the customers registers in the different shop, not this parent shop. The component is from [Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### Share available quantities for sale toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled toggle button</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Share available quantities between shops of this group. When changing this option, all available products quantities will be reset to 0.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="advanced-parameters-greater-than-multistore-greater-than-add-new-edit-shop-group.md#behavior-of-the-share-available-quantities-for-sale-toggle-switch">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of the Share available quantities for sale toggle switch

This option lets sharing quantities between the shops. The component is from [Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### Share orders toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled and inactive toggle button</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Once this option is enabled (which is only possible if customers and available quantities are shared among shops), the customer's cart will be shared by all shops in this group. This way, any purchase started in one shop will be able to be completed in another shop from the same group. Warning: You will not be able to disable this option once you've started to accept orders.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="advanced-parameters-greater-than-multistore-greater-than-add-new-edit-shop-group.md#behavior-of-the-share-orders-toggle-switch">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of the Share orders toggle switch

This option lets sharing orders between the shops. The component is from [Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### Status toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Once this option is enabled (which is only possible if customers and available quantities are shared among shops), the customer's cart will be shared by all shops in this group. This way, any purchase started in one shop will be able to be completed in another shop from the same group. Warning: You will not be able to disable this option once you've started to accept orders.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>Behavior</td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of the Status toggle switch

This option lets Enabling or Disabling the shop. The component is from [Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### Cancel button

Cancel button (todo link to common component).

### Save button

Save button (todo link to common component).
