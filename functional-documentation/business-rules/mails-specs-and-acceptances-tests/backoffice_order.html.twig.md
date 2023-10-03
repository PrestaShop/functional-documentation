---
description: >-
  Path from content root :
  mails/themes/{theme_name}/core/backoffice_order.html.twig
---

# backoffice\_order.html.twig

## Basic Scenario

As a merchant I want to warn my customer that I've placed an order for him in his place To he can be informed and pay easily

## Accpetance Test

Given that I am on the Create order page (BO)&#x20;

When

1. Choose the customer in “customer”
2. Choose product in “ Basket”
3. Select payment methode
4. Select Order Status
5. Click in dropdow “more action” and select send pre-filled order the customer by email&#x20;

Then an email is sent to the customer to inform “A new order has been generated on your behalf”



<figure><img src="../../../.gitbook/assets/Untitled (4).png" alt=""><figcaption></figcaption></figure>
