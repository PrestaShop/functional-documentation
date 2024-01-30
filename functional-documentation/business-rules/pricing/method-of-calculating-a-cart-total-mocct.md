---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total (MOCCT)

<figure><img src="../../../.gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>

## Description



## 1 - Standard Price and impact price

<figure><img src="../../../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>

### It exists 4 types of products&#x20;

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

To calculate the price of a product before the discount&#x20;

It would help if you calculated exactly with the price you are offering the product.&#x20;

If you want to calculate with fractional cents, then this needs to be able to be reproduced by the customer. So you need to show more precision on the product price, invoice positions and then round the final invoice to something that actually could be transferred.

You calculate either with tax-exclusive or tax-inclusive prices. If you want to display both prices, the other price would only be informative and imprecise and MUST not be used for any calculation.



#### 1) Product A without combination

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

#### 2) Product B without a combination

<figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

#### 3) Product C without combination

<figure><img src="../../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

#### 4) Product D without combination

<figure><img src="../../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

#### For Products with combination :&#x20;

If you are in a **B to B** display mode use the following data for chart calculation

&#x20;_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step1 = Retail price (tax excl.) and impact price (tax excl).</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

If you are in a **B to C** display mode use the following data for chart calculation

&#x20;_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step1 = Retail price (tax incl.) + impact price (tax incl).</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

#### For the other products&#x20;

If you are in a **B to B** display mode use the following data

&#x20;_<mark style="color:blue;">Price\_of\_product\_tax\_excluded\_step1  = Retail price (tax excl.)</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

If you are in a **B to C** display mode use the following data

_<mark style="color:blue;">Price\_of\_product\_tax\_included\_step1 = Retail price (tax incl.)</mark>_&#x20;

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

If B to C

_<mark style="color:blue;">For each product (Price\_of\_product\_tax\_included\_step1;Rate of the product)</mark>_

If B to B

_<mark style="color:blue;">For each product (Price\_of\_product\_tax\_excluded\_step1;Rate of the product)</mark>_



_Example Output data for products A,B,C,D_

_If B to B_

Product A : (5.221;20%)

Product B : (2.506;10%)

Product C : (6.22;20%)

Product D : (3.515;10%)

_If B to C_

Product A : (6.2652;20%)

Product B : (2.7566;10%)

Product C : (7.464;20%)

Product D : (3.8665;10%)

_<mark style="color:blue;">The data from this step to the following are sent with the most precision possible because the data displayed in the FO, so rounded, are this one after step 4 "Discount Customer Group" (or step 3 if step 4 is decided to be merged with step 3)</mark>_





{% embed url="https://github.com/PrestaShop/PrestaShop/discussions/34262#discussioncomment-7777008" %}

## 2 - Discount Specific price <mark style="color:orange;">for now consider no discount</mark>

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

## 3 - Discount Catalog Price Rules <mark style="color:orange;">for now consider no discount</mark>

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

## 4 - Discount - Customer Group (maybe included in catalog price rules) <mark style="color:orange;">for now consider no discount</mark>

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



## Rounding 1 for display price&#x20;

Each price displayed in the BO (list of products) and the FO is rounded according to the Decimals defined in currencies.

Products in BO :&#x20;

<figure><img src="../../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

Products in FO in the details page or in the catalog :&#x20;

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>



_<mark style="color:blue;">Display\_price\_rounding\_1 =</mark>_  _<mark style="color:blue;">Price of the product after the discounts (step 3) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

**WARNING**: We have to disting data displayed to data used for the following calculations.

#### Output data from this step

_<mark style="color:blue;">For each product (Display\_price\_rounding\_1, rate)</mark>_

_Example Output data for products A,B, C,D considering_

&#x20;_round mode: Round up away from zero, when it is half way there (recommended)  which is the round merchant_

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

Product A : (5.22;20%)

Product B : (2.51;10%)

Product C : (6.22;20%)

Product D : (3.52;10%)

_If B to C_

Product A : (6.27;20%)

Product B : (2.76;10%)

Product C : (7.46;20%)

Product D : (3.87;10%)



## Rounding 1 for calculation

We are going to set the Rounding thanks to a toggle button depending on :&#x20;

* either by the number of decimals in the currencies \[case 1 -like rounding 1 for display price] or&#x20;
* the number of digits after coma in the tab pricing of product (case 2).

Why the second option is interesting?

