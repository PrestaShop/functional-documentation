# New & Experimental Features

## Description

This page allows to try any new features on the shop.

<figure><img src="../../../../../.gitbook/assets/Screenshot 2022-12-07 at 16-49-52 New &#x26; Experimental Features • PrestaShop.png" alt=""><figcaption></figcaption></figure>

## Components description

* Enabled/disabled toggle switch
* [Help button](../../../common-components/help-button.md)
* [Save button](../../../common-components/save-button.md)&#x20;

## New features block

Displays an informative message - "New features are available. Feel free to try them out!".

### New product page - single store

| Description              | Value                                                                                                                  | Error message |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------- | ------------- |
| Mandatory                | No                                                                                                                     | -             |
| Allowed/Forbidden values | Enabled/Disabled                                                                                                       | -             |
| Default value            | Disabled                                                                                                               |               |
| Help text                | "This page benefits from increased performance and includes new features such as a new combination management system." | -             |

### Experimental features

| Description              | Value                                                                                                                                                                                                                                                                                                                                                              | Error message |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| Mandatory                | No                                                                                                                                                                                                                                                                                                                                                                 | -             |
| Allowed/forbidden values | Enabled/Disabled                                                                                                                                                                                                                                                                                                                                                   | -             |
| Default value            | Disabled                                                                                                                                                                                                                                                                                                                                                           | -             |
| Help text                | <p>"Testing a feature before its official release can be exciting. However, you must be aware of the potential risks of such experiments:</p><ul><li>Experimental features are still under development. Enabling them could therefore have unintended consequences and cause data loss.</li><li>In any case, you should never experiment in production."</li></ul> | -             |
| Tool tips                | "Access the new product page, even in a multistore context. This is a work in progress and some features are not available."                                                                                                                                                                                                                                       | -             |

## Behavior descriptions

### New features

Has a toggle switch - "New features are available. Feel free to try them out!". When shop is single context, the toggle switch becomes available to toggle either for enabled or disabled. When shop is in multi shop context, the field becomes impossible to edit and save.

#### Save call to action

User saves the toggle selection to enable or disable new features for a new product page.

### Experimental features

Has a toggle switch - "New product page - Multi store". When shop is in single context, the toggle switch is impossible to edit, when the store is in multi shop context, it appears as available to edit and save.

#### Save call to action

User saves the toggle selection to enable or disable experimental features for a new product page when shop is in multi context.

## Limitations

"New features" available only in single shop context.

"Experimental features" available only in multi shop context.
