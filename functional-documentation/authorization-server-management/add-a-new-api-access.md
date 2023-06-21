# Add a new API Access

## Description

This page is the one-step funnel to add a new API Access to a PrestaShop shop.&#x20;

![](<../../.gitbook/assets/Capture d’écran 2022-12-30 à 14.00.24.png>)

## Components description

This section MUST describe each component one by one

### A component description

Common components

* [heading-of-the-page.md](../ux-ui/common-components/heading-of-the-page.md "mention")
* [help-button.md](../ux-ui/common-components/help-button.md "mention")
* A "Save" [button](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)
* A [dropdown](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--menu-example) to select the associated Authorized application
* API access name text field

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Letters, dot (.) and dash (-) characters allowed</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Default value</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>This name serves as the API Access' client ID</td><td align="center">-</td><td></td></tr></tbody></table>

* A Scope selector

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Help text</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Tool tips text</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>Allows the user to select if the API Access is authorized to one or multiple scope</td><td align="center">-</td><td></td></tr></tbody></table>



## Behaviors description

### Workflow

This page only serves the API Access creation workflow in which the user fills the mandatory fields validating the form.

### Behavior description

* If the user input an unauthorized character they will get a focus on the name field when trying to validate the form to create the  API Access
* If the user does'nt input an associated authorized application they will get a focus on the associated application field when trying to validate the form
* If the user doesn't input at least a scope they will get a focus on the scope field when trying to validate the form
* When the form is validated the user is taken to [authorized-application-details.md](authorized-application-details.md "mention") and a green alert is displayed with the API Access' client secret

## Error messages

## Limitations

This page only serves the creation of API Access
