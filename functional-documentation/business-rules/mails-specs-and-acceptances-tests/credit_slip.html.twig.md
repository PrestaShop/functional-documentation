---
description: 'Path from content root : mails/themes/{theme_name}/core/credit_slip.html.twig'
---

# credit\_slip.html.twig

## Basic Scenario

As an merchant I want receive an email when i generate a credit slip in case of product return to let me know that the credit slip is available



## Accpetance Test

#### Acceptance 1: Partial Refund (BO)

&#x20;Given that your are on “customer" page

When

1. Selects a customer who has made purchases
2. In order table click in “ view” button on action colone.
3. Click on “partial refund” button
4. Selects the quantity to be refund
5. Check the box "Generate a Credit Slip." 4.Click in “partial refund” button&#x20;

Then you must receive an email confirming that your We have generated a credit slip in your name for order with the reference \[1]{order\_name}\[/1]

#### Acceptance 2: Return products (BO)&#x20;

Given that your are on “customer" page&#x20;

When

1. Selects a customer who has made purchases
2. In order table click in “ view” button on action colone.
3. Click on “return products” button
4. Selects the quantity to be return
5. Check the box "Generate a Credit Slip." 4.Click in “return products” button&#x20;

Then you must receive an email confirming that your We have generated a credit slip in your name for order with the reference \[1]{order\_name}\[/1]



<figure><img src="../../../.gitbook/assets/Untitled (6).png" alt=""><figcaption></figcaption></figure>
