---
description: >-
  Path from content root :
  mails/themes/{theme_name}/core/order_canceled.html.twig
---

# order\_canceled.html.twig

## Basic Scenario

As merchant I want send an email to the customer when i cancel his order To to warn him that the change

## Accpetance Test

Given that I am on the order page (BO)

&#x20;When i change the status on one order in “ Cancel”&#x20;

Then an email is sent to the customer to inform them that their order has been cancelled.



<figure><img src="../../../.gitbook/assets/Untitled (13).png" alt=""><figcaption></figcaption></figure>

