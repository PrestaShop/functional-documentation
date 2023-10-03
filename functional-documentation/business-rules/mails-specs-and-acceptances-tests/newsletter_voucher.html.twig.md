---
description: >-
  Path from content root :
  mails/themes/{theme_name}/modules/ps_emailsubscription/newsletter_voucher.html.twig
---

# newsletter\_voucher.html.twig

## Basic Scenario

As a merchant I want the customer to receive, in addition to an e-mail confirmation of his subscription to the newletter, a voucher that I have parrametered beforehand using the ps\_emailsubscription module. to encourage customers to place an order

## Accpetance Test

⚠️Before this test you have to be sure that on the Newsletter subscription module

* fields “ Welcome voucher code” is filled with a an active voucher reference
* Would you like to send a verification email after subscription is active
* Would you like to send a confirmation email after subscription is active

Given that I am on the any page of the FO&#x20;

When

1. i write my adress e-mail in “ get our latest news and specoal sales” and click on “suscribe” button
2. I receive an e-mail to confirme my adress email. In this email i click on the link to confirm my request&#x20;

Then I receive an email with the voucher





<figure><img src="../../../.gitbook/assets/Untitled (26).png" alt=""><figcaption></figcaption></figure>

