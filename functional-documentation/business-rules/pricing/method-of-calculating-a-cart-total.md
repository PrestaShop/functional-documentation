---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description



###

#### <mark style="color:blue;">1 - Standard Price and impact price</mark>

<figure><img src="../../../.gitbook/assets/image (172).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow Pricing - Step Standard Price + Impact Price</a></p></figcaption></figure>

#### 2 - Discount Specific price

<figure><img src="../../../.gitbook/assets/image (171).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow Pricing - Discount Specific Price</a></p></figcaption></figure>

#### 3 - Discount Catalog Price Rules

<figure><img src="../../../.gitbook/assets/image (169).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow of pricing - Step Discount Catalog Price Rules</a></p></figcaption></figure>

#### 4 - Discount - Customer Group

<figure><img src="../../../.gitbook/assets/image (170).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Worklfow of pricing - Step Discount Customer Group</a></p></figcaption></figure>



#### 5 - Discount- Cart Rules

<figure><img src="../../../.gitbook/assets/image (173).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow of pricing - Step Discount - Cart rules</a></p></figcaption></figure>



#### 5 - VAT

<figure><img src="../../../.gitbook/assets/image (165).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow of pricing - Step VAT</a></p></figcaption></figure>



#### 6 - Retrieve cost of Shipping

<figure><img src="../../../.gitbook/assets/image (166).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow of pricing - Step Retrieve cost of shipping</a></p></figcaption></figure>



#### 8 - Display of the chart tax excluded for B to B

<figure><img src="../../../.gitbook/assets/image (167).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Worflow of pricing - Step Display of the chart tax excluded</a></p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

1 - X item : Number before item correspond to the number of article in the chart

2 - Cost excluded of items : Sum of prices tax excluded of each product in the chart

3 - Shipping : Cost tax excluded of shipping + Handling charges

4 - Total (tax excl) : Sum of 1 and 2

6 - Taxes : Sum of rounding of TVA



To calculate VAT, first group the excluded tax costs by VAT value, round each one and then add them together. Consider :

* a product A (excluding VAT) of 5.221 euros taxed at 20%, quantity 4
* a product B HT of 2.506 euros taxed at 10%, quantity 2
* a product C HT of 6.220 euros taxed at 20%, quantity 3
* a product D HT of 3.515 euros taxed at 10%, quantity 1

We combine products taxed at 20% and those taxed at 10%, as follows

* a product A HT of 5.221 euros taxed at 20%, quantity 4
* a product C HT of 6.220 euros taxed at 20%, quantity 3
* a product B HT of 2.506 euros taxed at 10%, quantity 2
* a product D HT of 3.515 euros taxed at 10%, quantity 1

We calculate the prices of the products taxed at 20% according to the type of rounding (let's use line rounding for the example): 5.221 \* 4 = 20.884 rounded 20.88 6.220 \* 3 = 18.66 rounded 18.66 Sum them up: 20,88 + 18,66 = 39,54

Calculate the prices of products at 10% before tax according to the type of rounding (let's use line rounding for the example): 2.506 \* 2 = 5.012 rounded to 5.01 3.515 \* 1 = 3.515 rounded to 3.52 5,01 + 3,52 = 8,53

Calculate VAT at 20%: 0.20 \* 39.54 = 7.908 rounded up to 7.91

Calculate 10% VAT: 0.1 \* 8.53 = 0.853 rounded up to 0.85

This means a fair tax for the products at : 7,91 + 0,85 = 8,76



The shipping and handling tax is added to this: Consider :

* shipping at 20 euros, excluding tax, and VAT at 10
* handling at 2 euros We calculate the shipping VAT: 0,1 \* 20 = 2 Calculate the handling VAT: 0,1 \* 2 = 0,2

For a total tax of : 8,76 + 2 + 0,2 = 10.96

Explain the chosen price rounded off in relation to currency or number of digits after the decimal point in BO (case of petrol) to be parameterized

#### 8 - Display of the chart tax included for B to C

<figure><img src="../../../.gitbook/assets/image (168).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflof of pricing - Step display of the chart tax included</a></p></figcaption></figure>



#### Rules of calculation for cart rules

During the process of pricing you have to check [Edit or add Cart Rule](../../ux-ui/back-office/sell/catalog/discounts/edit-or-add-cart-rule.md#code) for following rules

MR\_Pricing\_calc\_001 : If field [Code ](../../ux-ui/back-office/sell/catalog/discounts/edit-or-add-cart-rule.md#code)in cart rules is blank, the rule will automatically be applied to benefiting customers. (MOCCT-008)

MR\_Pricing\_calc\_002 : If field Code in cart rules is filled, the discount will be apply only if the code has been added in the chart.(MOCCT-008)

MR\_Pricing\_calc\_003 : [Status](../../ux-ui/back-office/sell/catalog/discounts/edit-or-add-cart-rule.md#status). Apply the cart rules if Status is "Yes".If Status is "No" the cart Rule is not applied (MOCCT-009)

MR\_Pricing\_calc\_004 : [Priority behavior](../../ux-ui/back-office/sell/catalog/discounts/edit-or-add-cart-rule.md#priority-behavior) (MOCCT-011)

~~MR\_Pricing\_calc\_005 :~~ [~~Partial use~~](../../ux-ui/back-office/sell/catalog/discounts/edit-or-add-cart-rule.md#partial-use-switch-toggle-button-behavior) ~~The price of an item after prorata discount for an amount could not be lower than 0.~~

~~Amount of the second voucher :~~

~~If the amount discount is included : sum of product prices taxes included before discount - Sum of products prices taxes included after discount.~~

~~If the amount discount is excluded : sum of product prices taxes excluded before discount - Sum of products prices taxes excluded after discount.~~
