---
description: 'Path from content root : mails/themes/{theme_name}/core/account.html.twig'
---

# account.html.twig

## Basic Scenario

As an customer I want receive an email when a create a customer account to let me know that my account has been created.

## Accpetance Test

#### Acceptance test 1 - Create a account (FO)&#x20;

Given that I am on “log in to your account” page

&#x20;When

1. I click the "No account ? Create one here" button
2. In “create an account” I fill in all the information
3. I must select “ CG” et “Customer data privacy”
4. I click in “ save” button&#x20;

Then I must receive an email confirming that my account has been created

#### Acceptance test 2 - During Order (FO)&#x20;

Given that I am in “ personal information” ( Step 1: Payment) page

When

1. I fill in all the information and the most important is the password. without the password the account will not be created
2. I must select “ CG” et “Customer data privacy”
3. I click in “ continue” button

Then I must receive an email confirming that my account has been created



<figure><img src="../../../.gitbook/assets/Untitled (3) (1).png" alt=""><figcaption></figcaption></figure>
