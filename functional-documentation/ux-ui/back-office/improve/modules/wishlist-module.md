# Wishlist Module

## Description

This module allows the user of the shop to create a wish list. 2 sections are in the back-office of the module "Configuration" and "Statistics" tabs.

<figure><img src="../../../../../.gitbook/assets/image (43).png" alt="Wishlist module Configuration tab User Interface"><figcaption><p>Wishlist module Configuration tab User Interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (39) (1).png" alt="Wishlist module Statistics tab User Interface"><figcaption><p>Wishlist module Statistics tab User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher](../../../common-components/shop-switcher.md).
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Language dropdown for input fields](../../../common-components/language-dropdown-for-input-fields.md)
* [Save button](../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).

## The UI elements

### Wishlist default title input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The field WishlistDefaultTitle is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>My wishlist</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="wishlist-module.md#wishlist-default-title-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Create button label input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The field CreateButtonLabel is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Create new list</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="wishlist-module.md#create-button-label-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Wishlist page name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The field WishlistPageName is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>My wishlist</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="wishlist-module.md#wishlist-page-name-input-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Title Wording section** behavior

Title includes the title and edit icon.

### Wishlist default title input behavior

This is input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter wishlist default title.

### Create button label input behavior

This is input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter button label.

### Wishlist page name input

This is input ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter wishlist page name.

### **Title Top 10 most added products section** behavior

Title includes the title and star icon.

### Time period buttons group behavior

There are 4 CTA buttons in this button group ([Button group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--button-group)) and they are:

* Day - shows one day wishlist products in list.
* Month - shows month wishlist products in list.
* Year - shows year wishlist products in list.
* All time - shows all time wishlist products in list.

Day button is marked by default. When hover mouse pointer on each button, button's color changes.

### Refresh button behavior

This is CTA button with clock refresh icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). When hover mouse pointer on it, button's color changes. Once clicked button refreshes the statistics page with list bellow.

### Top 10 most added products list behavior

In this list the top 10 products are shown by chosen time period.\
The information shown for every product:

* Product (with a link which when pressed redirects to the product in the back office)
* Reference
* Combination
* Category
* Price (tax excl.)
* Available Qty
* Conversion rate

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.
