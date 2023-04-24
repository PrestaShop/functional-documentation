---
description: This section is the back office settings of the module Brand list
---

# Brand list

## Description

![](<../../../../../.gitbook/assets/Screenshot 2022-05-23 at 17-56-43 Module Manager • test.png>)

### QA&#x20;

[Link to test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/catalog/brands-and-suppliers/brands.html)

### Front-Office

The module when enabled displays list of brands possible on the shop.

## Components description

2 Components are present within the module settings:

* Type of display&#x20;

| Description              | Value                             | Error message |
| ------------------------ | --------------------------------- | ------------- |
| Mandatory                | Yes                               | -             |
| Allowed/Forbidden values | Use plain text or drop-down field | -             |
| Help text                | -                                 | -             |

* Number of elements to display

| Description              | Value                           | Error message |
| ------------------------ | ------------------------------- | ------------- |
| Mandatory                | No                              | -             |
| Allowed/Forbidden values | Everything is allowed           | -             |
| Help text                | "Only apply in plain-text mode" | -             |

## Workflow

#### Top buttons - Call to action

1. **Back**

When pressed redirect back to the module manager (Modules > Module manager]\(\{{\<ref "../view-module-manager.md">\}} "View module manager")).

**2. Translate**

When pressed, a pop-up opens with a drop-down, from which it is possible to select one of the languages installed on the shop to translate the module.

**3. Check update**

Checks for updates on the module.

**4. Manage hooks**

When pressed redirects to the (Design > Positions]\(\{{\<ref "../../back-office/design/positions/view-positions.md">\}} "View positions")).

2 Input fields are present in this section:

1. Type of display

This is a mandatory drop-down list, by default it is set to "Use a plain-text list". The other option to choose is: "Use a drop-down list".

&#x20; 2\.  Number of elements to display

This is a number input, by default it has the number: "16". Has a help text below: "Show the prices of the products displayed in the block.". Only numbers are allowed, trying to save with any other characters will result in error: [https://github.com/PrestaShop/PrestaShop/issues/28453](https://github.com/PrestaShop/PrestaShop/issues/28453)

#### Save - Call to action

* If all fields are input correctly, when pressed will show: "Settings updated". If some of the fields are incorrect or empty, will show an error according to the mistake.

## Configuration

This section has a checkbox for:

* Activate module for this shop context: all shops.

By default the checkbox is marked.

## Error messages

No error messages are present for this module, only a message "Settings updated." when settings are changed.B
