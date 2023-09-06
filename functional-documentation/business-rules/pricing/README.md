# Pricing

## Business rule description

[The General workflow of the pricing](https://miro.com/app/board/uXjVMuHE5i8=/)

<figure><img src="../../../.gitbook/assets/Pricing - General Workflow.jpg" alt=""><figcaption><p>General workflowof the pricing<a href="https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/~/changes/755/functional-documentation/business-rules/pricing/part-3-taxes">Part 3 : Taxes</a></p></figcaption></figure>

This [sheet-pricing ](https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=538880055)let to simulate the main cases taking into account :&#x20;

[Part 1 : Calculation in the catalogue before addind products in the cart](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/754/functional-documentation/business-rules/pricing/part-1-calculation-in-the-catalogue-before-addind-products-in-the-cart)

[Part 2 : Discount in the cart](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/755/functional-documentation/business-rules/pricing/part-2-discount-in-the-cart)

[Part 3 : Taxes](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/755/functional-documentation/business-rules/pricing/part-3-taxes)

Part 4 Display of the chart in the FO (put this part in UX/UI



### UX/UI impact of this BR

todo



<table><thead><tr><th width="94">Level</th><th>Formula</th></tr></thead><tbody><tr><td></td><td><h4><del><mark style="background-color:blue;">Step_Round_item</mark></del></h4><p><del><mark style="background-color:blue;">Description : It exist 6 round modes</mark></del></p><p><del><mark style="background-color:blue;">Formule : This mode have to be applicated on</mark></del> <del><mark style="background-color:red;">Step_CP or Step_RVAT ?</mark></del></p><p><del><mark style="background-color:blue;">US : MOCCT-005</mark></del></p></td></tr></tbody></table>

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

Quels sont tous les endroits où on retorouve la liste ci-dessus des règles de calcul



Group client peut être dans prix spécifiques, dans catalogues prices rules et au niveau du groupe client

Au niveau du groupe client tu peux avoir un discount gobal (sur tous les produits) et/ou au niveau de catégégorie de produit)



Il faut pouvoir ajouter une règle à n'importe quelle étape sur TTC ou HT



## Description



<table><thead><tr><th width="113">US (link to Github)</th><th>Descpription</th></tr></thead><tbody><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32592">MOCCT-001</a></td><td>For one article, Quantity 1, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32274">MOCCT-002</a></td><td>For one article, Quantity <strong>parametrable</strong>, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/33684">MOCCT-003</a></td><td>For one article, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT <strong>parametrable</strong>, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></td><td>For <strong>several</strong> items, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT parametrable, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/33691">MOCCT_005</a></td><td>For <strong>several</strong> items, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT parametrable, <strong>shipping including</strong> - Total Tax excluded, Tax included</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/33773">MOCCT_006</a></td><td><mark style="color:orange;">[US-Pricing][MOC][Without rounding] : MOCCT- 006 : Cart rules amount Tax excluded without conditions - Display excluded</mark></td></tr></tbody></table>

### Steps of the price calculation

Level 1 is the list of one or several products or value shared by all productd

Level 2 is for each product

<table><thead><tr><th width="94">Level</th><th>Formula</th></tr></thead><tbody><tr><td>2</td><td><h4>Step_SP_by_item</h4><p>Description: Retrieve the standard price for each product (SP) </p><p>Formula: NA</p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_IP_by_item</h4><p>Description: Retrieve the impact Price (IP) for each product</p><p>Formula: NA</p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_CP_by_item</h4><p>Description: Calculation of the price of the combination HT (CP) for each product</p><p>Formula : CP_by_item = SP_by_item + IP_by_item</p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td><mark style="color:orange;">2</mark></td><td><p><mark style="color:orange;"><strong>Step_Price_AfterDiscountCatalog_by_item</strong></mark></p><p><mark style="color:orange;">Description: Retrieve the price HT for each product after Specific Price and/or Catalog Price Rules and/or Group Discount Price_AfterDiscountCatalog_by_item</mark></p><p><mark style="color:orange;">Formula : NA</mark></p><p><mark style="color:orange;">US: MOCCT-006</mark></p></td></tr><tr><td>2</td><td><h4>Step_CP_Q_by_item</h4><p>Description: Calculation of the price total (Tax excl) taking into account quantity for each product</p><p>Formula : CP_Q_by_item = <del><mark style="color:orange;">CP_by_item</mark></del><mark style="color:orange;"> Price_AfterDiscountCatalog_by_item</mark> * Quantity of the product</p><p>US : MOCCT-001, MOCCT-002, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a>, <mark style="color:orange;">MOCCT-006</mark></p></td></tr><tr><td><mark style="color:orange;">2</mark></td><td><p><mark style="color:orange;"><strong>Step_Cart_rules_amount_excluded_By_Item_step1</strong></mark></p><p><mark style="color:orange;">Description: Calculation of the new price of chart after a discount <strong>amount</strong></mark> <mark style="color:orange;"><strong>Tax excluded</strong></mark></p><p><mark style="color:orange;">Step 1 consist to Calculation of the prorata of the discount on each product</mark></p><p><mark style="color:orange;">Formula:</mark> </p><p><mark style="color:orange;">1) If first cart rule</mark> </p><p><mark style="color:orange;">Cart_rules_amount_excluded_By_Item_step1 =</mark> <mark style="color:orange;">CP_Q_by_item</mark> <mark style="color:orange;">/</mark> <mark style="color:orange;">SUM(CP_Q_by_item )*Amount of the discount</mark></p><p></p><p><mark style="color:orange;">2) if it exist a precedent discount</mark></p><p><mark style="color:orange;">Cart_rules_amount_excluded_By_Item_step1 =(Precedent Prix reduit * Quantity of the product)/</mark> <mark style="color:orange;">SUM(Precedent Prix reduit * Quantity of the product)*Amount of the discount.</mark></p><p><mark style="color:orange;">US: MOCCT-006</mark></p></td></tr><tr><td><mark style="color:orange;">2</mark></td><td><p><mark style="color:orange;"><strong>Step_Cart_rules_amount_excluded_By_Item_step2</strong></mark></p><p><mark style="color:orange;">Description:Deduct the prorata of cart rules from Price of the product</mark></p><p><mark style="color:orange;">Formula:</mark></p><p><mark style="color:orange;">Cart_rules_amount_excluded_By_Item_step2=</mark></p><p><mark style="color:orange;">(Price_AfterDiscountCatalog_by_item-Cart_rules_amount_excluded_By_Item_step1)/Quantity of the product</mark> </p><p><mark style="color:orange;">US: MOCCT-006</mark></p></td></tr><tr><td></td><td><p><mark style="color:orange;"><strong>Step_Price_after_Cart_rules_amount_By_Item</strong></mark></p><p><mark style="color:orange;">Description : Retrieve the price HT after the last discount.</mark> </p><p><mark style="color:orange;">Formula : Price_after_Cart_rules_amount_By_Item =</mark></p><ul><li><mark style="color:orange;">if no discount retrieve Step_Price_AfterDiscountCatalog_by_item</mark></li></ul><ul><li><mark style="color:orange;">if the last discount is amount excluded retrieve</mark></li></ul><p>     <mark style="color:orange;">Cart_rules_amount_excluded_By_Item_step2</mark></p><ul><li><mark style="color:orange;">if the last discount is amount included retrieve TBD in another US</mark></li></ul><ul><li><mark style="color:orange;">if the last discount is percent excluded retrieve TBD in another US</mark></li></ul><ul><li><mark style="color:orange;">if the last discount is amount included retrieve TBD in another US</mark></li></ul><p><mark style="color:orange;">US : MOCCT-006</mark></p></td></tr><tr><td>2</td><td><p><mark style="color:orange;"><strong>Step_Cart_rules_amount_excluded_By_Item_prorata_display_included</strong></mark></p><p><mark style="color:orange;">Description : If the amount defined in the cart rules is Taxes excluded but the display in the FO is Taxes included we calculate the amount included corresponding to the amount excluded to display it in the chart.</mark></p><p><mark style="color:orange;">Formula :</mark> </p><p><mark style="color:orange;">Cart_rules_amount_excluded_By_Item_prorata_display_included</mark> = <mark style="color:orange;">(Precedent unit price taxes excluded * quantity of the current item)/Sum of each item (Precedent unit price taxes excluded * quantity of the current item) * (amount of the discount taxes excluded )*((1+ (Taxes of the item/100))</mark></p><p><mark style="color:orange;">US : MOCCT-006</mark></p></td></tr><tr><td></td><td></td></tr><tr><td>2</td><td><p><mark style="color:orange;"><strong>Step_Price_after_Cart_rules_amount_By_Item</strong></mark></p><p><mark style="color:orange;">Description : Retrieve the unit price taxes excluded after discount Cart_rules_amount_excluded_By_Item_step2 if amount different of 0 else last unit price without taxes</mark> </p><p><mark style="color:orange;">Formula : NA</mark></p><p><mark style="color:orange;">US : MOCCT-006</mark></p></td></tr><tr><td>2</td><td><h4>Step_Taxes_excluded_By_item</h4><p>Description: Calculation of taxes excluded (By_item_Taxes_excluded) for each product</p><p>Formula: </p><p>Taxes_excluded_By_item = <del><mark style="color:orange;">Step_CP_Q_By_item (because no discount)</mark></del>                <mark style="color:orange;">Price_after_Cart_rules_amount_By_Item *</mark>  <mark style="color:orange;">Quantity of the product</mark></p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a>, <mark style="color:orange;">MOCCT-006</mark></p></td></tr><tr><td>1</td><td><h4>Step_Taxes_excluded_Total</h4><p>Description: Calculation of total taxes excluded (Total_Taxes_excluded) for all products</p><p>Formula: </p><p>Taxes_excluded_Total = Sum Taxes_excluded_By_item of each product                   </p><p>US: <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_RVAT_By_item </h4><p>Description: Recovery of rate of VAT (RVAT) for each product</p><p>Formula:  Retrieve the VAT of the product by (Country, state, zip code)</p><p>US: MOCCT-001<mark style="color:purple;">,</mark>  MOCCT-003, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_AmountTVATaxExcluded_By_Item</h4><p>Description: Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded_By_Item) for each product </p><p>Formula<mark style="color:red;">:</mark> AmountTVATaxExcluded_By_Item = RVAT_By_Item * Total_Taxes_excluded_By_Item</p><p>US: <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>1</td><td><h4>Step_AmountTVATaxExcluded_Total</h4><p></p><p>Description: Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded) for all products </p><p>Formula: AmountTVATaxExcluded_Total = Sum (RVAT_By_item * Total_Taxes_excluded_By_Item)</p><p>US: <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>1</td><td><p><strong>Step_Shipping_Tax_excluded</strong></p><p>Description: Retrieve the shipping tax excluded (Shipping_tax_excluded)</p><p>Formula: NA         </p><p>US: MOCCT_005</p></td></tr><tr><td>1</td><td><p><mark style="color:orange;"><strong>Step_Discount_Cart_rule_3_Tax_excluded</strong></mark></p><p><mark style="color:orange;">Description : if it is an amount retrieve the amount of the discount tax excluded.</mark></p><p><mark style="color:orange;">Formula : NA</mark></p><p><mark style="color:orange;">US : MOCCT_006</mark></p></td></tr><tr><td>1</td><td><p><mark style="color:orange;"><strong>Step_Sum_Cart_rules_discount_Tax_excluded</strong></mark></p><p><mark style="color:orange;">Description : Calculation of the total of discount tax excluded</mark></p><p><mark style="color:orange;">Formula: Sum of each Step_Discount_Cart_ruleX_Tax_excluded</mark></p><p><mark style="color:orange;">US : MOCCT_006</mark></p></td></tr><tr><td>1</td><td><p><strong>Step_Taxes_excluded_with_shipping_cost_excluded_total</strong></p><p>Description: Calculation of the total tax excluded adding shipping cost excluding</p><p>Formula: Total_tax_excluded_with_shipping_cost_excluded=Shipping_tax_excluded + Taxes_excluded_Total         </p><p>US: MOCCT_005</p></td></tr><tr><td>1</td><td><h4>Step_Taxes_without_shipping_included_Total</h4><p>Description<mark style="color:purple;">:</mark> Calculation of total taxes included(Total_Taxes_excluded) for all product</p><p>Formula<mark style="color:purple;">:</mark></p><p> Taxes_included_Total =  Taxes_excluded_Total + AmountTVATaxExcluded_Total                    </p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td><mark style="color:orange;">1</mark></td><td><p><strong>Step_Shipping_Tax_included</strong></p><p>Description: Retrieve the shipping tax included ( Shipping_tax_included)</p><p>Formula: NA         </p><p>US: MOCCT_005</p></td></tr><tr><td></td><td><p><mark style="color:orange;"><strong>Step_Discount_Cart_rule_3_Tax_included</strong></mark></p><p><mark style="color:orange;">Description : Amount taxe included of the discount</mark></p><p><mark style="color:orange;">Formula : Case the discount is an amount taxes excluded</mark></p><p> <mark style="color:orange;">Sum for each item (Cart_rules_amount_excluded_By_Item_prorata_display_included)</mark></p><p><mark style="color:orange;">US : MOCCT_006</mark></p></td></tr><tr><td></td><td><p><mark style="color:orange;"><strong>Step_Sum_Cart_rules_discount_Tax_included</strong></mark></p><p><mark style="color:orange;">Description : Calculation of the total of discount taxes included</mark></p><p><mark style="color:orange;">Formula: Sum of each Step_Discount_Cart_ruleX_Tax_included</mark></p><p><mark style="color:orange;">US : MOCCT_006</mark></p></td></tr><tr><td></td><td><h4>Step_Taxes_included_with_shipping_cost_included_total</h4><p>Description: Calculation of the total tax included adding shipping cost including</p><p>Formula:</p><p>Total_tax_included_with_shipping_cost_included =  Taxes_without_shipping_included_Total + Shipping_tax_included                  </p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a>, MOCCT_005</p></td></tr></tbody></table>

####





####



####





####





\










### Behat test link
