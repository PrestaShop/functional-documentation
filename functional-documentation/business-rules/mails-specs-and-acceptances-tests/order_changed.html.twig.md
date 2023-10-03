---
description: >-
  Path from content root :
  mails/themes/{theme_name}/core/order_changed.html.twig
---

# order\_changed.html.twig

## Basic Scenario

As merchant I want send an email to the customer when i change his order To inform his of the change

## Accpetance Test

#### Acceptance test 1 - Edit a product

Given that I am on the Order page

When

* I select the order i want change
* I click on “ Edit” button
* I change the quantity&#x20;

Then the customer receive an email to inform his of the change

#### Acceptance test 2 - add product&#x20;

Given that I am on the Order page

&#x20;When

* I select the order i want change
* I click on “ Add product” button
* I write the product i want add & i click on “add” button&#x20;

Then the customer receive an email to inform his of the change



<figure><img src="../../../.gitbook/assets/Untitled (30).png" alt=""><figcaption></figcaption></figure>

