# Editing customer

## Description

This page contains the form to edit an existing customer in the BO.

[Customers related tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers.html)

<figure><img src="../../../../../.gitbook/assets/Capture d’écran du 2022-12-29 15-13-01.png" alt=""><figcaption></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/customers.html)

## Components description

### Common components

* [heading-of-the-page.md](../../../common-components/heading-of-the-page.md "mention")
* [help-button.md](../../../common-components/help-button.md "mention")

### Components

* A [form](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) composed of different types of fields :&#x20;
  * 1 radio button set of 2 buttons
  * 4 text input fields
  * 1 date picker split into 3 dropdown selectors
  * 2 toggles
  * 1 checkbox table with multiple entries
  * 1 dropdown selector linked to the checkbox table
  * 2 buttons

## Behaviors description

### Workflow

The **Creating a new customer** page purpose is to edit an existing customer using the BR [update-a-customer.md](../../../../business-rules/customers/update-a-customer.md "mention"). As a result this page only has 1 workflow

The user updates an customer and must ensure that at least the mandatory fields are filled :&#x20;

* First name (Text input)
* Last name (Text input)

| Description              | Value                                                                                       | Error message |
| ------------------------ | ------------------------------------------------------------------------------------------- | ------------- |
| Mandatory                | Yes                                                                                         | -             |
| Allowed/Forbidden values | Letters and dot (.)                                                                         |               |
| Default value            | -                                                                                           | -             |
| Help text                |                                                                                             | -             |
| Tool tips                |                                                                                             | -             |
| Lower limit              |                                                                                             |               |
| Upper limit              |                                                                                             |               |
| Behavior                 | [update-a-customer.md](../../../../business-rules/customers/update-a-customer.md "mention") |               |

* Email address (Text input)

| Descriptuion             | Value                                                                                       | Error message |
| ------------------------ | ------------------------------------------------------------------------------------------- | ------------- |
| Mandatory                | Yes                                                                                         | -             |
| Allowed/Forbidden values | ​                                                                                           | ​             |
| Default value            | Default value                                                                               | -             |
| Help text                | Help text                                                                                   | -             |
| Tool tips                | Tool tips text                                                                              | -             |
| Lower limit              | ​                                                                                           | ​             |
| Upper limit              | ​                                                                                           | ​             |
| Behavior                 | [update-a-customer.md](../../../../business-rules/customers/update-a-customer.md "mention") |               |

* Group access (checkbox)

| Description              | Value                                                                                       | Error message |
| ------------------------ | ------------------------------------------------------------------------------------------- | ------------- |
| Mandatory                | Yes                                                                                         | -             |
| Allowed/Forbidden values | ​                                                                                           | ​             |
| Default value            | Default value                                                                               | -             |
| Help text                | Help text                                                                                   | -             |
| Tool tips                | Tool tips text                                                                              | -             |
| Lower limit              | ​                                                                                           | ​             |
| Upper limit              | ​                                                                                           | ​             |
| Behavior                 | [update-a-customer.md](../../../../business-rules/customers/update-a-customer.md "mention") |               |

Then validates their creation by hitting the save button. The employee is then redirected to [customers.md](../catalog/customers.md "mention") which displays a success message in a green alert.

TODO : workflow diagram

### Behavior description

* Each mandatory field has its own set of validation rules. These rules are checked upon clicking the save button.
* When the user starts inputting a password :&#x20;
  * A security score bar appears under the field along 2 recommendations :&#x20;
    * The password length (between 8 and 72 characters) & the password strength (Strong)
  * The security score and bar vary from "very weak" to "very strong" depending on the inputted password

## Error messages

* If one of the mandatory text input fields is empty upon clicking the save button a pop-up asking the user to fill the field appears and refocus the user's screen on the empty field&#x20;
* If the user starts inputting a birthdate, the birthdate needs to be complete with a year, a month and a day otherwise it will be considered invalid.
* The user must have at least 1 item checked in the group access checkbox table otherwise when clicking the save button a red alert message is displayed with the text : \
  "A default customer group must be selected in group box."
