---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total (MOCCT)



<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>

## Description



## 1 - Standard Price and impact price

<figure><img src="../../../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>

#### It exists 4 types of products&#x20;

<figure><img src="../../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

To calculate the price of a product before the discount&#x20;

It would help if you calculated exactly with the price you are offering the product.&#x20;

If you want to calculate with fractional cents, then this needs to be able to be reproduced by the customer. So you need to show more precision on the product price, invoice positions and then round the final invoice to something that actually could be transferred.

You calculate either with tax-exclusive or tax-inclusive prices. If you want to display both prices, the other price would only be informative and imprecise and MUST not be used for any calculation.



Example&#x20;

You have a product which price without tax is 1066.34&#x20;

VAT = 21%

The price with tax is 1066.34\*1.21 = 1290,27 considering the price displayed rounded not 1290.2714.

So the following calculation have to be bases on the price displays for the customer



#### For Products with combination :&#x20;

If you are in a B to B display mode use the following data for chart calculation

&#x20;_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step1 = Retail price (tax excl.) and impact price (tax excl).</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

If you are in a B to C display mode use the following data for chart calculation

&#x20;_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step1 = Retail price (tax incl.) + impact price (tax incl).</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

#### For the other products&#x20;

If you are in a B to B display mode use the following data

&#x20;_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step1  = Retail price (tax excl.)</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure>

If you are in a B to C display mode use the following data

_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step1 = Retail price (tax incl.)</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>



#### Output data from this step

If B to C

_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step1</mark>_

_<mark style="color:blue;">Rate of the product</mark>_

If B to B

_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step1</mark>_

_<mark style="color:blue;">Rate of the product</mark>_



_<mark style="color:blue;">The data from this step to the following are sent with the most of precision possible because the data displayed in the FO is this one after step 4 "Discount Customer Group" or step 3 if step 4 is decided to be merged with step 3.</mark>_





{% embed url="https://github.com/PrestaShop/PrestaShop/discussions/34262#discussioncomment-7777008" %}

## 2 - Discount Specific price

This step will be calculated only if it exists some specific prices.

<figure><img src="../../../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

If B to C

_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step2</mark>_

_<mark style="color:blue;">Rate of the product</mark>_

If B to B

_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step2</mark>_

_<mark style="color:blue;">Rate of the product</mark>_



_<mark style="color:blue;">The data from this step to the following are sent with the most of precision possible because the data displayed in the FO is this one after step 4 "Discount Customer Group" or step 3 if step 4 is decided to be merged with step 3.</mark>_

## 3 - Discount Catalog Price Rules

This step will be calculated only if it exists some Catalog Price Rules.

<figure><img src="../../../.gitbook/assets/image (169).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1SKKAMRoQqmfnpv7Hg2fZdsrd1DjfuyYB3u8gmejZ3ZM/edit#gid=538880055">Workflow of pricing - Step Discount Catalog Price Rules</a></p></figcaption></figure>

