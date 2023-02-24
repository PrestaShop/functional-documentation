# Administration

## Description

This UI is responsible for General, Upload, and Notifications settings of the webshop.

<figure><img src="../../../.gitbook/assets/image (9) (4).png" alt="Administration User Interface"><figcaption><p>Administration User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../common-components/cancel-button.md)
* [E-commerce logo ](../common-components/e-commerce-logo.md)
* Version number (todo link)
* [Quick access dropdown ](../common-components/quick-access-dropdown.md)
* Search input (todo link)
* [Shop switcher with eye icon](../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../common-components/account-icon.md)
* [Language dropdown for input fields](../common-components/language-dropdown-for-input-fields.md)
* [Save button](../common-components/save-button.md)
* [Cancel button](../common-components/cancel-button.md)

## General section

Section title includes a grid icon.

### **Automatically check for module updates**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Choose a stability level for the modules downloaded from the Addons Marketplace. All zips pushed on Addons are in stable state unless stated otherwise.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#automatically-check-for-module-updates-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Addons API stability channel**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>"Beta" value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>New modules and updates are displayed on the modules page.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#addons-api-stability-channel-1">link to the behavior</a></td><td align="center">-</td><td> </td></tr></tbody></table>

### **Check the cookie's IP address**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#check-the-cookies-ip-address-behavior">link to the behavior</a></td><td align="center">-</td><td> </td></tr></tbody></table>

### **Lifetime of front office cookies**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this field (browser error).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numbers allowed, letters forbidden</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>480</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set the amount of hours during which the front office cookies are valid. After that amount of time, the customer will have to log in again.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">Lifetime of front office cookies is invalid. Please enter an integer greater than or equal to 0.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>876000</td><td align="center">Lifetime of front office cookies is invalid. Please enter an integer lower than 876000.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#lifetime-of-front-office-cook-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Lifetime of back office cookie**s&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this field (browser error).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numbers allowed, letters forbidden</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>480</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>When you access your back office and decide to stay logged in, your cookies lifetime defines your browser session. Set here the number of hours during which you want them valid before logging in again.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#lifetime-of-back-office-cookies-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Cookie SameSite**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Allows you to declare if your cookie should be restricted to a first-party or same-site context.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#cookie-samesite-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Upload quota section

Section title includes an upload icon.

### **Maximum size for attached files**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this field (browser error)</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">Please enter an integer greater than or equal to 0.</td><td></td></tr><tr><td>Default value</td><td>8 MB</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Set the maximum size allowed for attachment files (in megabytes). This value has to be lower than or equal to the maximum file upload allotted by your server (currently: 8 MB).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#maximum-size-for-attached-files-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Maximum size for a downloadable product**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this field (browser error)</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Negative values forbidden.</td><td align="center">Please enter an integer greater than or equal to 0.</td><td></td></tr><tr><td>Default value</td><td>2 MB</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Define the upload limit for a downloadable product (in megabytes). This value has to be lower or equal to the maximum file upload allotted by your server (currently: 2 MB).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#maximum-size-for-a-downloadable-product-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Maximum size for a product's image**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">Please fill in this field (browser error)</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Negative values forbidden.</td><td align="center">Please enter an integer greater than or equal to 0.</td><td></td></tr><tr><td>Default value</td><td>2 MB</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Define the upload limit for an image (in megabytes). This value has to be lower or equal to the maximum file upload allotted by your server (currently: 2 MB).</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#maximum-size-for-a-products-image-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Notifications section

Section title includes an exclamation icon and a blue circle element. The circle element includes the text _Notifications are numbered bubbles displayed at the very top of your back office, right next to the shop's name. They display the number of new items since you last clicked on them._ once it is hovered.&#x20;

### **Show notifications for new orders**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#show-notifications-for-new-orders-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Show notifications for new customers**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#show-notifications-for-new-customers-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Show notifications for new messages**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="administration.md#show-notifications-for-new-messages-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## **Behavior descriptions**

### **Automatically check for module updates behavior**

