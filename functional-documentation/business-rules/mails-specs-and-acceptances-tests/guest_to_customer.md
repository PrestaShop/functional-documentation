---
description: >-
  Path from content root :
  mails/themes/{theme_name}/core/guest_to_customer.html.twig
---

# guest\_to\_customer

## Basic Scenario

As a merchant or customer I want receive an email when the guest account has been turned into a customer account to confirm the change of status account

## Accpetance Test

#### Acceptance test 1 (FO)&#x20;

Given that I am in “ personal information” ( Step 1: Payment) page

&#x20;When

1. I fill all informations on this page without the password In “order as a guest” colone and i click on “cotinue” button.
2. I fill in all the information required for payment ( step 2, 3, 4) and validate the payment.
3. On the order summary page, at the end of the page, enter a password in the "define your password" field and click on "create an account".&#x20;

Then I must receive an email confirming that my guest account has been turned into a customer account

#### Acceptance test 2 (BO)

Given that I am on the Manage your Customer page ( Custormer)

When

1. I oppen one customer field
2. In the top right-hand box, click on “ transform to a customer account” button ( blue button)&#x20;

Then The customer must receive an email confirming that his guest account has been turned into a customer account



<figure><img src="../../../.gitbook/assets/Untitled (10).png" alt=""><figcaption></figcaption></figure>



