# Authorized application details

## Description

This page is the one-step funnel to add a new authorized application to a PrestaShop shop.&#x20;

![](<../../../../../.gitbook/assets/Capture d’écran 2022-12-30 à 11.49.30.png>)

## Components description

This section MUST describe each component one by one

### A component description

Common components

* [heading-of-the-page.md](../../../common-components/heading-of-the-page.md "mention")
* [help-button.md](../../../common-components/help-button.md "mention")
* A "Edit authorized application" [button](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)
* A panel displaying the name and the description of the authorized application
* A [table](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--basic) listing the API Accesses associated to the authorized application&#x20;
  * Each element of the list contains :&#x20;
    * A [switch](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) to activate or deactivate the API Access
    * An edit icon button
    * A delete icon button



## Behaviors description

### Workflow

This page displays the Authorized application details and is a starting point of four workflows :

* Edition of the Authorized application
* Edition of an API Access
* Deletion of an API Access
* View details of an API Access

### Behavior description

* The edition of an Authorized Application is triggered by clicking on the CTA. This leads the user to the edit funnel.
* The deletion of an API Access is triggered by clicking on the deletion icon button on an API Access entry of the list. It triggers a deletion prompt aiming to confirm the deletion.
* The edition of an API Access is triggered by clicking on the edition icon button on an API Access entry of the list. This leads to the user to the edit funnel [edit-api-access.md](edit-api-access.md "mention")
* The user can access [Broken link](broken-reference "mention")by clicking on an entry of the API Access list

## Error messages

## Limitations
