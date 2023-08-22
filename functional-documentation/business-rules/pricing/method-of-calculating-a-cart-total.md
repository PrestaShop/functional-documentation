---
description: Not used in course of maturation
---

# Method Of Calculating a Cart Total

## Description



<table><thead><tr><th width="113">US (link to Github)</th><th>Descpription</th></tr></thead><tbody><tr><td><a href="https://github.com/PrestaShop/PrestaShop/issues/32592"><mark style="color:purple;">MOCCT-001</mark></a></td><td><mark style="color:purple;">For one article, Quantity 1, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</mark></td></tr><tr><td><mark style="color:orange;">MOCCT-002</mark></td><td><mark style="color:orange;">For one article, Quantity parametrable, Without Ecotax, Price without decimal point, without reduction, fixed VAT, no shipping</mark></td></tr></tbody></table>

### Steps of the price calculation

Level 1 is the list of one or several products

Level 2 is for each product

<table><thead><tr><th width="94">Level</th><th>Formula</th></tr></thead><tbody><tr><td><mark style="color:purple;">1</mark></td><td><h4><mark style="color:purple;">Step_SP</mark></h4><p><mark style="color:purple;">Description : Retrieve the standard price for one product (SP)</mark> </p><p><mark style="color:purple;">Formula : NA</mark></p><p><mark style="color:purple;">US : MOCCT-001</mark></p></td></tr><tr><td>2</td><td><h4><mark style="color:purple;">Step_IP</mark></h4><p><mark style="color:purple;">Description : Retrieve the impact Price (IP)</mark></p><p><mark style="color:purple;">Formula : NA</mark></p><p><mark style="color:purple;">US : MOCCT-001</mark></p></td></tr><tr><td>2</td><td><h4><mark style="color:purple;">Step_CP</mark></h4><p><mark style="color:purple;">Description : Calculation of the price of the combination HT (CP) for this product</mark></p><p><mark style="color:purple;">Formula : CP = SP + IP</mark></p><p><mark style="color:purple;">US : MOCCT-001</mark></p></td></tr><tr><td>2</td><td><h4><mark style="color:purple;">Step_CP_Q</mark></h4><p><mark style="color:purple;">Description : Calculation of the price total (Tax excl) taking into account quantity (which is 1 for the MOCCT-001) for this product</mark></p><p><mark style="color:purple;">Formula : CP_Q = CP *</mark><del><mark style="color:orange;">1</mark></del><mark style="color:orange;"> (Quantity of the product)</mark></p><p><mark style="color:purple;">US : MOCCT-001,</mark> <mark style="color:orange;">MOCCT-002</mark></p></td></tr><tr><td>2</td><td><h4><mark style="color:purple;">Step_Total_Taxes_excluded</mark></h4><p><mark style="color:purple;">Description : Calculation of total taxes excluded (Total_Taxes_excluded)</mark> </p><p><mark style="color:purple;">Formula :</mark> </p><p><mark style="color:purple;">Total_Taxes_excluded = Step_CP_Q (because no discount)</mark>                   </p><p><mark style="color:purple;">US : MOCCT-001</mark></p></td></tr><tr><td>2</td><td><h4><mark style="color:purple;">Step_RVAT</mark> </h4><p><mark style="color:purple;">Description : Recovery of rate of VAT (RVAT)</mark> </p><p><mark style="color:purple;">Formula :  For now ARBITRARY fixed to 20% </mark><del><mark style="color:purple;">to dig into the specifications (Country, state, zip code) -</mark></del></p><p><mark style="color:purple;">US : MOCCT-001</mark></p></td></tr><tr><td>2</td><td><h4><mark style="color:purple;">Step_AmountTVATaxExcluded</mark></h4><p><mark style="color:purple;">Description : Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded) for this product</mark> </p><p><mark style="color:purple;">Formula</mark> <mark style="color:red;">:</mark> <mark style="color:purple;">AmountTVATaxExcluded = RVAT * Total_Taxes_excluded</mark></p><p><mark style="color:purple;">US  : MOCCT-001</mark></p></td></tr><tr><td>1</td><td><h4><mark style="color:purple;">Step_Total_Taxes_included</mark></h4><p><mark style="color:purple;">Description : Calculation of total taxes included(Total_Taxes_excluded)</mark> <mark style="color:purple;">for this product</mark></p><p><mark style="color:purple;">Formula :</mark></p><p> <mark style="color:purple;">Total_Taxes_included =  Step_Total_Taxes_excluded + AmountTVATaxExcluded</mark>                    </p><p><mark style="color:purple;">US : MOCCT-001</mark></p></td></tr></tbody></table>

####





####



####





####





\


