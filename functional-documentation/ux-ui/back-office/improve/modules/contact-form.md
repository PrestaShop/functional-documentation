# Contact form (contactform)

## Description

The page consists of 2 toggle switches that can be enabled or disabled. The module by default provides an informative message with a link: at the top of the page: "For even more security on your website forms, consult our Security & Access modules category on the [PrestaShop Addons Marketplace](https://addons.prestashop.com/en/429-website-security-access?utm\_source=back-office\&utm\_medium=native-contactform\&utm\_campaign=back-office-EN\&utm\_content=security)".

![](<../../../../../.gitbook/assets/Screenshot 2022-05-25 at 14-13-03 Module Manager • test.png>)

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/modules/contactform.html)

## Components description

2 components are described below

#### Send confirmation email to your customers description (toggle switch)

| Description               | Value                                                                                                                                                                                                                     | Error message |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| Mandatory                 | Yes                                                                                                                                                                                                                       | -             |
| Allowed/Forbidden values  | -                                                                                                                                                                                                                         | -             |
| Default value             | Disabled                                                                                                                                                                                                                  | -             |
| Help text                 | "Choose Yes and your customers will receive a generic confirmation email including a tracking number after their message is sent. Note: to discourage spam, the content of their message won't be included in the email." | -             |

#### Receive customers' messages by email (toggle switch)

| Description              | Value                                                                                   | Error message |
| ------------------------ | --------------------------------------------------------------------------------------- | ------------- |
| Mandatory                | Yes                                                                                     | -             |
| Allowed/Forbidden values | -                                                                                       | -             |
| Default value            | Disabled                                                                                | -             |
| Help text                | "By default, you will only receive contact messages through your Customer service tab." | -             |

## Behaviors description



#### Top buttons - Call to action

1. **Back**

When pressed redirect back to the module manager (Modules > Module manager).

**2. Translate**

When pressed, a pop-up opens with a drop-down, from which it is possible to select one of the languages installed on the shop to translate the module.

**3. Check update**

Checks for updates on the module.

**4. Manage hooks**

When pressed redirects to the (Design > Positions).

## Error messages

No error messages are present in this page.

## Limitations

No limitations are present in this page.