Case of gas station for fuel. The price is calculated with three digits after coma even if the payment is with two digits in the case of euros for instance. So for the calculation, the rounding has to be done with three digits not depending on currency. Only the result will be rounded ate the end.



### Case 1 : Rounding depending on the number of currency decimals used in the context of the FO and configured in the BO.

In this case, rounding for calculation in the next step is the same as that used for displayed prices.

_<mark style="color:blue;">Calculation\_price\_rounding\_1 =</mark>_  _<mark style="color:blue;">Price of the product after the catalog discounts (step 4) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

#### **Contextual currency in FO**

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Contextual currency in BO for order

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Case 2 : Rounding depending on the number of digits after coma in the tab pricing of product (case 2).

_<mark style="color:blue;">Calculation\_price\_rounding\_1 =</mark>_  _<mark style="color:blue;">Price of the product after the catalog discounts (step 4) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

If B to C check the number of digits for retail price (tax excl.)&#x20;

If B to B check the number of digits for retail price (tax incl.)



<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Case 1 : Output data from this step

_<mark style="color:blue;">For each product (Calculation\_price\_rounding\_1, rate)</mark>_

_Example Output data for products A,B,C,D considering_

&#x20;_round mode: Round up away from zero, when it is half way there (recommended)  which is the round merchant_

_Case 1 if B to B_

Product A : (5.22;20%)

Product B : (2.51;10%)

Product C : (6.22;20%)

Product D : (3.52;10%)

_Case 1 If B to C_

Product A : (6.27;20%)

Product B : (2.76;10%)

Product C : (7.46;20%)

Product D : (3.87;10%)



<mark style="color:red;">Todo case 2</mark>

#### <mark style="color:red;">Case 2 : Output data from this step</mark>

_<mark style="color:red;">For each product (Calculation\_price\_rounding\_1, rate)</mark>_



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

## 5 - Discount- Cart Rules <mark style="color:orange;">for now consider no discount</mark>

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>



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



## Rounding 2 for display price <mark style="color:orange;">for now consider no discount</mark>

The amount of the discount in the chart in the FO is rounded according to the Decimals defined in currencies.

_<mark style="color:blue;">Display\_amount\_discount\_n\_rounding\_2 = Price of the product after the previous cart rule (step 5) on which will be applied round mode\* taking into account the number of decimals as follows :</mark>_

<figure><img src="../../../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

_**1 -** <mark style="color:blue;">Display\_amount\_discount\_1\_rounding\_2</mark>_

_<mark style="color:blue;">2-Display\_amount\_discount\_2\_rounding\_2</mark>_

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

We have to disting data displayed to data used for the following calculations.

#### Output data from this step

_<mark style="color:blue;">Display\_amount\_discount\_n\_rounding\_2</mark>_

### Rounding 2 for calculation <mark style="color:orange;">for now consider no discount</mark>

Thanks to a toggle button either by  the number of decimals in the currencies (case 1] or depending on the number of digits after coma in the tab pricing of product (case 2).

Why the second option is interesting ?

Case of gas station for fuel. The price is displayed with three digits after coma event if the payment is with two digits in the case of euros. So for the calculation, the rounding has to be done with three digits.



### Case 1 : Rounding depends on the number of currency decimals used in the context of the FO and configured in the BO.

In this case, rounding for calculation in the next step is the same as the rounding used for displayed prices.

_<mark style="color:blue;">Calculation\_amount\_rounding\_2 =</mark>_   _<mark style="color:blue;">Price of the product after the previous cart rule (step 5) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;



_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

**Contextual currency in FO**

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Contextual currency in BO for order

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Case 2  : Rounding depending on the number of digits after coma in the tab pricing of product (case 2).

