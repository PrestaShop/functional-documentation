---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description



## 1 - Standard Price and impact price

<figure><img src="../../../.gitbook/assets/image (172).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow Pricing - Step Standard Price + Impact Price</a></p></figcaption></figure>

#### It exists 4 types of products&#x20;

<figure><img src="../../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

To calculate the price of a product before the discount :

### B to B

#### For Products with combination :&#x20;

In case of B to B merchant this one will enter in the catalog the retail price (tax excl.) and the impact on price (tax excl.)

&#x20;The retail price (tax incl.) and the impact on price (tax incl.) have to stay empty.

&#x20;_<mark style="color:blue;">Price of product before the discounts = Retail price (tax excl.) and impact price (tax excl).</mark>_&#x20;



<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

#### For the other products&#x20;

In case of B to B merchant this one will enter in the catalog the retail price (tax excl.)&#x20;

&#x20;The retail price (tax incl.) has to stay empty.

_<mark style="color:blue;">Price of product tax excludedc before the discounts = Retail price (tax excl.)</mark>_&#x20;



<figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

### B to C

<mark style="color:red;">Explain why use data inclu not calculate from excluded but from data display</mark>

{% embed url="https://github.com/PrestaShop/PrestaShop/discussions/34262#discussioncomment-7777008" %}

####

#### For Products with combination :&#x20;

In case of B to C merchant this one will enter in the catalog the retail price (tax incl.) and the impact on price (tax incl.)

&#x20;The retail price (tax excl.) and the impact on price (tax excl.) have to stay empty.

&#x20;_<mark style="color:blue;">Price of product tax included before the discounts = Sum the standard price (tax incl.) and impact price (tax incl).</mark>_&#x20;

Standard price = Retail price



<mark style="color:red;">CHANGER LES IMPRIX ECRAN AVEC TAX INCL</mark>

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

#### For the other products&#x20;

In case of B to C merchant this one will enter in the catalog the retail price (tax incl.)&#x20;

&#x20;The retail price (tax excl.) has to stay empty.

_<mark style="color:blue;">Price of product before the discounts = Standard price (tax excl.)</mark>_&#x20;

Standard price = Retail price

<mark style="color:red;">CHANGER LES IMPRIX ECRAN AVEC TAX INCL</mark>

<figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

###

## Rounding 1

Each data displayed in the FO has to be&#x20;

Thanks to a toggle button either by  the number of decimals in the currencies (case 1] or depending on the number of digits after coma in the tab pricing of product (case 2).

Why the second option is interesting ?

Case of gas station for fuel. The price is displayed with three digits after coma event if the payment is with two digits in the case of euros. So for the calculation, the rounding has to be done with three digits.



### Case 1 : Rounding depending on the number of currency decimals used in the context of the FO and configured in the BO.

_<mark style="color:blue;">Display price =</mark>_  _<mark style="color:blue;">Price of product before the discounts (</mark>_[_<mark style="color:blue;">value calculated in step 1</mark>_](method-of-calculating-a-cart-total.md#id-1-standard-price-and-impact-price)_<mark style="color:blue;">) on which will be applied rounding taking into account</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

**Contextual currency**

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>



### Case 2 : Rounding depending on the number of digits after coma in the tab pricing of product (case 2).

If B to C check the number of digits for retail price (tax excl.)&#x20;

If B to B check the number of digits for retail price (tax incl.)

<mark style="color:red;">What about retail price by unit ?</mark>

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

## 2 - Discount Specific price

<figure><img src="../../../.gitbook/assets/image (171).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow Pricing - Discount Specific Price</a></p></figcaption></figure>

## 3 - Discount Catalog Price Rules

<figure><img src="../../../.gitbook/assets/image (169).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow of pricing - Step Discount Catalog Price Rules</a></p></figcaption></figure>

To know if the prioritary between specific price and catalog price rules look at[ the diagram](https://miro.com/app/board/uXjVMuh8JPM=/) below&#x20;

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

## 4 - Discount - Customer Group (maybe included in catalog price rules)

<figure><img src="../../../.gitbook/assets/image (170).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Worklfow of pricing - Step Discount Customer Group</a></p></figcaption></figure>



## 5 - Discount- Cart Rules

<figure><img src="../../../.gitbook/assets/image (173).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow of pricing - Step Discount - Cart rules</a></p></figcaption></figure>



####



## 6 - Retrieve cost of Shipping

<figure><img src="../../../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

Today, we consider only mono-shipping.

You have to retrieve if the shipping is free or not.

1\) Shipping could be free :&#x20;

1.1) If defined like this for the carrier&#x20;

<figure><img src="../../../.gitbook/assets/image (183).png" alt=""><figcaption></figcaption></figure>

1.2) If a cart rule in the chart mentionned free shipping and filled conditions of the cart rules

