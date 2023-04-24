# Add new Image type

## Description

This configuration UI is about adding the new Image type into the Image type listing.

<figure><img src="../../../../../../.gitbook/assets/image (17) (1).png" alt=""><figcaption><p>Adding or Editing Image type User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/back-office-header/quick-access-dropdown.md)&#x20;
* Search input (todo link)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;
* [Save button](../../../../common-components/save-button.md) - [Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* [Cancel button](../../../../common-components/cancel-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## Adding or editing Image type UI

### **Name for the image type**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The name field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Letters, numbers, underscores and hyphens allowed only</td><td align="center">The name field is invalid.</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Letters, underscores and hyphens only (e.g. "small_custom", "cart_medium", "large", "thickbox_extra-large").</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#name-for-the-image-type-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Width

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The width field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">The width field is invalid.</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum image wight in pixels.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#width-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Height**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The height field is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numbers allowed only</td><td align="center">The height field is invalid.</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum image height in pixels.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#height-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Products&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This type will be used for Product images.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#products-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Categories

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This type will be used for Category images.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#categories-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Brands

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This type will be used for Brand images.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#brands-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Suppliers

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This type will be used for Supplier images.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#suppliers-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Stores

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This type will be used for Store images.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-image-type.md#stores-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

During default Image type configuration, the notification is prompted as error:\
_By default, all images settings are already installed in your store. Do not delete them, you will need it!_

After setting up the Image type configuration, the UI prompts the warning notification:\
_After modification, do not forget to regenerate thumbnails_

### **Name for the image type behavior**

This is input field ([Forms normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) that describes the main name of the image type.&#x20;

### **Width behavior**

This is input field ([Forms normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) that sets the numeric value of Image type width in pixels.&#x20;

### **Height behavior**

This is input field ([Forms normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal))  that sets the numeric value of Image type height in pixels.&#x20;

### **Products behavior**

This toggle switch button ([Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) can be set for using images type for PrestaShop Products.&#x20;

### **Categories behavior**

This toggle switch button ([Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) can be set for using images type for PrestaShop Categories.&#x20;

### **Brands behavior**

This toggle switch button ([Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) can be set for using images type for PrestaShop Brands.&#x20;

### **Suppliers behavior**

This toggle switch button ([Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) can be set for using images type for PrestaShop Suppliers.

### **Stores behavior**

This toggle switch button ([Forms switch story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story))can be set for using images type for PrestaShop Stores.&#x20;

## Multistore behavior

Multistores independent page (todo link).

The fields listed above don't have checkboxes and are available in all contexts (all shops, group, single store). Images types are set for all shops, no matter the context selected.

