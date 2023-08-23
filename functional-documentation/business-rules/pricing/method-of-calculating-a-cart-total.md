---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description



<table><thead><tr><th width="113">US (link to Github)</th><th>Descpription</th></tr></thead><tbody><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32592">MOCCT-001</a></td><td>For one article, Quantity 1, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32274">MOCCT-002</a></td><td>For one article, Quantity <strong>parametrable</strong>, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/33684">MOCCT-003</a></td><td>For one article, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT <strong>parametrable</strong>, no shipping</td></tr><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32602"><mark style="color:orange;">MOCCT_004</mark></a></td><td>For <strong>several</strong> items, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, VAT parametrable, no shipping</td></tr></tbody></table>

### Steps of the price calculation

Level 1 is the list of one or several products

Level 2 is for each product

<table><thead><tr><th width="94">Level</th><th>Formula</th></tr></thead><tbody><tr><td><mark style="color:purple;">1</mark></td><td><h4>Step_SP</h4><p>Description : Retrieve the standard price for one product (SP) </p><p>Formula : NA</p><p>US : MOCCT-001</p></td></tr><tr><td>2</td><td><h4>Step_IP</h4><p>Description : Retrieve the impact Price (IP)</p><p>Formula : NA</p><p>US : MOCCT-001</p></td></tr><tr><td>2</td><td><h4>Step_CP</h4><p>Description: Calculation of the price of the combination HT (CP) for this product</p><p>Formula : CP = SP + IP</p><p>US : MOCCT-001</p></td></tr><tr><td>2</td><td><h4>Step_CP_Q</h4><p>Description: Calculation of the price total (Tax excl) taking into account quantity (which is 1 for the MOCCT-001) for this product</p><p>Formula : CP_Q = CP *Quantity of the product)</p><p>US : MOCCT-001<mark style="color:orange;">,</mark> MOCCT-002</p></td></tr><tr><td>2</td><td><h4>Step_Total_Taxes_excluded</h4><p>Description: Calculation of total taxes excluded (Total_Taxes_excluded) </p><p>Formula : </p><p>Total_Taxes_excluded = Step_CP_Q (because no discount)                   </p><p>US : MOCCT-001</p></td></tr><tr><td>2</td><td><h4>Step_RVAT </h4><p>Description: Recovery of rate of VAT (RVAT) </p><p>Formula:  Retrieve the VAT of the product by (Country, state, zip code)</p><p>US : MOCCT-001<mark style="color:purple;">,</mark>  MOCCT-003</p></td></tr><tr><td>2</td><td><h4>Step_AmountTVATaxExcluded</h4><p>Description: Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded) for this product </p><p>Formula <mark style="color:red;">:</mark> AmountTVATaxExcluded = RVAT * Total_Taxes_excluded</p><p>US  : MOCCT-001</p></td></tr><tr><td>1</td><td><h4>Step_Total_Taxes_included</h4><p>Description <mark style="color:purple;">:</mark> Calculation of total taxes included(Total_Taxes_excluded) for this product</p><p>Formula <mark style="color:purple;">:</mark></p><p> Total_Taxes_included =  Step_Total_Taxes_excluded + AmountTVATaxExcluded                    </p><p>US : MOCCT-001</p></td></tr></tbody></table>

####





####



####





####





\


