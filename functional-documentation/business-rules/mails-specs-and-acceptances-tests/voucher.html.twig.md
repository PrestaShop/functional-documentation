---
description: 'Path from content root : mails/themes/{theme_name}/core/voucher.html.twig'
---

# voucher.html.twig

## Basic Scenario

As merchant I want send an email with all informations about voucher when i create one for a customer to inform him of the voucher he has at his disposal, so that he can use it easily

## Accpetance Test

#### Acceptance test 1 : Voucher - Partial Refund (BO)&#x20;

Given that your are on “customer" page&#x20;

When

1. Selects a customer who has made purchases
2. In order table click in “ view” button on action colone.
3. Click on “partial refund” button
4. Selects the quantity to be refund
5. Check the box "Generate a voucher” 4.Click in “partial refund” button&#x20;

Then the costomer must receive an email to informe him a voucher has been generated in his name

#### Acceptance test 2 : Voucher - Return products (BO)&#x20;

Given that your are on “customer" page&#x20;

When

1. Selects a customer who has made purchases
2. In order table click in “ view” button on action colone.
3. Click on “return products” button
4. Selects the quantity to be refund
5. Check the box "Generate a voucher” 4.Click in “Standard refund” button&#x20;

Then the costomer must receive an email to informe him a voucher has been generated in his name

⚠️ When creating a voucher on the "basket rules" page, the email is not sent.





<figure><img src="../../../.gitbook/assets/Untitled (25).png" alt=""><figcaption></figcaption></figure>

