---
description: >-
  Path from content root :
  mails/themes/{theme_name}/modules/ps_emailalerts/return_slip.html.twig
---

# return\_slip.html.twig

## Basic Scenario

As merchant I want to receive a message if the customer wants to return one or more products in order to process the request as quickly as possible.

## Accpetance Test

⚠️Before this test you have to be sure that on the Merchandise Returns page

* Enabled returns active

Given i am in “ order history and details” page (FO)&#x20;

When

* I click on “ details” button of the order i want to return
* I select the product & the quantity
* I write why i want to return the product in “ merchandise return” fields&#x20;

Then As merchant i receive an email who informs me of the customer's request



<figure><img src="../../../.gitbook/assets/Untitled (31).png" alt=""><figcaption></figcaption></figure>

