# New products block

## Description

The page consists of 2 input fields that can have their own values inside.

![](<../../../../../.gitbook/assets/Screenshot 2022-05-31 at 16-46-05 Module Manager • test (1).png>)

## Components description

#### 2 Components are present within the module settings:

* Products to display

| Description              | Value                                                                         | Error message     |
| ------------------------ | ----------------------------------------------------------------------------- | ----------------- |
| Mandatory                | No                                                                            | -                 |
| Allowed/Forbidden values | Only numbers are allowed, entering any other symbols will result to an error. | "Invalid number." |
| Default value            | 8                                                                             | -                 |
| Help text                | "Define the number of products to be displayed in this block."                | -                 |

* Number of days for which the product is considered 'new'

| Description              | Value                                                                         | Error message     |
| ------------------------ | ----------------------------------------------------------------------------- | ----------------- |
| Mandatory                | No                                                                            | -                 |
| Allowed/Forbidden values | Only numbers are allowed, entering any other symbols will result to an error. | "Invalid number." |
| Default value            | 20                                                                            | -                 |
| Help text                | -                                                                             | -                 |



## Workflow

#### Top buttons - Call to action

1. **Back**

When pressed redirect back to the module manager (Modules > Module manager).

**2. Translate**

When pressed, a pop-up opens with a drop-down, from which it is possible to select one of the languages installed on the shop to translate the module.

**3. Check update**

Checks for updates on the module.

**4. Manage hooks**

When pressed redirects to the (Design > Positions).

**2 Input fields are present in the section below for the main configuration:**

1. Products to display

This is an input field for a number of products which will be displayed, by default the number is set to "8". Only numbers can be entered in this field.

&#x20; 2\.  Number of days for which the product is considered 'new'

This is an input field for the number of days for which the product is considered 'new' in the shop. The default number set is "20". Only numbers can be entered in this field.

## Configuration

This section has a checkbox for:

* Activate module for this shop context: all shops.

By default the checkbox is marked.

## Error messages

1 error message can be found, when an incorrect value is being saved, it will show an error:

* "Invalid number."
