# Authorization server management

## Description

This page aims to allow users to manage their authorized applications and API access. It serves as a landing point to manage those objects and give an overview of the state of the applications authorized to use a shop's API.

<img src="../../.gitbook/assets/Capture d’écran 2022-12-29 à 15.05.03.png" alt="" data-size="original">

## Components description

This section MUST describe each component one by one

### A component description

Common components

* [heading-of-the-page.md](../ux-ui/common-components/heading-of-the-page.md "mention")
* [help-button.md](../ux-ui/common-components/help-button.md "mention")
* [pagination.md](../ux-ui/common-components/pagination.md "mention")
* The list element is based on a [table](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--basic)

## Behaviors description

### Workflow

This page is the starting point of 4 workflows :&#x20;

* Creation of an Authorized Application
* Creation of an API Access
* Deletion of an Authorized Application
* Edit of an Authorized Application

### Behavior description

* The creation of an Authorized Application is triggered by clicking on the CTA "Add a new authorized app", making the user leave this page to enter a creation funnel.
* The creation of an API Access is triggered by clicking on the CTA "Add a new API access", making the user leave this page to enter a creation funnel.
* The deletion of an Authorized Application is triggered by clicking on the three dot button of an authorized app entry of the list then clicking on the delete button. It triggers a deletion prompt aiming to confirm the deletion.
* The edition of an Authorized Application is triggered by clicking on the three dot button of an authorized app entry of the list then clicking on the edit button. This leads the user to the edit funnel.

## Error messages

This section MUST list all errors messages / Exceptions for the page / workflow

## Limitations

This section SHOULD list limitations of the page.