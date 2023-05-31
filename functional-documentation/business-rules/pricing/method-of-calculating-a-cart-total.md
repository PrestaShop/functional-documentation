---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description





US

<table><thead><tr><th width="113">US</th><th>Descpription</th><th>Examples</th></tr></thead><tbody><tr><td><mark style="color:purple;">MOCCT-001</mark></td><td><mark style="color:purple;">Case without reduction for ONE article and fixed VAT</mark> - without decimal and rounding</td><td><mark style="color:purple;">Examples for the case MOCCT-001. Click</mark> <a href="https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=0"><mark style="color:purple;">here</mark></a></td></tr><tr><td><mark style="color:orange;">MOCCT-002</mark></td><td><mark style="color:orange;">MOCCT_001 for a product with more than one for quantity - without decimal and rounding</mark></td><td><mark style="color:orange;">Examples for the case MOCCT-002</mark>      <a href="https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=43061852"><mark style="color:orange;">Click here</mark></a></td></tr><tr><td><mark style="color:green;">MOCCT_003</mark></td><td><mark style="color:green;">MOCCT_002 with rational number only</mark></td><td><mark style="color:green;">Examples for the case MOCCT-003</mark> <a href="https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=1249928607"><mark style="color:green;">Click here</mark></a></td></tr><tr><td><mark style="color:red;">MOCCT_004</mark></td><td><mark style="color:red;">MOCCT- 004 : Case without reduction for differents articles with a quantity > 1/ fixed VAT/with rational numbers</mark></td><td><mark style="color:red;">Examples for the case MOCCT-004</mark> <a href="https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=1249928607"><mark style="color:red;">Click here</mark></a></td></tr><tr><td><mark style="background-color:blue;">MOCCT_005</mark></td><td><mark style="background-color:blue;">[US-Pricing][MOC] : MOCCT- 005 : Round product with different round modes and precisions</mark></td><td><mark style="background-color:blue;">Examples for the case MOCCT-005</mark><a href="http://localhost:5000/s/jyL8OZq59yY3Nomb341u/user-guide/connecting-back-office"> </a></td></tr></tbody></table>

### Steps of the price calculation

#### <mark style="color:purple;">Step\_SP</mark>

<mark style="color:purple;">Description : Retrieve the standard price for</mark> <mark style="color:purple;"></mark>~~<mark style="color:purple;">one</mark>~~ <mark style="color:red;">each</mark> <mark style="color:purple;">product (SP)</mark>&#x20;

<mark style="color:purple;">Formule : NA</mark>

<mark style="color:purple;">US : MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>



#### <mark style="color:purple;">Step\_IP</mark>

<mark style="color:purple;">Description : Retrieve the impact Price (IP)</mark> <mark style="color:red;">for each product</mark>

<mark style="color:purple;">Formule : NA</mark>

<mark style="color:purple;">US : MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>



#### <mark style="color:purple;">Step\_CP</mark>

<mark style="color:purple;">Description : Calculation of the price of the combination HT (CP)</mark> <mark style="color:purple;"></mark><mark style="color:red;"><mark style="color:purple;">for<mark style="color:purple;"></mark> <mark style="color:red;"></mark><mark style="color:red;">each product</mark>

<mark style="color:purple;">Formule : CP = SP + IP</mark>

<mark style="color:purple;">US : MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>

#### <mark style="color:purple;">Step\_RVAT</mark>&#x20;

<mark style="color:purple;">Description : Recovery of rate of VAT (RVAT)</mark>&#x20;

<mark style="color:purple;">Formule : to dig into the specifications (Country, state, zip code) - For now ARBITRARY fixed to 20%</mark>

<mark style="color:purple;">US : MOCCT-001</mark>

#### <mark style="color:purple;">Step\_AmountTVATaxExcluded</mark>

<mark style="color:purple;">Description : Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded)</mark> <mark style="color:red;">for each product</mark>&#x20;

<mark style="color:purple;">Formule</mark> <mark style="color:red;">:</mark> <mark style="color:purple;">AmountTVATaxExcluded = RVAT \* CP</mark>

<mark style="color:purple;">US  : MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>



#### <mark style="color:orange;">Step\_Quantity\_Recovery</mark>&#x20;

<mark style="color:orange;">Description : Recovery of the quantité of CP (Q)</mark> <mark style="color:red;">for each product</mark>

<mark style="color:orange;">Formule : NA</mark>

<mark style="color:orange;">US : MOCCT-002,</mark> <mark style="color:red;">MOCCT\_004</mark>



#### <mark style="background-color:blue;">Step\_Round\_item</mark>

