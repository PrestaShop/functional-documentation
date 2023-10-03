---
description: >-
  Path from content root :
  mails/themes/{theme_name}/core/download_product.html.twig
---

# download\_product.html.twig

## Basic Scenario

As merchant I want to send an e-mail with the virtual product when payment is confirmed to he customer who placed the order

## Accpetance Test

Given that I am on the Order page (BO)\
When I changeorder satus for one virtual product:

* Payment accepted
* Remot payment accepted&#x20;

Then an email is send to the customer with the product virtual



<figure><img src="../../../.gitbook/assets/Untitled (7).png" alt=""><figcaption></figcaption></figure>
