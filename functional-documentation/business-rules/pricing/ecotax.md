# Ecotax

## Add ecotax on the general workflow look at [this page](./)

## Business rule description

This business rules correspond to this part of the [sheet-pricing ](https://docs.google.com/spreadsheets/d/1yHwk9nc1Ab9T6s-fqybFpm6P8ejGac-SpO6miR39uOY/edit#gid=538880055):

![](<../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1).png>)

**(prix de vente H.T + TVA) + (écotaxe + TVA à 19,6%) = prix à payer par le consommateur**

Si le commerçant fait une remise, celle-ci ne doit pas être appliquée sur l’écotaxe. Le calcul sera donc le suivant :

**((prix de vente H.T – remise) + TVA) + ( écotaxe + TVA à 19,6%) = prix remisé à payer**

<mark style="color:red;">**==> dans nos calculs 20 semble utilisé**</mark>

{% embed url="https://www.wizishop.fr/blog/ecotaxe-et-e-commerce-comment-retranscrire-lecotaxe-sur-la-facture-client.html" %}
lien formule ecotax
{% endembed %}

### UX/UI impact of this BR

todo

### Behat test link
