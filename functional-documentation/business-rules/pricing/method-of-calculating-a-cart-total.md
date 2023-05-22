# Method Of Calculating a Cart Total

US

| US                                           | Descpription                                                                                                                                     | Examples                                                                                                                                                                                                                       |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <mark style="color:purple;">MOCCT-001</mark> | <mark style="color:purple;">Case without reduction for ONE article and fixed VAT</mark> - without decimal and rounding                           | <mark style="color:purple;">Examples for the case MOCCT-001. Click</mark> [<mark style="color:purple;">here</mark>](https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=0)            |
| <mark style="color:orange;">MOCCT-002</mark> | <mark style="color:orange;">MOCCT\_001 for a product with more than one for quantity - without decimal and rounding</mark>                       | <mark style="color:orange;">Examples for the case MOCCT-002</mark>      [<mark style="color:orange;">Click here</mark>](https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=43061852) |
| <mark style="color:green;">MOCCT\_003</mark> | <mark style="color:green;">MOCCT\_002 with rational number only</mark>                                                                           | <mark style="color:green;">Examples for the case MOCCT-003</mark> [<mark style="color:green;">Click here</mark>](https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=1249928607)      |
| <mark style="color:red;">MOCCT\_004</mark>   | <mark style="color:red;">MOCCT- 004 : Case without reduction for differents articles with a quantity > 1/ fixed VAT/with rational numbers</mark> |                                                                                                                                                                                                                                |

Steps of the price calculation

| Step                                                                                 | Descpription                                                                                                                                                                                                                                                                                       | Formule                                                                                                                                                                                                                                                                                                                                                                                                                                                            | US                                                                                                                                     |
| ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| <mark style="color:purple;">Step\_SP</mark>                                          | <mark style="color:purple;">Retrieve the standard price for</mark> <mark style="color:purple;"></mark>~~<mark style="color:purple;">one</mark>~~ <mark style="color:red;">each</mark> <mark style="color:purple;">product (SP)</mark>                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | <mark style="color:purple;">MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>                                               |
| <mark style="color:purple;">Step\_IP</mark>                                          | <mark style="color:purple;">Retrieve the impact Price (IP)</mark> <mark style="color:red;">for each product</mark>                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | <mark style="color:purple;">MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>                                               |
| <p></p><p><mark style="color:purple;">Step_CP</mark></p><p></p>                      | <mark style="color:purple;">Calculation of the price of the combination HT (CP)</mark> <mark style="color:purple;"></mark><mark style="color:red;"><mark style="color:purple;">for<mark style="color:purple;"></mark> <mark style="color:red;"></mark><mark style="color:red;">each product</mark> | <mark style="color:purple;">CP = SP + IP</mark>                                                                                                                                                                                                                                                                                                                                                                                                                    | <mark style="color:purple;">MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>                                               |
| <p></p><p><mark style="color:purple;">Step_RVAT</mark> </p><p> </p>                  | <mark style="color:purple;">Recovery of rate of VAT (RVAT)</mark>                                                                                                                                                                                                                                  | <mark style="color:purple;">to dig into the specifications (Country, state, zip code) - For now ARBITRARY fixed to 20%</mark>                                                                                                                                                                                                                                                                                                                                      | <mark style="color:purple;">MOCCT-001</mark>                                                                                           |
| <mark style="color:purple;">Step\_AmountTVATaxExcluded</mark>                        | <p><mark style="color:purple;">Calculation of VAT amount on unit price before tax (AmountTVATaxExcluded)</mark></p><p><mark style="color:red;">for each product</mark> </p>                                                                                                                        | <mark style="color:purple;">AmountTVATaxExcluded = RVAT \* CP</mark>                                                                                                                                                                                                                                                                                                                                                                                               | <mark style="color:purple;">MOCCT-001,</mark> <mark style="color:red;">MOCCT\_004</mark>                                               |
| <mark style="color:orange;">Step\_Quantity\_Recovery</mark>                          | <mark style="color:orange;">Recovery of the quantité of CP (Q)</mark> <mark style="color:red;">for each product</mark>                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | <mark style="color:orange;">MOCCT-002,</mark> <mark style="color:red;">MOCCT\_004</mark>                                               |
| <p></p><p> <mark style="color:purple;">Step_Total_Taxes_excluded</mark></p>          | <p><mark style="color:purple;">Calculation of total taxes excluded (Total_Taxes_excluded)</mark> <mark style="color:red;">for all products</mark></p><p></p>                                                                                                                                       | <p><del><mark style="color:purple;">The quantity Q is consider to 1 arbitrary</mark></del></p><p> <del><mark style="color:purple;">Total_Taxes_excluded = 1 * CP</mark></del><mark style="color:purple;">  </mark>                   </p><p> <mark style="color:red;">For all products</mark> <mark style="color:orange;">Total_Taxes_excluded =</mark> <mark style="color:red;">For all products sum of</mark> <mark style="color:orange;">Q * CP</mark>     </p> | <mark style="color:purple;">MOCCT-001,</mark> <mark style="color:orange;">MOCCT-002,</mark> <mark style="color:red;">MOCCT\_004</mark> |
|                                                                                      |                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                        |
| <p></p><p><mark style="color:purple;">Step_Shipping_costs</mark> </p>                | <mark style="color:purple;">Recovery of Shipping cost Taxes excluded (Shipping\_costs)</mark>                                                                                                                                                                                                      | <p><mark style="color:purple;">Arbitrary</mark> </p><p><mark style="color:purple;">Shipping_costs = 10%</mark></p>                                                                                                                                                                                                                                                                                                                                                 | <mark style="color:purple;">MOCCT-001</mark>                                                                                           |
| <mark style="color:purple;">Step\_Total\_Tax\_Excluded\_with\_Shipping\_costs</mark> |  <mark style="color:purple;">Calculation tax excluded of the total with shipping costs (Total\_Tax\_Excluded\_with\_Shipping\_costs)</mark>                                                                                                                                                        | <p></p><p><mark style="color:purple;">Total_Tax_Excluded_with_Shipping_costs</mark> </p><p><mark style="color:purple;"><strong>=</strong></mark> <mark style="color:red;">Sum for each products (CP * (</mark><del><mark style="color:purple;">1</mark></del> <mark style="color:orange;">Q+ RVAT + Shipping_costs))</mark></p>                                                                                                                                    | <mark style="color:purple;">MOCCT-001,</mark> <mark style="color:orange;">MOCCT-002,</mark> <mark style="color:red;">MOCCT-004</mark>  |
|                                                                                      |                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                        |
|                                                                                      |                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                        |

CP + CP\*TVA + CP\*Shipping\_cost







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

Voir avec [Hibatallah Aouadni](http://localhost:5000/u/VFTPTXvHkhc2P65TG4Ec8RBDcyF2 "mention") si elles pensent à d'autres endroit ou les règles changent

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



Algo :thumbsup:

0\. Specific price on P1 (par produit)



\


