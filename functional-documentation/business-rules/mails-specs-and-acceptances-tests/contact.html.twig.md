---
description: 'Path from content root : mails/themes/{theme_name}/core/contact.html.twig'
---

# contact.html.twig

## Basic Scenario

As merchant I want receive an email when a customer send a message to see it as soon as possible

## Accpetance Test

⚠️ Before this test you have to be sure that on the Contact form module

* Send confirmation email to your customers
* Receive customers' messages by email sound activated

Given that I am on the any page of the FO&#x20;

When

* I click in “contact us” button
* I select subject and order reference, i write my email adresse and my message in contact form
* I click in “ send” button&#x20;

Then an email will be sent to the merchant to inform him of the message



<figure><img src="../../../.gitbook/assets/Untitled (32).png" alt=""><figcaption></figcaption></figure>

