# Adding or Editing Order Message

## Description

This UI shows the Order Message adding or editing form.

<figure><img src="../../../../../../.gitbook/assets/image (45).png" alt="Adding or Editing messages User Interface"><figcaption><p>Adding or Editing messages User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customer-service/order-messages.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../../common-components/cancel-button.md) - [Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo ](../../../../common-components/back-office-header/prestashop-logo.md)
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)
* [Quick access dropdown ](../../../../common-components/quick-access-dropdown.md)
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher](../../../../common-components/shop-switcher.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)
* [Language dropdown for input fields](../../../../common-components/language-dropdown-for-input-fields.md)

## The UI elements

### **Recommended Modules and Services button**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Recommended Modules and Services</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### **Name** input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field name is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">The field name is required at least in your default language.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>128</td><td align="center">This value is too long. It should have 128 characters or less. - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="adding-or-editing-order-message.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Message input**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field message is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or editable value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">The field message is required at least in your default language.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>1200</td><td align="center">This value is too long. It should have 1200 characters or less. - Language: English (English)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="adding-or-editing-order-message.md#message-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors descriptions

### **Recommended Modules and Services button behavior**

This is CTA button ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). When hover mouse pointer on it, buttons color changes. \
Once clicked it opens popup with Recommended Modules and Services, exit icon and loading spinner ([Spinner UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/spinner--spinner)). When loading is finished, notification message ([Alerts basics storybook UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) with _i_ icon and link: \
_More modules on addons.prestashop.com_ \
Once clicked link opens PrestaShop addons marketplace page in new window.

### **Notification message behavior**

There is a blue information message ([Alerts basics storybook UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) with _i_ icon, displaying the text:\
&#x20;_Note that this feature is available in all shops context only. It will be added to all your stores._&#x20;

### Order messages title behavior

Order messages is the title of block with person icon.&#x20;

### **Name input behavior**

Input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)), where desired Name would be set for the specific Order message.&#x20;

### **Message input behavior**

Input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)), where desired Message text will be set for the specific Order message.

## Multistores functionality

This page is Multistores independent (todo link) page.

The editing form is displayed the same for all the available Multistores in webshop, switching the Multistores shows the same editing form UI.
