---
description: 'Path from content root : mails/themes/{theme_name}/core/refund.html.twig'
---

# refund.html.twig

## Basic Scenario

As a merchant I want recive an email when when to have stock available all the time

## Accpetance Test

Given that I am on the Stock manaagement page (BO)&#x20;

When

1. select a product to test, exemple a pull
2. in the "edit quantity" field, change the quantity to negative&#x20;

Then i must receive an email to informe me “There are now less than 3 items in stock.” and explains what I need to do to bring my stock up to date.



<figure><img src="../../../.gitbook/assets/Untitled (21).png" alt=""><figcaption></figcaption></figure>
