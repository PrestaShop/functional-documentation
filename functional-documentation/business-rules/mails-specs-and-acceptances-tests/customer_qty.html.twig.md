---
description: >-
  Path from content root :
  mails/themes/{theme_name}/modules/ps_emailalerts/customer_qty.html.twig
---

# customer\_qty.html.twig

## Basic Scenario

As costumer I want to be notified when a product I want is back in stock to that I can buy it as soon as possible

## Accpetance Test

⚠️Before this test you have to be sure that on the mail alerts module

* Product availability is active
* Order edit is active&#x20;

Given that I am on the any product page of the FO - only for product out-of-stock&#x20;

When

* As customer, i write my email adress in “notify me when available”
* As merchant, i add stock to the product in BO&#x20;

Then As customer i receive an email to informe me “ Good news, this item is back in stock”



<figure><img src="../../../.gitbook/assets/Untitled (28).png" alt=""><figcaption></figcaption></figure>



