---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description



## 1 - Standard Price and impact price

<figure><img src="../../../.gitbook/assets/image (172).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow Pricing - Step Standard Price + Impact Price</a></p></figcaption></figure>

#### It exists 4 types of products&#x20;

<figure><img src="../../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

To calculate the price of a product before the discount&#x20;

You need to calculate exactly with the price you are offering the product.&#x20;

If you want to calculate with fractional cents, then this needs to be able to reproduced by the customer. So you need to show more precision on the product price, invoice positions and then round the final invoiced to something that actually could be transferred.

You calculate either with tax exclusive or tax inclusive prices. If you want to display both prices, the other price would only be informative and imprecise and MUST not be used for any calculation.



Example&#x20;

You have a product which price without tax is 1066.34&#x20;

VAT = 21%

The price with tax is 1066.34\*1.21 = 1290,27 considering the price displayed rounded not 1290.2714.

So the following calculation have to be bases on the price displays for the customer



#### For Products with combination :&#x20;

If you are in a B to B display mode use the following data

&#x20;_<mark style="color:blue;">Price of product before the discounts = Retail price (tax excl.) and impact price (tax excl).</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

If you are in a B to C display mode use the following data

&#x20;_<mark style="color:blue;">Price of product before the discounts = Retail price (tax incl.) + impact price (tax incl).</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

#### For the other products&#x20;

If you are in a B to B display mode use the following data

_<mark style="color:blue;">Price of product tax excluded before the discounts = Retail price (tax excl.)</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure>

If you are in a B to C display mode use the following data

_<mark style="color:blue;">Price of product tax included before the discounts = Retail price (tax incl.)</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>



#### Output data from this step

_<mark style="color:blue;">Price of product tax included before the discounts for B to C</mark>_

_<mark style="color:blue;">Price of product tax excluded before the discounts for B to B</mark>_

_<mark style="color:blue;">Rate</mark>_





###





{% embed url="https://github.com/PrestaShop/PrestaShop/discussions/34262#discussioncomment-7777008" %}

## Rounding 1

<mark style="color:red;">Perhaps suppress rounding 1 and merge it with rounding 2 as the data displayed is this one after (specific price, catalog price rules and customer group even if no discount like this)</mark>

Each data displayed in the FO has to be rounded

Thanks to a toggle button either by  the number of decimals in the currencies (case 1] or depending on the number of digits after coma in the tab pricing of product (case 2).

Why the second option is interesting ?

Case of gas station for fuel. The price is displayed with three digits after coma event if the payment is with two digits in the case of euros. So for the calculation, the rounding has to be done with three digits.



### Case 1 : Rounding depending on the number of currency decimals used in the context of the FO and configured in the BO.

_<mark style="color:blue;">Display price =</mark>_  _<mark style="color:blue;">Price of product before the discounts (</mark>_[_<mark style="color:blue;">value calculated in step 1</mark>_](method-of-calculating-a-cart-total.md#id-1-standard-price-and-impact-price)_<mark style="color:blue;">) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

**Contextual currency in FO**

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

#### Contextual currency in BO for order

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

### Case 2 : Rounding depending on the number of digits after coma in the tab pricing of product (case 2).

_<mark style="color:blue;">Display price =</mark>_  _<mark style="color:blue;">Price of product before the discounts (</mark>_[_<mark style="color:blue;">value calculated in step 1</mark>_](method-of-calculating-a-cart-total.md#id-1-standard-price-and-impact-price)_<mark style="color:blue;">) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

If B to C check the number of digits for retail price (tax excl.)&#x20;

If B to B check the number of digits for retail price (tax incl.)



<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>



### \*Round mode

* Round up away form zero, when it is half way there (recommended)
* Round down towards zero when it is half way there
* Round towards the next even value
* Round towards the next odd value
* Round up to the nearest value
* Round down to the nearest value

[cf php documentation](https://www.php.net/manual/en/function.round.php)

<figure><img src="../../../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>

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







### Round (to move at another place)

* Round on each line
* Round on each item
* Round on the total

<figure><img src="../../../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>

### \*R



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
