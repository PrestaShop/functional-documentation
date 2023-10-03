---
description: >-
  Path from content root :
  mails/themes/{theme_name}/modules/ps_emailsubscription/newsletter_verif.html.twig
---

# newsletter\_verif.html.twig

## Basic Scenario

As as merchant I want to check the email address of customers who subscribe to the newsletter To avoid sending mail if the address doesn't work

## Accpetance Test

⚠️Before this test you have to be sure that on the Newsletter subscription module

* Would you like to send a verification email after subscription is active
* Would you like to send a confirmation email after subscription is active

Given that I am on the any page of the FO&#x20;

When

1. i write my adress e-mail in “ get our latest news and specoal sales” and click on “suscribe” button&#x20;

ThenI receive an e-mail to confirm my adress email.



<figure><img src="../../../.gitbook/assets/Untitled (27).png" alt=""><figcaption></figcaption></figure>