<figure><img src="../../../.gitbook/assets/image (184).png" alt=""><figcaption></figcaption></figure>

2\) In case of shipping not free

Three things to retrieve

2.1) In Shipping>Carriers

<figure><img src="../../../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>

1- Carrier's tax

2- Cost tax excluded of shipping



2.2) In Shipping>Preferences

<figure><img src="../../../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>

3- Handling charges tax excluded

## 7 - Calculation of TVA

<figure><img src="../../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

&#x20;Taxes : Sum of rounding of VAT :

To calculate a unique VAT

1\) VAT of products

first group the excluded tax costs by VAT value, round each one and then add them together. Consider :

* a product A (excluding VAT) of 5.221 euros taxed at 20%, quantity 4
* a product B (excluding VAT) of 2.506 euros taxed at 10%, quantity 2
* a product C (excluding VAT) of 6.220 euros taxed at 20%, quantity 3
* a product D (excluding VAT) of 3.515 euros taxed at 10%, quantity 1

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



2\) VAT of shipping

The shipping and handling tax is added to this: Consider :

* shipping at 20 euros, excluding tax, and VAT at 10
* handling at 2 euros We calculate the shipping VAT: 0,1 \* 20 = 2 Calculate the handling VAT: 0,1 \* 2 = 0,2

For a total tax of : 8,76 + 2 + 0,2 = 10.96

Explain the chosen price rounded off about currency or number of digits after the decimal point in BO (case of petrol) to be parameterized



2\) To calculate multi VAT : TODO

## 8.1 - Display of the chart tax excluded for B to B

<figure><img src="../../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

1 - X item : Number before _item_ correspond to the number of articles in the chart

2 - Cost excluded of items : Sum of prices tax excluded of each product in the chart ([datas retrieved step 1](method-of-calculating-a-cart-total.md#id-1-standard-price-and-impact-price))

3 - Shipping : Cost tax excluded of shipping + Handling charges tax ecluded ([datas retrieved step 6](method-of-calculating-a-cart-total.md#id-6-retrieve-cost-of-shipping))

4 - Total (tax excl) : Sum of 2 and 3

6 - Taxes : ([VAT retrieved step 7](method-of-calculating-a-cart-total.md#id-7-calculation-of-tva))



#### <mark style="color:red;">You have two notions : the display price and the price use for calculation</mark>

<mark style="color:red;">That is correct, if you round to the number of displayed decimals, that is solving the problem that the price is a bot off, like 99.999999 in the above example. You are calculating with the same price that is displayed. But there could be merchants that display unit prices with higher precision, lite in the gas stations the litre price would be 1.895 Euros, for example. So I think that we need two settings for the decimals, a separate one for the precision of displayed prices.</mark>

<mark style="color:red;">The requirement would be:</mark>

* <mark style="color:red;">Unit prices can have more decimals than the currency, to support small unit prices which need more precision. In this case, invoice line totals are rounded to the precision of the currency.</mark>

<mark style="color:red;">from</mark> [<mark style="color:red;">https://github.com/PrestaShop/PrestaShop/discussions/32969</mark>](https://github.com/PrestaShop/PrestaShop/discussions/32969)

## 8.2 - Display of the chart tax included for B to C

<figure><img src="../../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>



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
