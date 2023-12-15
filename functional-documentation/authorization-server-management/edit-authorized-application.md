# Edit Authorized application

## Description

This page is the one-step funnel to edit an authorized application of a PrestaShop shop.&#x20;

![](<../../.gitbook/assets/Capture d’écran 2022-12-30 à 11.39.49.png>)

## QA

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/advanced-parameters/authorization-server.html)

## Components description

Common components

* [heading-of-the-page.md](../ux-ui/common-components/heading-of-the-page.md "mention")
* [help-button.md](../ux-ui/common-components/help-button.md "mention")
* A "Save" [button](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)



**App name text field**

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">"Please complete this field" with bowser notification</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All character is allowed</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>50</td><td align="center">An unexpected error occurred. [Doctrine\DBAL\Exception\DriverException code 0]: An exception occurred while executing 'UPDATE ps_authorized_application SET name = ? WHERE id_authorized_application = ?' with params ["<strong>[your text]</strong>", 1]: SQLSTATE[22001]: String data, right truncated: 1406 Data too long for column 'name' at row 1</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>

**Description text field**

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All character is allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>0</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>no limit</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>



## Behaviors description

### Workflow

This page only serves the Authorized application edition workflow in which the user fills at least the application name before validating the form.

### Behavior description

* If the user input an unauthorized character they won't be able to validate the form to edit the  authorized application
* When clicking on save the page detailling the edited authorized application is opened ->[authorized-application-details.md](authorized-application-details.md "mention")

## Error messages

## Limitations

This page only serves the edition of authorized applications
