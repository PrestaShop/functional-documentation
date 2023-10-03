---
description: 'Path from content root : mails/themes/{theme_name}/core/outofstock.html.twig'
---

# outofstock.html.twig

## Basic Scenario

As a merchant I want send an email to the customer when the order is on hold because of a stock problem To notify him that them one or more items are currently out of stock and so this may cause a slight delay in your delivery

## Accpetance Test

Given that I am on the order page (B0)&#x20;

When i change the status on one order in “ On backorder (paid) ” or “ On backorder (not paid) ”&#x20;

Then an email is sent to the customer to inform them one or more items are currently out of stock and so this may cause a slight delay in your delivery



<figure><img src="../../../.gitbook/assets/Untitled (18).png" alt=""><figcaption></figcaption></figure>
