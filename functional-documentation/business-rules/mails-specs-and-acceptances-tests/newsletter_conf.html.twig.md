---
description: >-
  Path from content root :
  mails/themes/{theme_name}/modules/ps_emailsubscription/newsletter_conf.html.twig
---

# newsletter\_conf.html.twig

## Basic Scenario

As a Customer I want receive an email when i confirm my email adress after subscribing to the newletter to cofirm my inscription on the newsletter

## Accpetance Test

⚠️Before this test you have to be sure that on the Newsletter subscription module

* Would you like to send a verification email after subscription is active
* Would you like to send a confirmation email after subscription is active

Given that I am on the any page of the FO When

1. i write my adress e-mail in “ get our latest news and specoal sales” and click on “suscribe” button
2. I receive an e-mail to confirm my adress email. In this email i click on the link to confirm my request&#x20;

Then I receive an email to cofirm my inscription





