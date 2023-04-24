# Email theme

## Description

This page allows managing the email themes.

<figure><img src="../../../../../.gitbook/assets/image (29) (1) (1).png" alt="Email Theme User Interface"><figcaption><p>Email Theme User Interface</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon
* [Account icon](../../../common-components/account-icon.md).
* [Shop switcher](../../../common-components/shop-switcher.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).

## The UI elements

### Configuration

#### Select your default email theme dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>modern</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This won't regenerate email templates, it only sets the default email theme for future generation (when a language is installed fore example).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#select-your-default-email-theme-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Save button&#x20;

Behavior link to the behavior

### Generate emails

#### Select your email theme dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>modern</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#select-your-email-theme-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Select your language dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">Please select an item in the list.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder: Language</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Please select an item in the list.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#select-your-language-dropdown-in-generate-emails-block-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Select the theme you want to overwrite dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Core (no theme selected)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>PrestaShop's email templates are stored in the "mails" folder, but they can be overridden by your current theme's own "mail" folder. Using this option enables to overwrite emails from your current theme.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#select-the-theme-you-want-to-overwrite-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Overwrite templates toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>By default, existing email template files are not modified to avoid deleting any modification you may have done. Enable this option to force the overwrite.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#overwrite-templates-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Generate emails button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>By default, existing email template files are not modified to avoid deleting any modification you may have done. Enable this option to force the overwrite.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#overwrite-templates-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Translate emails

#### Select your language dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">Please select an item in the list.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder: Language</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Please select an item in the list.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#select-your-language-dropdown-in-translate-emails-block-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Email themes

List of email themes in your PrestaShop.\
Each email theme can be previewed by pressing the button **Preview**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="email-theme.md#select-your-language-dropdown-in-translate-emails-block-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description



### Configuration

#### Select your default email theme dropdown behavior

This is a dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) to select default email theme. It lists all the emails in the repo/email.\
By default,

* modern
* classic

are installed.

#### Save

The **button Save (**[save-button.md](../../../common-components/save-button.md "mention") UI) when is pressed, then the theme selected in **Select your default email theme dropdown** is used as the default email theme of the PrestaShop.

What happened when the default theme is changed without being edited?



### Generate emails block behavior

This block contains these elements:

* [Select your email theme dropdown](email-theme.md#select-your-email-theme-dropdown-behavior)
* [Select your language dropdown](email-theme.md#select-your-language-dropdown-in-generate-emails-block-behavior)
* [Select the theme you want to overwrite dropdown](email-theme.md#select-the-theme-you-want-to-overwrite-dropdown-behavior)
* [Overwrite templates toggle switch](email-theme.md#overwrite-templates-toggle-switch-behavior)
* [Generate emails button](email-theme.md#generate-emails-button-behavior)

### Select your email theme dropdown behavior

This is a dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) listing all the user email themes. By default,

* modern
* classic

are installed.

### Select your language dropdown in Generate emails block behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) to select language for emails. This dropdown shows languages that are enabled in International -> Localization -> Languages page.

### Select the theme you want to overwrite dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) to select theme that should be overwritten. It has these options:&#x20;

* Core (no theme selected)
* classic

### Overwrite templates toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that enables or disables email templates overwriting.&#x20;

### Generate emails button behavior

This is CTA button with mail icon ([Buttons with icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), once clicked it generates emails template changes and appears green notification message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)): _Successfully generated email templates for theme 'theme name' with locale 'language ISO code'._\
When hover mouse pointer on it, button color changes.

### Title of Translate emails block behavior

It contains title and mail icon.

### Translate emails block behavior

This block contains these elements:

* [Select your language dropdown](email-theme.md#select-your-language-dropdown-in-translate-emails-block-behavior)
* [Translate emails button](email-theme.md#translate-emails-button-behavior)

### Select your language dropdown in Translate emails block behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) to select language for translation. This dropdown shows languages that are enabled in International -> Localization -> Languages page.

### Translate emails button behavior

This is CTA button with mail icon ([Buttons with icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), once clicked it opens International -> Translations -> Email Body translation to selected language page.\
When hover mouse pointer on it, button color changes.

### Email themes block behavior

This block contains list of email themes. By default there are two themes: classic and modern. Each theme is shown with these elements in the list:

* Name - shows theme name.
* Actions - view icon, once clicked opens that theme Preview Theme page.

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.

