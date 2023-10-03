---
description: 'Path from content root : mails/themes/{theme_name}/core/order_conf.html.twig'
---

# order\_conf.html.twig

## Basic Scenario

As an customer (FO), I want receive an email when i make an order to let me know that my order is confirmed

## Accpetance Test

⚠️Before this test you have to be sure that on the mail alerts module

* New order active

Given that I am on the order page ( Step 4: Payment) (BO)&#x20;

When

* I select my payment method
* I accept Terme & condition
* I click the "Place Order" button&#x20;

Then I must receive an email confirming that my order to be place successfully



<figure><img src="../../../.gitbook/assets/Untitled (14).png" alt=""><figcaption></figcaption></figure>
