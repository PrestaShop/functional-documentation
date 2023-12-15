# Image slider (ps\_imageslider)

## Description

This module enables an image slider at the front-office of the shop, in the back-office it's possible to configure the slider.

<figure><img src="../../../../../.gitbook/assets/image (27) (2).png" alt="Image Slider User Interface"><figcaption><p>Image Slider User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md).
* Bell icon (todo link).
* [Account icon](../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../common-components/help-button.md) - [Buttons Outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [Page header call to action buttons](../../../common-components/page-header-call-to-action-buttons-modules.md).
* Text Editing Tools list (todo link) - [Buttons Toolbar UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar).

## Settings

The table starts with the title _Settings_ and a gear-type icon nearby. Below there are 3 components in this settings box.

### Speed

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">Invalid values</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">Invalid values</td><td></td></tr><tr><td>Default value</td><td>5000</td><td align="center">Invalid values</td><td></td></tr><tr><td>Help text</td><td>The duration of the transition between two slides.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">Invalid values</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">Invalid values</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#speed-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Pause On hover

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Stop sliding when the mouse cursor is over the slideshow.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#pause-on-hover-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Loop forever

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Loop or stop after the last slide.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#loop-forever-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## **Slide list block**

This block starts with a title _Slides list_ and a list-type icon nearby. Also, there is a [Buttons Toolbar UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar) plus element, which initiates a new slide adding.

This section has the slides list in it, by default the 3 of them are located there. All of them have their own settings.

**Call-to-action button** - add new is located at the top of this section, when pressed, redirects to the Slide Information tab.&#x20;

There are the **drag and drop indicator arrows**, so slides can be dragged up or down, by the desired arrangement.

Every slide has 3 buttons:

* **Enabled/Disabled** - can be clicked, when the slide is Enabled, it will turn the CTA to red, the slide will be Disabled, the [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) message _Configuration updated_ will notice about that. And that's vice versa.&#x20;
* **Edit** - redirects to the Slide Information page.&#x20;
* **Delete** - when clicked, deletes the slide, shows an [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) message _Successful deletion_.

<figure><img src="../../../../../.gitbook/assets/Screenshot 2022-07-20 at 14-38-38 Module Manager • test.png" alt="Slides block UI"><figcaption><p>Slides block User Interface</p></figcaption></figure>

## Slide information

This section can only be accessed when editing a slide or when you click on _Add a new slide_ plus icon.

<figure><img src="../../../../../.gitbook/assets/Screenshot 2022-07-20 at 16-26-01 Module Manager • test.png" alt="Slide information UI"><figcaption><p>Slide information User Interface</p></figcaption></figure>

The section starts with a title _Slide information_ and a gear-type icon nearby.

The following components are listed:

### **Image**

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The image is not set.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or thumbnail of the Image already uploaded</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Maximum image size: 20M.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#image-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Title**

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Text, numeric values allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty of already filled value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">The title is too long.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#title-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Target URL**

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The URL is not set.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Letters and numbers allowed</td><td align="center">The URL format is not correct.</td><td></td></tr><tr><td>Default value</td><td>Empty of filled value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">The URL is too long.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#target-url-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Caption**

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All the numeric and letter values allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or filled value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">The caption is too long.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#caption-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Description**

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All numeric and letter values allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty or filled values</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>3993 characters</td><td align="center">The description is too long.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Enabled**

<table><thead><tr><th width="200">Description</th><th width="270">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="image-slider-ps_imageslider.md#enabled-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## **Behaviors descriptions**

### **Speed behavior**

A [Forms Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group) component. Specifies the duration time of the transition between the slides.

### **Pause On hover behavior**

A [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Enables or disables the pause action when mouse cursor hovers the slide in Front-Office.

### **Loop forever behavior**

A [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Enables or disables the looping forever, or stopping the transition after the last slide.

### **Image behavior**

This section displays the current image, a new one can be uploaded with a call to action button ([Forms Files UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) - _Choose a file_, when pressed it opens a new tab to select an image to upload. The component is multi language, and can be translated to other existing languages in the back-office.

### **Title behavior**

A [Form Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Has the title input of the slide, the field is multi language, can be translated to any other language that is installed on the shop.

### **Target URL behavior**

A [Form Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. There can be a particular URL link that can be defined for the certain image. The visitors can click on the link.

### **Caption behavior**

A [Form Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. A small description of the image. The caption of the slide, the field is multi language, can be translated to any other language that is installed on the shop.

### **Description behavior**

A [Form Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. The text area starts with Text Editing Tools list (todo link) common component.&#x20;

### Enabled behavior

A [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. A toggle switch, by default, is set at "Yes" or "No" depending on if the slide is activated. Enables or Disables the Slide visibility in Front-Office UI.

## Multistores functionality

[Multistores independent](../../../common-components/multistores-independent.md) page. After the changes take effect on separate Multistore, the UI will return a notification from [Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) - _The modifications will be applied to shop: {shop name}._



