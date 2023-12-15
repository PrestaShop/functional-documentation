# Preference

## Description

The UI it’s the "Preferences" page, you can set some basic informations that will have an impact on the carierres page

<figure><img src="../../../../../.gitbook/assets/Capture d’écran 2023-03-07 à 16.37.34.png" alt=""><figcaption></figcaption></figure>

## Components description

**Common components**&#x20;

* [Checkmark navigation CTA buttons](../../../common-components/checkmark-navigation-cta-buttons.md) - [Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons).
* [Help Button](../../../common-components/help-button.md) - [Buttons Outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).&#x20;
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).&#x20;
* [Account icon](../../../common-components/account-icon.md).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [Setting bar](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/366/functional-documentation/ux-ui/common-components/setting-bar)&#x20;
* [Bell icon ](../../../common-components/bell-icon.md)
* [Save button ](../../../common-components/save-button.md)

## The UI elements

#### <mark style="color:purple;">Handling</mark>&#x20;

### Handling charges input&#x20;

<table><thead><tr><th width="202.66666666666666">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only <strong>number</strong> &#x26; <strong>.</strong> allowed</td><td align="center">This value is not valid.</td><td></td></tr><tr><td>Default value</td><td>2.00</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td></td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="preference.md#speed-grade-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Free shipping starts at input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only <strong>number</strong> &#x26; <strong>.</strong> allowed</td><td align="center">This value is not valid.</td><td></td></tr><tr><td>Default value</td><td>0.000000</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="preference.md#logo-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Free shipping starts at input

<table><thead><tr><th width="236.66666666666666">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center"></td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only <strong>number</strong> &#x26; <strong>.</strong> allowed</td><td align="center">This value is not valid.</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="preference.md#tracking-url-input-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### <mark style="color:purple;">Carrier options</mark>

### Default carrier dropdown

<table><thead><tr><th width="202.66666666666666">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Click and collect</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Your shop's default carrier.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td></td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="preference.md#speed-grade-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Sort by dropdown&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Price</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>This will only be visible in the front office.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="preference.md#logo-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Order by dropdown

<table><thead><tr><th width="236.66666666666666">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center"></td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Ascending</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>This will only be visible in the front office.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="preference.md#tracking-url-input-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

#### <mark style="color:purple;">Handling</mark>&#x20;

### Handling title Helpbox&#x20;

The Handing title helpbox [( Helpbox UI kit)](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/helpbox--helpbox) displays the help message : " If you set these parameters to 0, they will be disabled. Coupons are not taken into account when calculating free shipping" &#x20;

### Handling charges input&#x20;

This is input field ([Forms input group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group)) to enter the handling price withou VAT.

### Free shipping starts at input

This is input field ([Forms input group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group)) to enter the price value at which the free shipping starts.&#x20;

### Free shipping starts at input

This is input field ([Forms input group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group)) to enter the weigth value at which the free shipping starts.&#x20;



#### <mark style="color:purple;">Carrier options</mark>

### Default carrier dropdown

The dropdown menu ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) displays all the enabled carriers existing in Shipping > Carrier . The value by default " Click and collect" is selected

### Sort by dropdown&#x20;

The dropdown menu ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) displays to display option for front office.&#x20;

* **Price** - the position of carriers will be determined with price.&#x20;
* **Position -**the position of carries will be determined according to the settings of the "position" column of the [General setting](carrier-list-page/edit-add-carrier/general-setting.md) page .

### Order by dropdown

The dropdown menu ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) displays to display option for front office.&#x20;

* **Ascendig** - the position of carriers will be determined with price or postion (as explained above). If Ascending is select, the carriers position is ascending
* **Descending -**the position of carries will be determined price or postion ( as explained above) If Descending is select, the carriers position is Descending

