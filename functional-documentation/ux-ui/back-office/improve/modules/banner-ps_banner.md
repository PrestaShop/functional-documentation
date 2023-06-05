# Banner (ps\_banner)

## Description

This module is responsible for generating and managing the graphical interface element called Banner. Usually, the Banner is displayed in the homepage of the webshop.&#x20;

![Banner User Interface](<../../../../../.gitbook/assets/image (4).png>)

## Common components

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).
* Bell icon (todo link).
* Trophy icon (todo link).
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../common-components/page-header-call-to-action-buttons-modules.md).
* [Language dropdown for input fields](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/diff/\~/changes/KjeTPSLSN1LXBZMsI7JI/functional-documentation/ux-ui/common-components/language-dropdown-for-input-fields).
* ​[Save button](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/save-button) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [Configuration block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block).

## The UI elements

### Banner image input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>GIF, JPG or PNG</td><td align="center"><em>Image format not recognized, allowed formats are: .gif, .jpg, .png</em></td><td></td></tr><tr><td>Default value</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Upload an image for your top banner. The recommended dimensions are 1110 x 214px if you are using the default theme.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a data-mention href="banner-ps_banner.md#banner-image-input-behavior">#banner-image-input-behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Banner link input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enter the link associated to your banner. When clicking on the banner, the link opens in the same window. If no link is entered, it redirects to the homepage.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a data-mention href="banner-ps_banner.md#banner-link-input-behavior">#banner-link-input-behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Banner description input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Please enter a short but meaningful description for the banner.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a data-mention href="banner-ps_banner.md#banner-description-input-behavior">#banner-description-input-behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Banner image input behavior

**Banner image** ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) with **Choose a file button with folder icon** ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) - clicking on button Choose a file component will initiate a Browse for file pop-up action, depending on the OS the user has. \
When hover mouse pointer on it, button color changes.

After those components, there is a **Preview** block. It displays the latest loaded image.

### **Banner link input behavior**

**Banner Link** ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) - a certain link can be defined, then users will be able to click on the banner and get redirected to the certain place.&#x20;

### **Banner description input behavior**

**Banner description** ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) - a certain description that can be defined. The description will be displayed as hovered alt text on the image banner.

## Multistores functionality

The page is [Multistores dependent](banner-ps\_banner.md#multistores-functionality).

