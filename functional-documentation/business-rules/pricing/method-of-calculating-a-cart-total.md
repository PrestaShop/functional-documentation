---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description



<table><thead><tr><th width="113">US (link to Github)</th><th>Descpription</th></tr></thead><tbody><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32592">MOCCT-001</a></td><td>For one article, Quantity 1, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32274">MOCCT-002</a></td><td>For one article, Quantity <strong>parametrable</strong>, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/33684">MOCCT-003</a></td><td>For one article, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT <strong>parametrable</strong>, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></td><td><mark style="color:orange;">For <strong>several</strong> items, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT parametrable, no shipping</mark></td></tr></tbody></table>

### Steps of the price calculation

Level 1 is the list of one or several products

Level 2 is for each product

<table><thead><tr><th width="94">Level</th><th>Formula</th></tr></thead><tbody><tr><td>2</td><td><h4>Step_SP<mark style="color:orange;">_by_item</mark></h4><p>Description: Retrieve the standard price for <del><mark style="color:orange;">one</mark></del><mark style="color:orange;">  each</mark> product (SP) </p><p>Formula: NA</p><p>US: MOCCT-001<mark style="color:orange;">,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>2</td><td><h4>Step_IP<mark style="color:orange;">_by_item</mark></h4><p>Description: Retrieve the impact Price (IP) <mark style="color:orange;">for each product</mark></p><p>Formula: NA</p><p>US: MOCCT-001<mark style="color:orange;">,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>2</td><td><h4>Step_CP<mark style="color:orange;">_by_item_by_item</mark></h4><p>Description: Calculation of the price of the combination HT (CP) for <del><mark style="color:orange;">this</mark></del><mark style="color:orange;">  each</mark> product</p><p>Formula : CP<mark style="color:orange;">_by_item</mark> = SP<mark style="color:orange;">_by_item</mark> + IP<mark style="color:orange;">_by_item</mark></p><p>US: MOCCT-001<mark style="color:orange;">,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>2</td><td><h4>Step_CP_Q<mark style="color:orange;">_by_item</mark></h4><p>Description: Calculation of the price total (Tax excl) taking into account quantity for <del><mark style="color:orange;">this</mark></del><mark style="color:orange;">  each</mark> product</p><p>Formula : CP_Q<mark style="color:orange;">_by_item</mark> = CP<mark style="color:orange;">_by_item</mark> * Quantity of the product)</p><p>US : MOCCT-001<mark style="color:orange;">,</mark> MOCCT-002<mark style="color:orange;">,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>2</td><td><h4>Step<mark style="color:orange;">_</mark><del><mark style="color:orange;">Total-</mark></del>Taxes_excluded_<mark style="color:orange;">By_item</mark></h4><p>Description: Calculation of <del><mark style="color:orange;">total</mark></del> taxes excluded (<mark style="color:orange;">By_item</mark>_Taxes_excluded) <mark style="color:orange;">for each product</mark></p><p>Formula: </p><p><del><mark style="color:orange;">Total_</mark></del>Taxes_excluded_<mark style="color:orange;">By_item</mark> = Step_CP_Q_<mark style="color:orange;">By_item</mark> (because no discount)                   </p><p>US: MOCCT-001<mark style="color:orange;">,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>1</td><td><h4><mark style="color:orange;">Step_Taxes_excluded_Total</mark></h4><p><mark style="color:orange;">Description: Calculation of total taxes excluded (Total_Taxes_excluded) for all products</mark></p><p><mark style="color:orange;">Formula:</mark> </p><p><mark style="color:orange;">Taxes_excluded_Total = Sum Taxes_excluded_By_item of each product</mark>                   </p><p><mark style="color:orange;">US:</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>2</td><td><h4>Step_RVAT<mark style="color:orange;">_By_item</mark> </h4><p>Description: Recovery of rate of VAT (RVAT) <mark style="color:orange;">for each product</mark></p><p>Formula:  Retrieve the VAT of the product by (Country, state, zip code)</p><p>US: MOCCT-001<mark style="color:purple;">,</mark>  MOCCT-003<mark style="color:orange;">,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>2</td><td><h4>Step_AmountTVATaxExcluded<mark style="color:orange;">_By_Item</mark></h4><p>Description: Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded_<mark style="color:orange;">By_Item</mark>) for <del><mark style="color:orange;">this</mark></del><mark style="color:orange;">  each</mark> product </p><p>Formula<mark style="color:red;">:</mark> AmountTVATaxExcluded_<mark style="color:orange;">By_Item</mark> = RVAT_<mark style="color:orange;">By_Item</mark> * Total_Taxes_excluded_<mark style="color:orange;">By_Item</mark></p><p>US  : <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>1</td><td><h4><mark style="color:orange;">Step_AmountTVATaxExcluded_Total</mark></h4><p></p><p><mark style="color:orange;">Description: Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded) for all products</mark> </p><p><mark style="color:orange;">Formula: AmountTVATaxExcluded_Total = Sum (RVAT_By_item * Total_Taxes_excluded_By_Item)</mark></p><p><mark style="color:orange;">US:</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr><tr><td>1</td><td><h4>Step<del><mark style="color:orange;">_Total</mark></del>_Taxes_included<mark style="color:orange;">_Total</mark></h4><p>Description<mark style="color:purple;">:</mark> Calculation of total taxes included(Total_Taxes_excluded) for <del><mark style="color:orange;">this</mark></del> all product</p><p>Formula<mark style="color:purple;">:</mark></p><p> <del><mark style="color:orange;">Total_</mark></del>Taxes_included<mark style="color:orange;">_Total</mark> =  Step_<del><mark style="color:orange;">Total_</mark></del>Taxes_excluded_<mark style="color:orange;">Total</mark> + AmountTVATaxExcluded<mark style="color:orange;">_Total</mark>                    </p><p>US: MOCCT-001<mark style="color:orange;">,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></p></td></tr></tbody></table>

####





####



####





####





\


