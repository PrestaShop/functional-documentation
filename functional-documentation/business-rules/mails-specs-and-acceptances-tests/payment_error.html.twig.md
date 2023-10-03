---
description: >-
  Path from content root :
  mails/themes/{theme_name}/core/payment_error.html.twig
---

# payment\_error.html.twig

## Basic Scenario

As merchant I want to send an email to the customer when there are a problem with him payement To notify him we encountered an error while processing him payment

## Accpetance Test

Given that I am on the order page (BO)

When i change the status on one order in “ payment error ”

Then an email is sent to the customer to inform him we encountered an error while processing him payment



<figure><img src="../../../.gitbook/assets/Untitled (20).png" alt=""><figcaption></figcaption></figure>