To know if the prioritary between specific price and catalog price rules look at[ the diagram](https://miro.com/app/board/uXjVMuh8JPM=/) below&#x20;

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

If B to C

_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step3</mark>_

_<mark style="color:blue;">Rate of the product</mark>_

If B to B

_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step3</mark>_

_<mark style="color:blue;">Rate of the product</mark>_



_<mark style="color:blue;">The data from this step to the following are sent with the most of precision possible because the data displayed in the FO is this one after step 4 "Discount Customer Group" or step 3 if step 4 is decided to be merged with step 3.</mark>_

## 4 - Discount - Customer Group (maybe included in catalog price rules)

This step will be calculated only if it exists some Catalog Price Rules.

<figure><img src="../../../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

If B to C

_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step4</mark>_

_<mark style="color:blue;">Rate of the product</mark>_

If B to B

_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step4</mark>_

_<mark style="color:blue;">Rate of the product</mark>_



_<mark style="color:blue;">The data from this step to the following are sent with the most of precision possible because the data displayed in the FO is this one after step 4 "Discount Customer Group" or step 3 if step 4 is decided to be merged with step 3.</mark>_

_<mark style="color:blue;">After each cart rules you have to apply rounding because each discount is displayed</mark>_



## Rounding 1 for display price

Each price displayed in the BO (list of products) and in the FO is rounded according to the Decimals defined in currencies.

_<mark style="color:blue;">Display\_price\_rounding\_1 =</mark>_  _<mark style="color:blue;">Price of product after the discounts (step 3) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

We have to disting data displayed to data used for the following calculations.

#### Output data from this step

_<mark style="color:blue;">Display\_price\_rounding\_1</mark>_





## Rounding 1 for calculation

Thanks to a toggle button either by  the number of decimals in the currencies (case 1] or depending on the number of digits after coma in the tab pricing of product (case 2).

Why the second option is interesting ?

Case of gas station for fuel. The price is displayed with three digits after coma event if the payment is with two digits in the case of euros. So for the calculation, the rounding has to be done with three digits.



### Case 1 : Rounding depending on the number of currency decimals used in the context of the FO and configured in the BO.

In this case, rounding for calculation in the next step is the same as the rounding used for displayed prices.

_<mark style="color:blue;">Calculation\_price\_rounding\_1 =</mark>_  _<mark style="color:blue;">Price of the product after the catalog discounts (step 4) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

**Contextual currency in FO**

<figure><img src="../../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Contextual currency in BO for order

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

### Case 2 : Rounding depending on the number of digits after coma in the tab pricing of product (case 2).

_<mark style="color:blue;">Calculation\_price\_rounding\_1 =</mark>_  _<mark style="color:blue;">Price of the product after the catalog discounts (step 4) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

If B to C check the number of digits for retail price (tax excl.)&#x20;

If B to B check the number of digits for retail price (tax incl.)



<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

_<mark style="color:blue;">Calculation\_price\_rounding\_1</mark>_

### \*Round mode

* Round up away form zero, when it is half way there (recommended)
* Round down towards zero when it is half way there
* Round towards the next even value
* Round towards the next odd value
* Round up to the nearest value
* Round down to the nearest value

[cf php documentation](https://www.php.net/manual/en/function.round.php)

<figure><img src="../../../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>

##

## 5 - Discount- Cart Rules

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>



#### Output data from this step

If B to C

_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step5 (price after cart rules n)</mark>_

_<mark style="color:blue;">Amount\_of\_the\_discount\_tax\_included\_step5</mark>_

_<mark style="color:blue;">Rate of the product</mark>_

If B to B

_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step5 (price after cart rules n)</mark>_

_<mark style="color:blue;">Amount\_of\_the\_discount\_tax\_excluded\_step5</mark>_

_<mark style="color:blue;">Rate of the product</mark>_



##



## Rounding 2 for display price

The amount of the discount in the chart in the FO is rounded according to the Decimals defined in currencies.

_<mark style="color:blue;">Display\_amount\_discount\_n\_rounding\_2 = Price of the product after the previous cart rule (step 5) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

_**1 -** <mark style="color:blue;">Display\_amount\_discount\_1\_rounding\_2</mark>_

_<mark style="color:blue;">2-Display\_amount\_discount\_2\_rounding\_2</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

We have to disting data displayed to data used for the following calculations.

#### Output data from this step

_<mark style="color:blue;">Display\_amount\_discount\_n\_rounding\_2</mark>_

\*\*\*

### Rounding 2 for calculation

Thanks to a toggle button either by  the number of decimals in the currencies (case 1] or depending on the number of digits after coma in the tab pricing of product (case 2).

Why the second option is interesting ?

Case of gas station for fuel. The price is displayed with three digits after coma event if the payment is with two digits in the case of euros. So for the calculation, the rounding has to be done with three digits.



### Case 1 : Rounding depends on the number of currency decimals used in the context of the FO and configured in the BO.

In this case, rounding for calculation in the next step is the same as the rounding used for displayed prices.

_<mark style="color:blue;">Calculation\_amount\_rounding\_2 =</mark>_   _<mark style="color:blue;">Price of the product after the previous cart rule (step5) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Calculation\_price\_rounding\_2 =</mark>_   _<mark style="color:blue;">Price of the product after the previous cart rule (step5) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

**Contextual currency in FO**

<figure><img src="../../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Contextual currency in BO for order

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

### Case 2  : Rounding depending on the number of digits after coma in the tab pricing of product (case 2).

_<mark style="color:blue;">Calculation\_amount\_rounding\_2 =</mark>_  _<mark style="color:blue;">Price of product before the discounts (</mark>_[_<mark style="color:blue;">value calculated in step 1</mark>_](method-of-calculating-a-cart-total-mocct.md#id-1-standard-price-and-impact-price)_<mark style="color:blue;">) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Calculation\_price\_rounding\_2 =</mark>_  _<mark style="color:blue;">Price of product before the discounts (</mark>_[_<mark style="color:blue;">value calculated in step 1</mark>_](method-of-calculating-a-cart-total-mocct.md#id-1-standard-price-and-impact-price)_<mark style="color:blue;">) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

If B to C check the number of digits for retail price (tax excl.)&#x20;

If B to B check the number of digits for retail price (tax incl.)



<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

_<mark style="color:blue;">Calculation\_price\_rounding\_2</mark>_

If you have another discount Go back to step 5 else go on

##

## 6 - Calculation of VAT

TODO : separate B to B and B to C

<figure><img src="../../../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

### B to B

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



### B to C





2\) To calculate multi VAT : TODO





## 7 - Retrieve cost of Shipping

<figure><img src="../../../.gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure>

TODO : separate B to B and B to C

Today, we consider only mono-shipping.

You have to determine if the shipping is free or not.

1\) Shipping could be free :&#x20;

1.1) If defined like this for the carrier&#x20;

<figure><img src="../../../.gitbook/assets/image (183).png" alt=""><figcaption></figcaption></figure>

1.2) If a cart rule in the chart mentions free shipping and filled conditions of the cart rules

