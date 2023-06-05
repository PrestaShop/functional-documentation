# Category tree links (ps\_categorytree)

## Description

This module is responsible for the Category Tree display in the front-office.&#x20;

![Category tree links User Interface](<../../../../../.gitbook/assets/image (130).png>)

## Common components

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* Search input (todo link).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).
* Bell icon (todo link).
* Trophy icon (todo link).
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../common-components/page-header-call-to-action-buttons-modules.md).
* ​[Save button](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/save-button) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [Configuration block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block).

## The UI elements

### Category root

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center"><em>-</em></td><td></td></tr><tr><td>Default value</td><td>Current category</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Select which category is displayed in the block. The current category is the one the visitor is currently browsing.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="category-tree-links-ps_categorytree.md#category-root-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Maximum depth

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only.</td><td align="center"><em>-</em></td><td></td></tr><tr><td>Default value</td><td>4</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set the maximum depth of category sublevels displayed in this block (0 = infinite).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="category-tree-links-ps_categorytree.md#maximum-depth-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Sort

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center"><em>-</em></td><td></td></tr><tr><td>Default value</td><td>By position</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="category-tree-links-ps_categorytree.md#sort-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Sort order

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center"><em>-</em></td><td></td></tr><tr><td>Default value</td><td>Ascending</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="category-tree-links-ps_categorytree.md#sort-order-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Category root behavior**

**Category root** - various different Category root display options available ([Forms radio buttons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons)):

* Home category
* Current category
* Parent category
* Current category, unless it has no subcategories, in which case the parent category of the current category is used

### **Maximum depth behavior**

This is input field ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter maximum depth of category sublevels displayed. Numeric value can be set here. If enter letters or other symbols, input changes to 0 when Save button clicked.

### **Sort behavior**

**Sort** - ([Forms radio buttons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons)) sorting the category display options:

* **By name** - A-Z or Z-A style sorting.
* **By position** - sorting according to category ID.&#x20;

### **Sort order behavior**

**Sort order** - ([Forms radio buttons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons)) sorting the category display options:

* **Descending** - Z-A, 9-0 style sorting.
* **Ascending** - A-Z, 0-9 style sorting.

## Multistores functionality

The page is [Multistores dependent](category-tree-links-ps\_categorytree.md#multistores-functionality).
