# Module Alerts and Updates

## Description

These UIs, displayed in separate Alerts and Updates tabs, indicate the modules, that should be with full configuration in order to make the module fully operational, or to upgrade the module to the newest version.

<figure><img src="../../../../../.gitbook/assets/image (142).png" alt="Module Alerts Tab User Interface"><figcaption><p>Module Alerts Tab User Interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (70).png" alt="Module Updates Tab User Interface"><figcaption><p>Module Updates Tab User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../common-components/cancel-button.md)
* [E-commerce logo ](../../../common-components/back-office-header/prestashop-logo.md)
* [Version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown ](../../../common-components/back-office-header/quick-access-dropdown.md)
* [Search input](../../../common-components/search-input-field.md)&#x20;
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../common-components/account-icon.md)
* [Language dropdown for input fields](../../../common-components/language-dropdown-for-input-fields.md)
* [Save button](../../../common-components/save-button.md)
* [Cancel button](../../../common-components/cancel-button.md)

## Top UI elements for Alerts and Updates tabs

* **Upload a module Call-to-action (CTA) button with the cloud-style icon with the arrow pointed up** - allows uploading and installing the module to the store. Once the mouse pointer is hovered this button, an additional tooltip is visible with the advisable text _Upload a module_. After the button is clicked, a pop-up will appear (more details in the next paragraph, _Upload pop-up_).
* **Tabs** - navigation tabs for Modules menu. Components are from [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills). The editing tab is indicated as highlighted:
  * **Modules**
  * **Alerts** - yellow notification circle with white number in the top-right place of tab, indicating, how many modules can be triggered for alerts or updates.
  * **Updates** - yellow notification circle with white number in the top-right place of tab, indicating, how many modules can be triggered for alerts or updates.

## Alerts tab

* **Balded title with the tooltip** - {modules number in total} modules to configure and a hover tooltip. A tooltip is displayed as a blue information _i_ icon, and when hovered, the text _Modules to configure. These modules require your attention: you need to take some action to ensure they are fully operational._ appears in dark box. Component is from [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills).

### Module row blocks for Alerts tab

Module row block for Alerts tab is displayed the same as in other Module Manager or Module Selections listings.

Each Module block is displayed as a separate row and with the following elements:

* **Icon** - specific module icon, that identifies the module in visual side.
* **Name** - full module name.
* **Numeric value with dots** - module version.
* **Bolded smaller text** - the name of the module developer.
* **Description paragraph** - description of the module. Sometimes there is a huge paragraph, so a module row shows only an excerpt of the description and the rest of the text is expanded under the _Read more_ link (more information about the Read more pop-up is in a separate paragraph).
* **CTA button** **(usually Configure)** - these buttons are used for module management. This component is from [Dropdowns With Button Split UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split). By default, once the module is installed in the system, the CTA button becomes _Configure_ named. Clicking configure leads to a module management dashboard page. If the module is outdated, the CTA button can be shown as _Upgrade_. Clicking Upgrade will update the module to the latest version according to the latest module release. There is a **dropdown arrow** near the button - clicking on the arrow, shows additional functions for the certain module (the same, as Bulk action functions):
  * **Uninstall** - uninstalls selected module.
  * **Disable** - disables selected module.
  * **Enable** - enables selected module.
  * **Reset** - resets selected module.
  * **Enable Mobile** - enables the Mobile view for the module.
  * **Disable Mobile** - disables the Mobile view for the module.

## Updates tab

* **Balded title with the tooltip** - {modules number in total} modules to update and a hover tooltip. A tooltip is displayed as a blue information _i_ icon, and when hovered, the text _Modules to update. Update these modules to enjoy their latest versions._ appears in dark box.
* **Ghost button CTA Upgrade All** - initiates the Bulk action for upgrading all the available modules at the same time. The next actions are specified in the next topic. This component is from [Buttons Outline UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).

### Upgrade All Pop-up UI

Once the **Ghost CTA Upgrade All** or single **Upgrade** button is clicked, the pop-up is prompted in UI with the following displayed elements:

* _**Are you sure you want to upgrade this module?**_
* **X icon** - for closing the pop-up.
* _**We strongly advise you to upgrade the modules on maintenance mode to avoid any cache issues.**_
* **Cancel** - closes the pop-up.
* **Go to maintenance page CTA** - clicking this will redirect to the Maintenance page, to enable the maintenance mode, so that the webshop visitors will get the notification in the homepage, that something in the webshop is being updated, in case something would fail in code during upgrade process.
* **Upgrade anyway** - initiates the upgrade action instantly and ignores the suggestions from this pop-up.

After the upgrade action, the pop-up will close automatically, and the spinner will be loading instead of the module CTA button in place. Once the spinner finishes the interaction, it will become as **Disabled CTA**, and there will be a success message _Upgrade action on module {module name} succeeded._ in the top-right of the whole page UI. If there are some failures in the module upgrading process, the UI will prompt the error. The pop-up contains [Buttons Basics](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics) and [Buttons Outline](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline) UI Kits.

### Module row blocks for Updates tab

* **Icon**
* **Module title**
* **Versions from the current {arrow to the right symbol} to the newest numeric expression** - it helps visually to orientate, which is the current outdated module version and what will be the next module version after the upgrade finishes.
* **Changelog** - displays the log of the newest version module release. Sometimes, if a module has no changelog in the newest version, there will be _No changelog provided_ placeholder texted.
* **CTA Upgrade button** - this component is from [Dropdowns With Button Split UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split). If the module is outdated, the CTA button can be shown as _Upgrade_. Clicking Upgrade will update the module to the latest version according to the latest module release. There is a **dropdown arrow** near the button - clicking on the arrow, shows additional functions for the certain module:
  * **Uninstall** - uninstalls selected module.
  * **Disable** - disables selected module.
  * **Enable** - enables selected module.
  * **Reset** - resets selected module.
  * **Enable Mobile** - enables the Mobile view for the module.
  * **Disable Mobile** - disables the Mobile view for the module.

## Multistores functionality

This page is Multistores independent (todo link) style page.

The modules, that are displayed in Alerts and Updates tabs, are not maintained and managed separately in different Multistores or Shop groups. All the actions for one module in one Multistore or Shop group will result in the same outcome in the other Multistore or Shop group.