<figure><img src="../../../.gitbook/assets/image (184).png" alt=""><figcaption></figcaption></figure>

1.3) Shipping to 0 by range is like free or could be integrated to shipping not free = 0 and the result will be 0.

Range and cost are tax excluded : cf 1- and 2- image below

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>

1.4) Free shipping starts at in Shipping>Preference (is tax included)

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>



2\) In case of shipping not free

Three things to retrieve : Carrier's tax, Cost tax excluded of shipping, handling charges if add handling costs is "Yes"

2.1) In Shipping>Carriers

<figure><img src="../../../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>

1- Carrier's tax

2- Cost tax excluded of shipping



2.2) In Shipping>Preferences

<figure><img src="../../../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>

3- Handling charges tax excluded



&#x20;VAT of shipping

The shipping and handling tax is added to this: Consider :

* shipping at 20 euros, excluding tax, and VAT at 10
* handling at 2 euros We calculate the shipping VAT: 0,1 \* 20 = 2 Calculate the handling VAT: 0,1 \* 2 = 0,2

For a total tax of : 8,76 + 2 + 0,2 = 10.96

Explain the chosen price rounded off about currency or number of digits after the decimal point in BO (case of petrol) to be parameterized

## 8.1 - Display of the chart tax excluded for B to B

<figure><img src="../../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

1 - X item : Number before _item_ correspond to the number of articles in the chart

2 - Cost excluded of items : Sum of prices tax excluded of each product in the chart ([datas retrieved step 1](method-of-calculating-a-cart-total-mocct.md#id-1-standard-price-and-impact-price))

3 - Shipping : Cost tax excluded of shipping + Handling charges tax ecluded ([datas retrieved step 6](method-of-calculating-a-cart-total-mocct.md#id-6-retrieve-cost-of-shipping))

4 - Total (tax excl) : Sum of 2 and 3

6 - Taxes : ([VAT retrieved step 7](method-of-calculating-a-cart-total-mocct.md#id-7-calculation-of-tva))



## 8.2 - Display of the chart tax included for B to C

<figure><img src="../../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>







### Round (to move at another place)

* Round on each line
* Round on each item
* Round on the total

<figure><img src="../../../.gitbook/assets/image (189).png" alt=""><figcaption></figcaption></figure>

###



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
