---
description: 'Path from content root : mails/themes/{theme_name}/core/password.html.twig'
---

# password.html.twig

## Basic Scenario

As cusotmer I want receive an email when I update my password after clicking on "password forgotten". to confirm the operation has been correctly updated.

## Accpetance Test

Given that I am on the Log in to your account page ( FO)

When

* i click in “forgot your password” button
* I write my email address & click on “send rest link”
* I receive an email with a link, I click in this link
* I enter my new password on the page that opens and validate.&#x20;

Then i receive an email to confirm the operation has been correctly updated.

