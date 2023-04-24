# Edit Authorized application

## Description

This page is the one-step funnel to edit an authorized application of a PrestaShop shop.&#x20;

![](<../../../../../.gitbook/assets/Capture d’écran 2022-12-30 à 11.39.49.png>)

## Components description

This section MUST describe each component one by one

### A component description

Common components

* [heading-of-the-page.md](../../../common-components/heading-of-the-page.md "mention")
* [help-button.md](../../../common-components/help-button.md "mention")
* A "Save" [button](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)
* App name text field

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Letters, dot (.) and dash (-) characters allowed</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>

* Description text field

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Alphanumeric characters and basic special characters allowed</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td></td><td align="center">-</td><td></td></tr></tbody></table>



## Behaviors description

### Workflow

This page only serves the Authorized application edition workflow in which the user fills at least the application name before validating the form.

### Behavior description

* If the user input an unauthorized character they won't be able to validate the form to edit the  authorized application
* When clicking on save the page detailling the edited authorized application is opened ->[authorized-application-details.md](authorized-application-details.md "mention")

## Error messages

## Limitations

This page only serves the edition of authorized applications
