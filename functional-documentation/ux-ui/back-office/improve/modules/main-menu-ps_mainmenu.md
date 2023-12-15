# Main menu (ps\_mainmenu)

## Description

This module is responsible for the webshop's top main menu links, and it's configuration.

<figure><img src="../../../../../.gitbook/assets/image (79).png" alt="Main menu configuration UI - All Shops content"><figcaption><p>Main menu configuration User Interface - All Shops content</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (59).png" alt="Main menu configuration UI"><figcaption><p>Main menu configuration User Interface - Single Shop content</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/modules/ps-mainmenu.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics) (becomes as Update button in Update link section, when Links are being updated)
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/back-office-header/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Configuration block](../../../common-components/configuration-block.md)
* [Page header CTA buttons](../../../common-components/module-page-specific-component/page-header-call-to-action-buttons-modules.md)

## Menu Top Link block

The block starts with the chain-style icon and the title _Menu Top Link._

### **Change position**

If the user wants to change the selected menu link (or links) position (or positions), there are 2 navigation buttons-arrows:

* **Upwards arrow button** - after selecting the link (or links), the link moves one step up.
* **Downwards arrow button** - after selecting the link (or links), the link moves one step down.

### **Selected items**

The input block, where the links are listed. By default, the links are:

* **Clothes**
* **Accessories**
* **Art**

### **Available items**

The input block, where the links are listed. By default, the links are:

* **CMS**
  * **Home**
    * **Delivery**
    * **Legal notice**
    * **Terms and conditions of user**
    * **About us**
    * **Secure payment**
* **Supplier**
  * **All suppliers**
    * **Accessories supplier**
    * **Fashion supplier**
* **Brand**
  * **All brands**
  * **Graphic Corner**
  * **Studio Design**
* **Categories**
  * **Root (PrestaShop)**
    * **Home (PrestaShop)**
      * **Clothes (PrestaShop)**
        * **Men (PrestaShop)**
        * **Women (PrestaShop)**&#x20;
      * **Accessories (PrestaShop)**
        * **Stationery (PrestaShop)**
        * **Home Accessories (PrestaShop)**
      * **Art (PrestaShop)**
* **Products**
  * **Choose product ID**
* **Menu Top Links**

### **Remove CTA button**

A [Button with icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons) component. Removes the selected item (or items) from the Selected Items form component and places in the Available Items form.

### **Add CTA button**

A [Button with icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons) component. Adds the selected item (or items) to the Selected Items form component from the Available Items form.

## Add a new link

The block starts with the chain-style icon and the title _Add a new link._

### Label

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any characters allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="main-menu-ps_mainmenu.md#label-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Link

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any characters allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="main-menu-ps_mainmenu.md#link-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### New window

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="main-menu-ps_mainmenu.md#new-window-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Link list (appears when links are stored)

The table is made of the [Tables Hoverable UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--hoverable) component. It contains:

* **Link ID** - numeric value of the link.
* **Shop name** - shows the multistore name, where the link is placed in.
* **Label** - shows the label of the link.
* **Link** - shows the link URL, it can be clicked.
* **New window** - shows if the clicked link will be opened in new window or not
* **Edit or Delete action** - [Dropdowns With Button Split UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split) component, which enables functionality to Edit the link or just to Delete it. After clicking **Delete**, the dialog box is prompted in the UI, with the question _Delete selected item?_ and with the available choices, **Yes** or **No**.

## Behaviors descriptions

### Label behavior

[Forms Normal UI Kit ](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)component. This input lets the administrator Edit or Add the link label.

### Link behavior

[Forms Normal UI Kit ](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)component. This input lets the administrator Edit or Add the link URL.

### New window behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This toggle switch Enables or Disables the functionality, that opens the clicked link in new page.

## Multistores functionality

The page is [Multistores dependent](../../../common-components/multistores-dependent.md) page.
