# Image slider (ps\_imageslider)

## Description

This module enables an image slider at the front-office of the shop, in the back-office it's possible to configure the slider.

<figure><img src="../../../../../.gitbook/assets/image (27).png" alt="Image Slider User Interface"><figcaption><p>Image Slider User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/e-commerce-logo.md).
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

## Settings

Below there are 3 components in settings box.

### Speed: Number input field measured in milliseconds

| Description   | Value                                                | Error message    |
| ------------- | ---------------------------------------------------- | ---------------- |
| Mandatory     | No, but can be left empty                            | "Invalid values" |
| Default value | 5000                                                 | -                |
| Help text     | "The duration of the transition between two slides." | -                |

### Pause On hover (toggle switch)

| Description   | Value                                                       | Error message |
| ------------- | ----------------------------------------------------------- | ------------- |
| Mandatory     | Yes                                                         | -             |
| Default value |  By default is set to "Yes".                                | -             |
| Help text     | "Stop sliding when the mouse cursor is over the slideshow." | -             |

### Loop forever (toggle switch)

| Description   | Value                                | Error message |
| ------------- | ------------------------------------ | ------------- |
| Mandatory     | Yes                                  | -             |
| Default value |  By default is set to "Yes".         | -             |
| Help text     | "Loop or stop after the last slide." | -             |

****

## **Behaviors description**

****

### **Save Button CTA**

Call to action - save button is located at the bottom, when pressed displays the message: "The settings have been successfully updated."

### **Slides list**

This section has the slides list in it, by default the 3 of them are located there. All of them have their own settings.

Call to action button - add new is located at the top of this section, when pressed, redirects to the \[SLIDE INFORMATION] tab.&#x20;

The slides can be dragged up or down.

Every slide has 3 buttons:

* Enabled/Disabled - can be pressed, when the slide is disabled, it will turn the color to red.
* Edit - redirects to the \[SLIDE INFORMATION] tab.&#x20;
* Delete - when pressed deletes the slide, shows a message: "Successful deletion."

![](<../../../../../.gitbook/assets/Screenshot 2022-07-20 at 14-38-38 Module Manager • test.png>)

## Slide information

This section can only be accessed when editing a slide or when you click on "add a new slide".

![](<../../../../../.gitbook/assets/Screenshot 2022-07-20 at 16-26-01 Module Manager • test.png>)

The following components are listed:

* **Image**

This section displays the current image, a new one can be uploaded with a call to action button - "Choose a file", when pressed it opens a new tab to select an image to upload. The component is multi language, and can be translated to other existing languages in the back-office.

Has a help text: "Maximum image size: 1500M."

* **Title**

Has the title input of the slide, the field is multi language, can be translated to any other language that is installed on the shop.

* **Target URL**

| Description              | Value                                    | Error message         |
| ------------------------ | ---------------------------------------- | --------------------- |
| Mandatory                | Yes                                      |                       |
| Default value            | The URL of the slide                     |                       |
| Allowed/Forbidden values | Anything is allowed, can't be left empty | "The URL is not set." |

* **Caption**

The caption of the slide, the field is multi language, can be translated to any other language that is installed on the shop.

* **Description**

The specifications of the description field can be found [\[HERE\]](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/JoHY00TjQGJ6Tyc8mp3s/functional-documentation/ux-ui/common-components/text-editing-tools-list).

* **Enabled**

A toggle switch, by default is set at "Yes" or "No" depending if the slide is activated.



A call to action button - **save** is located at the bottom, when pressed shows the following message: "Successful update.".

## Configuration

Multistore settings for all shop context can be found [\[HERE\]](../../../common-components/multistores-dependent.md).

## Front-office

By default the slides are located at the top of the shop, they switch to another on the miliseconds the user has set.

![](<../../../../../.gitbook/assets/Screenshot 2022-07-20 at 16-54-22 test.png>)

