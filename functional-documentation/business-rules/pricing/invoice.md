# Invoice

Associated to [MOCCT-014](https://github.com/PrestaShop/PrestaShop/issues/33846)

## Description

Cas of an Invoice without (specific, price, catalog, price rules or group customer)

<figure><img src="../../../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

2  - Retrieve all the Name of products present in the chart

3 - The  rate associate to each product

4 - The price tax excluded as displayed in the catalog of the FO

5 - The quantity of products added in the chart

6 - Retrieve the data of [Step\_CP\_Q\_By\_item](method-of-calculating-a-cart-total-mocct.md#step\_cp\_q\_by\_item)

7 - The list of discount apply on the chart in the same order as this one apply in the chart : Retrieve all [Step\_Discount\_Cart\_rule\_X\_Tax\_excluded](method-of-calculating-a-cart-total-mocct.md#steps-of-the-price-calculation)

8 - List of products 9 - aggregate by taxes and shipping

10 - Base of price after apply discounts [Step\_Taxes\_excluded\_By\_Item ](method-of-calculating-a-cart-total-mocct.md#step\_taxes\_excluded\_by\_item)and aggregate by taxes

11 - Taxes associated to 10- C Attention delta entre 10% de 176,42 et 17.67

12 - <mark style="color:red;">Ajouter cette étape après avoir fait les US arrondis</mark>

13 - Retrieve [Step\_Sum\_Cart\_rules\_discount\_Tax\_excluded](method-of-calculating-a-cart-total-mocct.md#step\_taxes\_excluded\_by\_item)

14 - The cost of shipping taxe excmuded

15 - Retrieve Step\_Taxes\_excluded\_with\_shipping\_cost\_excluded\_total

16 - Sum Step\_AmountTVATaxExcluded\_Total + tax shipping <mark style="color:red;">(TODO or sum of taxes of invoice ?)</mark>

17 - Retrieve [Step\_Taxes\_included\_with\_shipping\_cost\_included\_total](method-of-calculating-a-cart-total-mocct.md#step\_taxes\_included\_with\_shipping\_cost\_included\_total)

18 - Retrieve [Step\_Taxes\_included\_with\_shipping\_cost\_included\_total](method-of-calculating-a-cart-total-mocct.md#step\_taxes\_included\_with\_shipping\_cost\_included\_total)





