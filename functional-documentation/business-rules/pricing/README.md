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

### Behat test link
