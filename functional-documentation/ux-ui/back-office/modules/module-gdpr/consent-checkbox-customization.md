# Consent checkbox customization

## Description

This tab allows you customize the consent confirmation checkboxes and the corresponding consent request messages in various forms of your store. You can activate and customize the consent confirmation checkboxes in two places by default:

* In the account creation form on your store
* In the Information tab in the customer account

&#x20; [A link to related tests](https://build.prestashop.com/test-scenarios/scenarios/core/functional/bo/catalog/attributes-and-features/attributes.html) (TODO)

<figure><img src="../../../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

## Components description

<mark style="color:red;"></mark>[<mark style="color:red;">https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar</mark>](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar)<mark style="color:red;"></mark>

### A component description

<mark style="color:red;">****</mark>

1. <mark style="color:red;">**The component is a common component with a standard behavior described in the**</mark> [<mark style="color:red;">**UI/KIT**</mark>](https://build.prestashop.com/prestashop-ui-kit/?path=/story/modals--modal) <mark style="color:red;">**or Design System : it must be a link to the UI/KIT or DS**</mark>
2. <mark style="color:red;">**Otherwise the component MUST be described as a Table as described bellow**</mark>



Point d'attention

We recommend you to put a link to your confidentiality policy page in each of your custom messages. Be aware that a dedicated confidentiality policy page is required on your website; if you do not have one yet, please click [here](https://maboutique801.demo-niak.prestashop.net/ps-admin/index.php/improve/design/cms-pages/?\_token=60HU2c9\_EfWtEJ3SUBe1-7lQzBocXZwtzEqE9maojd8).



1\) Account creation form

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Yes ????</mark> </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><p><mark style="color:red;">BO_GDPR_CONSENT_001</mark></p><p><mark style="color:red;">Ajouter la condition si Yes on a le bloc Consent request message sinon non. A vérifier</mark></p></td><td align="center">-</td><td></td></tr></tbody></table>

Consent request message

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>J'accepte les conditions générales et la politique de confidentialité</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>NA</td><td align="center">-</td><td></td></tr></tbody></table>

Menu déroulant avec la langue <mark style="color:red;">**link to the UI/KIT or DS**</mark>

<mark style="color:red;">****</mark>

2\) Customer account area

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Yes ????</mark> </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_CONSENT_002</td><td align="center">-</td><td></td></tr></tbody></table>

Consent request message

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>J'accepte les conditions générales et la politique de confidentialité</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>NA</td><td align="center">-</td><td></td></tr></tbody></table>

Menu déroulant avec la langue <mark style="color:red;">**link to the UI/KIT or DS**</mark>

<mark style="color:red;">****</mark>

3\) Newsletter subscription <mark style="color:red;">(pourquoi en gras et pas les précédent ? et icône en plus)</mark>

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Yes ????</mark> </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_CONSENT_003</td><td align="center">-</td><td></td></tr></tbody></table>

Consent request message

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Pourquoi vide ?</mark></td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>NA</td><td align="center">-</td><td></td></tr></tbody></table>

Menu déroulant avec la langue <mark style="color:red;">**link to the UI/KIT or DS**</mark>

<mark style="color:red;">****</mark>

4\) Product Comments <mark style="color:red;">(pourquoi en gras et pas les précédent ? et icône en plus)</mark>

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Yes ????</mark> </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_CONSENT_004</td><td align="center">-</td><td></td></tr></tbody></table>

Consent request message

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Pourquoi vide ?</mark></td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>NA</td><td align="center">-</td><td></td></tr></tbody></table>

Menu déroulant avec la langue <mark style="color:red;">**link to the UI/KIT or DS**</mark>

<mark style="color:red;">****</mark>

5\) Contact form <mark style="color:red;">(pourquoi en gras et pas les précédent ? et icône en plus)</mark>

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Yes ????</mark> </td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_CONSENT_005</td><td align="center">-</td><td></td></tr></tbody></table>

Consent request message

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td><mark style="color:red;">Pourquoi vide ?</mark></td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>NA</td><td align="center">-</td><td></td></tr></tbody></table>

Menu déroulant avec la langue <mark style="color:red;">**link to the UI/KIT or DS**</mark>

<mark style="color:red;">****</mark>

Point d'attention

For other installed modules requiring consent confirmation, they will be displayed in this tab only if they have done the GDPR update. The corresponding fields will automatically appear in order for you to customize the consent confirmation checkboxes



Bouton Save <mark style="color:red;">**link to the UI/KIT or DS cf Behavior B6 W1 save the data of the form and stay on the form**</mark>

##

## Behaviors description

### Workflow

W1 :  <mark style="color:red;">A compléter</mark>



### Behavior description



For other installed modules requiring consent confirmation, they will be displayed in this tab only if they have done the GDPR update. The corresponding fields will automatically appear in order for you to customize the consent confirmation checkboxes

<mark style="color:red;">BO\_GDPR\_CONSENT\_001</mark> : Account creation form <mark style="color:red;">Ajouter la condition si Yes on a le bloc Consent request message sinon non. A vérifier</mark>

BO\_GDPR\_CONSENT\_002 : Customer account area

BO\_GDPR\_CONSENT\_003 : Newsletter subscription

BO\_GDPR\_CONSENT\_004 : Product Comments

BO\_GDPR\_CONSENT\_005 : Contact form



## Error messages

This section COULD list all errors messages / Exceptions for the page / workflow

## Limitations

This section SHOULD list limitations of the page.
