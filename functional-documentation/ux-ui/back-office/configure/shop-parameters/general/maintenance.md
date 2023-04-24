# Maintenance

## Description&#x20;

This page manages the setting for webshop administrators to temporary stop the access to the webshop Front-Office. Instead of accessing the webshop, there will be a maintenance page for the visitors.

![Maintenance interface](<../../../../../../.gitbook/assets/image (2) (2) (2).png>)

<figure><img src="../../../../../../.gitbook/assets/image (6) (2) (1) (1).png" alt=""><figcaption><p>Multishop in Maintenance User Interface ( LABEL MULTISHOP ) </p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Text Editing tools list](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/JoHY00TjQGJ6Tyc8mp3s/functional-documentation/ux-ui/common-components/text-editing-tools-list).
* Save button (todo link)
* Cancel button (todo link)

## Tabs section

The active selected tab _Maintenance_ is highlighted using [Navigation Tab UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/navigation--navigation-tabs).

## The main block&#x20;

**Header of the block** - named **General** with material family icon nearby.

### **Enable store**&#x20;

Required toggle switch from [Forms Switch UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story). It enables or disables the webshop from the Front-Office for visitors. The helper text from [Forms Helpers UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--helpers) defines that:

_We recommend that you deactivate your store while performing maintenance. Note that it will not disable the webservice._

### **Maintenance IP**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>IP address or addresses can access the webshop Front-Office. All the IP addresses can be typed, separating with commas (,).</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or saved IP adresses </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>"Allow IP addresses to access the store, even in maintenance mode. Use a comma to separate them (e.g. 42.24.4.2,127.0.0.1,99.98.97.96)."</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>No limitations for number of characters (as seen in database).</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>No limitations for number of characters (as seen in database).</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="maintenance.md#behavior-of-the-maintenance-ip-field">Behavior</a> of Maintenance IP</td><td align="center">-</td><td></td></tr></tbody></table>

### **Add IP button**&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td><strong>-</strong></td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="maintenance.md#add-my-ip-call-to-action">Behavior</a> of Add IP button</td><td align="center">-</td><td></td></tr></tbody></table>

### Custom maintenance text area

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td><strong>-</strong></td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty field or defined text earlier</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td><em>0 of 21844 characters allowed</em></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="maintenance.md#behavior-of-the-custom-maintenance-text-area">Behavior</a> of the custom maintenance text area</td><td align="center">-</td><td></td></tr></tbody></table>

### Multistores dropdown component

If the content is displayed on **All Shops** mode, there is an element from the [Dropdown Variation UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--variations), market-style material icon included, which shows the available Multistores, that are set in the webshop. These dropdowns are placed on the right side with all the paragraphs aligned. Once the dropdowns are clicked, the arrow-style icon will reposition upwards and a contextual block will appear.&#x20;

### Search shop name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center"><em>No results fount for "{searched word}"</em></td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td><strong>-</strong></td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder text "Search shop name"</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td><em>-</em></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="maintenance.md#search-input-with-a-placeholder">Behavior</a> of input with a placeholder</td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors descriptions

### Workflow

This sub-section MUST describe the page workflow

[Tristan Lehot](http://localhost:5000/u/wxuQ8dEUfYTsCcCBbcFmmedKE5t2 "mention") ( TODO )&#x20;

This sub-section MUST include a diagram of this worflow (using : [https://app.diagrams.net/](https://app.diagrams.net) or [figma](https://www.figma.com/file/14ptOoCqDdmBqtmq1Grc5M/BO-Core-Cartography?node-id=0%3A1) ) & the xml export of this workflow

### Behavior descriptions

#### **Behavior of the Maintenance IP field**&#x20;

Input field of [Forms Normal UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--normal). This field can be filled only with the IP addresses. If the webshop is on Maintenance mode, certain IP addresses can be as exceptions. That means, that devices with only certain IP address or addresses can access the webshop Front-Office. All the IP addresses can be typed, separating with commas (,).&#x20;

#### Add my IP call to action&#x20;

Clicking the CTA button (from [Buttons with icons UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), the page contains JavaScript, and it initiates adding the current IP address to the input field. Just one click and the IP address is stored automatically.&#x20;

The format of the IP address is as standard and follows the standard IP address construction from 4 byte-type elements: _XX.XX.XX.XX_

#### Save call to action&#x20;

User saves the information of the form in Maintenance page, so that he can configure the traffic of the webshop and deny or prevent the access of the front page visitors.

* This sub-section COULD contains a link to the relevant [business rule](../../../../../how-to-write-functional-documentation/templates/business-rules-template.md)

#### Behavior of the custom maintenance text area

It has the following components:

* Tab selections for different languages from [Navigation Pills UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/navigation--navigation-pills). By default, the main tab selected is the default Prestashop language tab.

#### **Search input with a placeholder**&#x20;

_Search shop name_ from [Forms Normal UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--normal), and a magnifier icon nearby. If there are more than 2 characters typed into the field, the additional dropdown will be shown with the text _No results fount for "{searched word}"_ if nothing matches, or the text in the dropdown text will be bolded, if the wording matches the Multistore name. Clicking on the name appeared will reload the page and switch the content to the exact Multistore.

#### Input Multistore dropdown behaviors

Once there are Multistores installed, the input fields will contain the dropdowns. The dropdown will contain the following elements:

* **Headlines with the Multistore group name**.
* **Multistore names** - will be listed one after other, with the additional definitions nearby - the main Multistore will be defined as Customized (with a lock-style icon nearby), the other Multistores will be defined as Inherited (green colored bolded text). Clicking on the names will reload the page and switch the content to the exact Multistore.

#### Text editing tools in the Custom maintenance text area

The tools available allows to customize the maintenance text, that will be displayed in Front-Office. Once the tool button is hovered, there will be alt text with the tool name, for better orientation. The buttons are referred to [Buttons Toolbar UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--toolbar).

[Text editing tools list](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/JoHY00TjQGJ6Tyc8mp3s/functional-documentation/ux-ui/common-components/text-editing-tools-list).

#### Character counter help text in the Custom maintenance text area

There is a character counter text, right above the input form. It shows how many characters are stored in the input area and what is the maximum amount of characters in that input area.&#x20;

Helper text notifies, that, _21844 characters allowed_ in the form_._

## Limitations

User should check his IP address by himself or simply click the button _Add my IP_, to store the current IP of the computer.
