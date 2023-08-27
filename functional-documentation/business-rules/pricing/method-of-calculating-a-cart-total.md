---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description



<table><thead><tr><th width="113">US (link to Github)</th><th>Descpription</th></tr></thead><tbody><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32592">MOCCT-001</a></td><td>For one article, Quantity 1, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32274">MOCCT-002</a></td><td>For one article, Quantity <strong>parametrable</strong>, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/33684">MOCCT-003</a></td><td>For one article, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT <strong>parametrable</strong>, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></td><td>For <strong>several</strong> items, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT parametrable, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/33691">MOCCT_005</a></td><td><mark style="color:orange;">For <strong>several</strong> items, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT parametrable, <strong>shipping including</strong> - Total Tax excluded, Tax included</mark></td></tr></tbody></table>

### Steps of the price calculation

Level 1 is the list of one or several products or value shared by all productd

Level 2 is for each product

<table><thead><tr><th width="94">Level</th><th>Formula</th></tr></thead><tbody><tr><td>2</td><td><h4>Step_SP_by_item</h4><p>Description: Retrieve the standard price for each product (SP) </p><p>Formula: NA</p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_IP_by_item</h4><p>Description: Retrieve the impact Price (IP) for each product</p><p>Formula: NA</p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_CP_by_item</h4><p>Description: Calculation of the price of the combination HT (CP) for each product</p><p>Formula : CP_by_item = SP_by_item + IP_by_item</p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_CP_Q_by_item</h4><p>Description: Calculation of the price total (Tax excl) taking into account quantity for each product</p><p>Formula : CP_Q_by_item = CP_by_item * Quantity of the product)</p><p>US : MOCCT-001, MOCCT-002, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_Taxes_excluded_By_item</h4><p>Description: Calculation of taxes excluded (By_item_Taxes_excluded) for each product</p><p>Formula: </p><p>Taxes_excluded_By_item = Step_CP_Q_By_item (because no discount)                   </p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>1</td><td><h4>Step_Taxes_excluded_Total</h4><p>Description: Calculation of total taxes excluded (Total_Taxes_excluded) for all products</p><p>Formula: </p><p>Taxes_excluded_Total = Sum Taxes_excluded_By_item of each product                   </p><p>US: <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_RVAT_By_item </h4><p>Description: Recovery of rate of VAT (RVAT) for each product</p><p>Formula:  Retrieve the VAT of the product by (Country, state, zip code)</p><p>US: MOCCT-001<mark style="color:purple;">,</mark>  MOCCT-003, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>2</td><td><h4>Step_AmountTVATaxExcluded_By_Item</h4><p>Description: Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded_By_Item) for each product </p><p>Formula<mark style="color:red;">:</mark> AmountTVATaxExcluded_By_Item = RVAT_By_Item * Total_Taxes_excluded_By_Item</p><p>US: <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td>1</td><td><h4>Step_AmountTVATaxExcluded_Total</h4><p></p><p>Description: Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded) for all products </p><p>Formula: AmountTVATaxExcluded_Total = Sum (RVAT_By_item * Total_Taxes_excluded_By_Item)</p><p>US: <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td><mark style="color:orange;">1</mark></td><td><p><mark style="color:orange;"><strong>Step_Shipping_Tax_excluded</strong></mark></p><p><mark style="color:orange;">Description: Retrieve the shipping tax excluded (Shipping_tax_excluded)</mark></p><p><mark style="color:orange;">Formula: NA</mark>         </p><p><mark style="color:orange;">US: MOCCT_005</mark></p></td></tr><tr><td>1</td><td><p><mark style="color:orange;"><strong>Step_tax_excluded_with_shipping_cost_excluded_total</strong></mark></p><p><mark style="color:orange;">Description: Calculation of the total tax excluded adding shipping cost excluding</mark></p><p><mark style="color:orange;">Formula: Total_tax_excluded_with_shipping_cost_excluded=Shipping_tax_excluded + Taxes_excluded_Total</mark>         </p><p><mark style="color:orange;">US: MOCCT_005</mark></p></td></tr><tr><td>1</td><td><h4>Step_Taxes_<mark style="color:orange;">without_shipping</mark>_included_Total</h4><p>Description<mark style="color:purple;">:</mark> Calculation of total taxes included(Total_Taxes_excluded) for all product</p><p>Formula<mark style="color:purple;">:</mark></p><p> Taxes_included_Total =  Taxes_excluded_Total + AmountTVATaxExcluded_Total                    </p><p>US: MOCCT-001, <a href="https://github.com/PrestaShop/PrestaShop/issues/32602">MOCCT_004</a></p></td></tr><tr><td><mark style="color:orange;">1</mark></td><td><p><mark style="color:orange;"><strong>Step_Shipping_Tax_included</strong></mark></p><p><mark style="color:orange;">Description: Retrieve the shipping tax included ( Shipping_tax_included)</mark></p><p><mark style="color:orange;">Formula: NA</mark>         </p><p><mark style="color:orange;">US: MOCCT_005</mark></p></td></tr><tr><td></td><td><h4><mark style="color:orange;">Step_Taxes_included_with_shipping_cost_included_total</mark></h4><p><mark style="color:orange;">Description: Calculation of the total tax included adding shipping cost including</mark></p><p><mark style="color:orange;">Formula:</mark></p><p><mark style="color:orange;">Total_tax_included_with_shipping_cost_included =  Taxes_without_shipping_included_Total + Shipping_tax_included</mark>                  </p><p><mark style="color:orange;">US: MOCCT-001,</mark> <a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a><mark style="color:orange;">, MOCCT_005</mark></p></td></tr></tbody></table>

####





####



####





####





\