<mark style="background-color:blue;">Description : It exist 6 round modes</mark>

<mark style="background-color:blue;">Formule : This mode have to be applicated on</mark> <mark style="background-color:red;">Step\_CP or Step\_RVAT ?</mark>

<mark style="background-color:blue;">US : MOCCT-005</mark>



#### <mark style="color:purple;">Step\_Total\_Taxes\_excluded</mark>

<mark style="color:purple;">Description : Calculation of total taxes excluded (Total\_Taxes\_excluded)</mark> <mark style="color:red;">for all products</mark>

<mark style="color:purple;">Formule :</mark> <mark style="color:purple;"></mark>~~<mark style="color:purple;">The quantity Q is consider to 1 arbitrary</mark>~~

&#x20;~~<mark style="color:purple;">Total\_Taxes\_excluded = 1 \* CP</mark>~~  <mark style="color:purple;"></mark>                  &#x20;

&#x20;<mark style="color:red;">For all products</mark> <mark style="color:orange;">Total\_Taxes\_excluded =</mark> <mark style="color:red;">For all products sum of</mark> <mark style="color:orange;">Q \* CP</mark>    &#x20;

<mark style="color:purple;">US : MOCCT-001,</mark> <mark style="color:orange;">MOCCT-002,</mark> <mark style="color:red;">MOCCT\_004</mark>



#### <mark style="color:purple;">Step\_Shipping\_costs</mark>&#x20;

<mark style="color:purple;">Description : Recovery of Shipping cost Taxes excluded (Shipping\_costs)</mark>

<mark style="color:purple;">Formule : Recovery of Shipping cost Taxes excluded (Shipping\_costs)</mark>

<mark style="color:purple;">US : MOCCT-001</mark>



#### <mark style="color:purple;">Step\_Line\_Tax\_Excluded\_with\_Shipping\_costs</mark>

<mark style="color:purple;">Description : Calculation tax excluded of the total with shipping costs (Total\_Tax\_Excluded\_with\_Shipping\_costs)</mark>

<mark style="color:purple;">Formule :</mark>&#x20;

<mark style="color:purple;">Line\_Tax\_Excluded\_with\_Shipping\_costs</mark>&#x20;

<mark style="color:purple;">**=**</mark> <mark style="color:red;">(</mark><mark style="color:purple;">CP \* (</mark>~~<mark style="color:purple;">1</mark>~~ <mark style="color:orange;">Q</mark><mark style="color:purple;">+ RVAT + Shipping\_costs)</mark><mark style="color:red;">)</mark>



<mark style="color:purple;">US : MOCCT-001,</mark> <mark style="color:orange;">MOCCT-002</mark>



#### <mark style="color:red;">Step\_total</mark>

<mark style="color:red;">Description :</mark>&#x20;

<mark style="color:red;">Formule : Sum for each products of Step\_Line\_Tax\_Excluded\_with\_Shipping\_costs</mark>



<mark style="color:red;">US : Sum for each products of Step\_Line\_Tax\_Excluded\_with\_Shipping\_costs</mark>





#### Round mode

R1 : Round up away from zero, when it is half way there (recommended)&#x20;

R2 : Round down towards zero, when it is half way there&#x20;

R3 : Round towards the next even value&#x20;

R4 : Round towards the next odd value&#x20;

R5 : Round up to the nearest value R6 : Round down to the nearest value

[https://www.php.net/manual/en/function.round.php](https://www.php.net/manual/en/function.round.php)



Ce qui impacte le prix :

Règles connues sont celles-ci

* cart rules (où ?)
* catalogues prices rules (où ?)
* prix spécifiques (où ?)
* TVA (où ?)
* Ecotax&#x20;
* Group client
* Cadeaux ?
* Modifications des prix selon les currencies
* Pays ?



Cf ITW Christophe :&#x20;

5 outils de promo&#x20;

* Prix spécifiques
* Code promo (=règle panier = coupon de réduction)
* Règles de prix catalogue
* Groupe Client
* Pack





Par défaut règle de prix spécifique qui prend le dessus sur le prix catalogue



Qu'est ce qui modifie le prix à quel moment à quel endroit et ce qu'on veut que ca fasse ?

Quels sont tous les endroits où on retorouve la liste ci-dessus des règlesde calcul



Group client peut être dans prix spécifiques, dans catalogues prices rules et au niveau du groupe client

Au niveau du groupe client tu peux avoir un discount gobal (sur tous les produits) et/ou au niveau de catégégorie de produit)



Il faut pouvoir ajouter une règle à n'importe quelle étape sur TTC ou HT





\