Required toggle button - toggle switch, by default it is enabled - it initiates the automatic Prestashop module updates checking. If there will be a newer module released in Addons Marketplcace, the system will show the notifications, about the available module updates. The description says _Choose a stability level for the modules downloaded from the Addons Marketplace. All zips pushed on Addons are in stable state unless stated otherwise._ and that means, that updating the modules with the newest will impact the webshop stability to the greater. This component is from [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Addons API stability channel behavior**

Required setting - it is a dropdown, with 3 available values - **Stable**, **Beta** and **Alpha**. By default, the Stable option is selected. Those values are set only from the Addons modules development side, as well especially useful for modules testing. Those channels are like development versioning branches. **Alpha** channel will contain the newest module updates, but mostly not tested, **Stable** will have the latest bug-fixed module changes and **Beta** will have a little tested and a little bug-fixed module API state - displayed as the middle type of the 3 channels. This component is from [Dropdown Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics).

### Check the cookie's IP address behavior

Required setting - it is a dropdown, with 3 available values - **Stable**, **Beta** and **Alpha**. By default, the Stable option is selected. Those values are set only from the Addons modules development side, as well especially useful for modules testing. Those channels are like development versioning branches. **Alpha** channel will contain the newest module updates, but mostly not tested, **Stable** will have the latest bug-fixed module changes and **Beta** will have a little tested and a little bug-fixed module API state - displayed as the middle type of the 3 channels. This component is from [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Lifetime of front office cook behavior**

Required setting - by default the value is set to 480 hours. This field can set the hourly rate, after when the Prestashop will logg-off the Customer from Front-Office. It was made for security reasons to prevent stealing the Customers' information. Also, it is a good practice for Customers to change the password in some time, so that Prestashop checks for the new password. If the field is submitted with invalid characters, the response _Lifetime of front office cookies is invalid. Please enter an integer greater than or equal to 0._ is prompted right after clicking Save CTA. This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group).

### **Lifetime of back office cookie**s behavior

Required setting - by default the value is set to 480 hours. This field can set the hourly rate, after when the Prestashop will logg-off the Administrator from Back-Office. It was made for security reasons to prevent stealing the Administrators' information. Also, it is a good practice for Administrators to change the password in some time, so that Prestashop checks for the new password. If the field is submitted with invalid characters, the response _Lifetime of back office cookies is invalid. Please enter an integer greater than or equal to 0._ is prompted right after clicking Save CTA. This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group).

### **Cookie SameSite behavior**

Required dropdown - by default, the value is set to Lax. These settings sets the cookie sending information to the third-party or the first-party websites. Additional information can be found in any browsers' [documentation page.](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie/SameSite)

There are the following SameSite cookie values:

* **Lax** - Cookies are not sent on normal cross-site subrequests.
* **Strict** - Cookies will only be sent in a first-party context.
* **None** - Cookies will be sent in all contexts, i.e. in responses to both first-party and cross-origin requests.

This component is from [Dropdown Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics).

### **Maximum size for attached files behavior**

Required input, by default the value is set to 8 megabytes. This field triggers the maximum size allowed for attachment. The size is valued in number of megabytes, additional block with the _megabytes_ is defined in the end of input element. Max file size is also defined in server configuration files.

No invalid character notifications are prompted, after typing letters or symbols. This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group).

### **Maximum size for a downloadable product behavior**

Required input, by default the value is set to 2 megabytes. This field triggers the maximum size allowed for file uploading. The size is valued in number of megabytes, additional block with the _megabytes_ is defined in the end of input element. Max file uploading size is also defined in server configuration files.

No invalid character notifications are prompted, after typing letters or symbols. This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group).

### Maximum size for a product's image behavior

Required input, by default the value is set to 2 megabytes. This field triggers the maximum size allowed for uploading product images. The size is valued in number of megabytes, additional block with the _megabytes_ is defined in the end of input element. Max product images uploading size is also defined in server configuration files.

No invalid character notifications are prompted, after typing letters or symbols. This component is from [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group).

### **Show notifications for new orders behavior**

Required toggle button, by default it is enabled. This feature allows showing notifications of the new orders on the top-right of the Prestashop UI. The new notifications will appear in the block. This component is from [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Show notifications for new customers behavior**

Required toggle button, by default it is enabled. This feature allows showing notifications of the new customers on the top-right of the Prestashop UI. The new notifications will appear in the block. This component is from [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

### **Show notifications for new messages behavior**

Required toggle button, by default it is enabled. This feature allows showing notifications of the new messages on the top-right of the Prestashop UI. The new notifications will appear in the block. This component is from [Forms Switch Story UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).

## Multistores functionality

This page is [Multistores dependent](../common-components/multistores-dependent.md) page.

Each Multistore or Shop group can be configured in All Shops mode or in separate Shops or Shop groups in this page. The configuration is being stored in separate databases of Shops and Shop groups, so the stored data can not be mixed between content.