_<mark style="color:blue;">Calculation\_amount\_rounding\_2 =</mark>_  _<mark style="color:blue;">Price of product before the discounts (</mark>_[_<mark style="color:blue;">value calculated in step</mark>_ ](method-of-calculating-a-cart-total-mocct.md#id-1-standard-price-and-impact-price)_<mark style="color:blue;">5) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;



If B to C check the number of digits for retail price (tax excl.)&#x20;

If B to B check the number of digits for retail price (tax incl.)



<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

_<mark style="color:blue;">Calculation\_price\_rounding\_2</mark>_

If you have another discount Go back to step 5 else go on calculation of VATthe&#x20;

##

## 6 - Calculation of VAT



<figure><img src="../../../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

### B to B

&#x20;Taxes: Sum of rounding of VAT :

To calculate a unique VAT

1\) VAT of products

First group the excluded tax costs by VAT value, round each one and then add them together. Consider Let's take the products A,B,C,D like rounded step 1

* a product A  quantity 4 in the chart
* a product B quantity 2 in the chart
* a product C quantity 3 in the chart
* a product D quantity 1



We combine products taxed at 20% and those taxed at 10%, as follows

* a product A 5.22 euros taxes excluded at rate 20%, quantity 4
* a product C 6.22  taxes excluded at 20%, quantity 3
* a product B 2.51  taxes excluded  10%, quantity 2
* a product D 3.52  taxes excluded  10%, quantity 1



We calculate the prices tax excluded of products with rate 20% rounded (let's use line rounding for the example):&#x20;

5.22 \* 4 = 20.88&#x20;

6.22 \* 3 = 18.66

Sum them up : 20.88 + 18.66 = 39,54

VAT of products with rate 20%&#x20;

<mark style="color:blue;">VAT\_rate\_20</mark> = 0.20 \* 39.54 = 7.908 rounded up to 7.91 <mark style="color:red;">(separate the rounding in a step)</mark>



We calculate the prices tax excluded of products with rate 20% rounded (let's use line rounding for the example): &#x20;

2.51 \* 2 = 5.02

3.52 \* 1 = 3.52&#x20;

Sum them up :  5.02 + 3.52 = 8,54

VAT of products with rate 10%&#x20;

<mark style="color:blue;">VAT\_rate\_10 =</mark> 0.1 \* 8.54 = 0.854 rounded up to 0.85



VAT total of products :

<mark style="color:blue;">Total\_VAT</mark> = <mark style="color:blue;">VAT\_rate\_20 + VAT\_rate\_10 = 7.91 + 0.85 = 8.76</mark>



FO :

<figure><img src="../../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

Invoice :

<figure><img src="../../../.gitbook/assets/image (207).png" alt=""><figcaption></figcaption></figure>



### B to C

Let's now imagine the same product in B to C

and the parameter of rounding is fixing with this one of the currency so two decimals after coma

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>



Let's take the products A,B,C,D like rounded step 1

* a product A  quantity 4 in the chart
* a product B quantity 2 in the chart
* a product C quantity 3 in the chart
* a product D quantity 1



We combine products taxed at 20% and those taxed at 10%, as follows

* a product A 6.27 euros taxes included at rate 20%, quantity 4
* a product C 7.46 euros taxes included at rate 20%, quantity 3
* a product B 2.76 euros taxes included at rate 10%, quantity 2
* a product 3.87 euros taxes included at rate10%, quantity 1



We calculate the price of products with rate 20% rounded (let's use line rounding for the example):&#x20;

6.27 \* 4 = 25.08 &#x20;

7.46 \* 3 = 22.38

&#x20;Sum them up: 25.08 + 22.38 = 47.46 Price tax included of products with rate 20%

47.46/1.2 = 39.55 Price tax excluded of product with rate 20%

VAT of products with rate 20%&#x20;

<mark style="color:blue;">VAT\_rate\_20</mark> = 47.46-39.55 = 7.91



We calculate the price of products with rate 10% rounded (let's use line rounding for the example)<mark style="color:purple;">:</mark>&#x20;

2.76 \* 2 =  5.52

3.87 \* 1 = 3.87

&#x20;Sum them up: 5.52 + 3.87 = 9.39 Price tax included of products with rate 10%

9.39/1.1 = 8.536363.. Price tax excluded of product with rate 10%

VAT of products with rate 10%&#x20;

<mark style="color:blue;">VAT\_rate\_10</mark> = 9.39-(9.39/1.1) = 0.853636... rounded 0.85 as displayed in the invoice (add print screen)



VAT total of products

<mark style="color:blue;">Total\_VAT</mark> = <mark style="color:blue;">VAT\_rate\_20 + VAT\_rate\_10 = 7.91 + 0.85 = 8.76</mark>



FO :

<figure><img src="../../../.gitbook/assets/image (208).png" alt=""><figcaption></figcaption></figure>

Invoice:&#x20;

<figure><img src="../../../.gitbook/assets/image (207).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

<mark style="color:blue;">Total\_VAT</mark>

<mark style="color:blue;">VAT\_rate\_20</mark>

<mark style="color:blue;">VAT\_rate\_10</mark>

<mark style="color:blue;">VAT\_rate\_X</mark>



2\) To calculate multi VAT : TODO

\*\*\* adapter ce qui est entre les étoiles

## Rounding 3 for display price

The amount of the discounts in the chart in the FO is rounded according to the Decimals defined in currencies.

The display mode is used for invoice and chart

<mark style="color:red;">add print screens</mark>

_<mark style="color:blue;">Display\_VAT\_rate\_20\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Display\_VAT\_rate\_10\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Display\_VAT\_rate\_X\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

<mark style="color:blue;">Display\_Total\_VAT\_rounding\_3 = Total\_VAT\_rounding\_3</mark> <mark style="color:blue;"></mark> <mark style="color:blue;"></mark>_<mark style="color:blue;">(step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;



_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

We have to disting data displayed to data used for the following calculations.

#### Output data from this step

_<mark style="color:blue;">Display\_VAT\_rate\_20\_rounding\_3</mark>_&#x20;

_<mark style="color:blue;">Display\_VAT\_rate\_10\_rounding\_3</mark>_&#x20;

_<mark style="color:blue;">Display\_VAT\_rate\_X\_rounding\_3</mark>_&#x20;

<mark style="color:blue;">Display\_Total\_VAT\_rounding\_3</mark>

## Rounding 3 for calculation

Thanks to a toggle button either by  the number of decimals in the currencies (case 1] or depending on the number of digits after coma in the tab pricing of product (case 2).

Why the second option is interesting ?

Case of gas station for fuel. The price is displayed with three digits after coma event if the payment is with two digits in the case of euros. So for the calculation, the rounding has to be done with three digits.



### Case 1 : Rounding depending on the number of currency decimals used in the context of the FO and configured in the BO.

In this case, rounding for calculation in the next step is the same as the rounding used for displayed prices.

_<mark style="color:blue;">Calculation\_VAT\_rate\_20\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Calculation\_VAT\_rate\_10\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Calculation\_VAT\_rate\_X\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

<mark style="color:blue;">Calculation\_Total\_VAT\_rounding\_3 = Total\_VAT\_rounding\_3</mark> <mark style="color:blue;"></mark> <mark style="color:blue;"></mark>_<mark style="color:blue;">(step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_**Configuration in the BO**_

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>

**Contextual currency in FO**

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Contextual currency in BO for order

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Case 2 : Rounding depending on the number of digits after coma in the tab pricing of product (case 2).

_<mark style="color:blue;">Calculation\_VAT\_rate\_20\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows Calc\_VAT\_rate\_10\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Calculation\_VAT\_rate\_X\_rounding\_3 = VAT\_rate\_20 (step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

_<mark style="color:blue;">Calculation\_</mark>_<mark style="color:blue;">Total\_VAT\_rounding\_3 = Total\_VAT\_rounding\_3</mark> <mark style="color:blue;"></mark> <mark style="color:blue;"></mark>_<mark style="color:blue;">(step 6) on which will be applied round mode\* taking into account the number of decimals as follows</mark>_&#x20;

If B to C check the number of digits for retail price (tax excl.)&#x20;

If B to B check the number of digits for retail price (tax incl.)



<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Output data from this step

_<mark style="color:blue;">Calculation\_VAT\_rate\_20\_rounding\_3</mark>_

_<mark style="color:blue;">Calculation\_VAT\_rate\_X\_rounding\_3</mark>_

_<mark style="color:blue;">Calculation\_</mark>_<mark style="color:blue;">Total\_VAT\_rounding\_3</mark>

\*\*\*



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

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

1 - X item : Number before _item_ correspond to the number of articles in the chart

2 - Cost excluded of items : Sum of prices tax excluded of each product in the chart ([datas retrieved step 1](method-of-calculating-a-cart-total-mocct.md#id-1-standard-price-and-impact-price))

3 - Shipping : Cost tax excluded of shipping + Handling charges tax ecluded ([datas retrieved step 6](method-of-calculating-a-cart-total-mocct.md#id-6-retrieve-cost-of-shipping))

4 - Total (tax excl) : Sum of 2 and 3

6 - Taxes : ([VAT retrieved step 7](method-of-calculating-a-cart-total-mocct.md#id-7-calculation-of-tva))



## 8.2 - Display of the chart tax included for B to C

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>







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
