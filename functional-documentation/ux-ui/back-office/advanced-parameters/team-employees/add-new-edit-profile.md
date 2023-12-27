# Add new / edit profile

### Description

This page allows to create new profile or edit changes in profile.

<figure><img src="../../../../../.gitbook/assets/image (92).png" alt="Add new / edit profile User interface"><figcaption><p>Add new / edit profile User interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/advanced-parameters/team/profiles/bo-advanced-parameters-team-roles-crud.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md).
* [Search input](../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md).
* [Shop switcher](../../../common-components/shop-switcher.md).
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../common-components/help-button.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Cancel button](../../../common-components/cancel-button.md) -  [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* [Language dropdown for input fields](../../../common-components/language-dropdown-for-input-fields.md).

## The UI elements

### Name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">The field name is required at least in your default language.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>32</td><td align="center">This field cannot be longer than 32 characters - Language: (chosen language for input)</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-profile.md#name-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Avatar input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Placeholder: Choose file(s)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>No file chosen</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="add-new-edit-profile.md#avatar-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Notification behavior

This is notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) that is shown if multistore is enabled on the shop. This notification message is: \
_Note that this feature is available in all shops context only. It will be added to all your stores._

### Title of Profile behavior

It contains title and 2 people icon.

### Name input behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter profile name.

### Avatar input behavior

This is a field ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) for uploading an avatar, it has a button "Browse", when pressed opens a window for selecting an avatar.

## Multistores functionality

This page is available in all shops context only.
