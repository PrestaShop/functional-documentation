# Customer activity tracking

## Description

In this tab, you can view all your customers' actions related to their personal data (especially for data accessibility, permission and deletion).&#x20;



[A link to related tests](https://build.prestashop.com/test-scenarios/scenarios/core/functional/bo/catalog/attributes-and-features/attributes.html) (TODO)

<figure><img src="../../../../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

## Components description

[<mark style="color:red;">https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar</mark>](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--toolbar)

### A component description

Customer activity list

1\) A text "Keep track of your customer activity related to data accessibility, consent and erasure."

2\) Show x entries

3\) Export

Copy button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Copy</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_TRACKING_001</td><td align="center">-</td><td></td></tr></tbody></table>

Excel button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Excel</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_TRACKING_002</td><td align="center">-</td><td></td></tr></tbody></table>

CSV button&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>CSV</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_TRACKING_003</td><td align="center">-</td><td></td></tr></tbody></table>

PDF

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>PDF</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_TRACKING_004</td><td align="center">-</td><td></td></tr></tbody></table>

4\) Search TODO add the component.&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>PDF</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>BO_GDPR_TRACKING_005</td><td align="center">-</td><td></td></tr><tr><td></td><td></td><td align="center"></td><td></td></tr></tbody></table>

5\) Summary table

In this summary table, you will find the information below:

* Customer's first and last name or client ID
* Type of request: data accessibility, permission, or deletion
* Date and time of the action

## Behaviors description

### Workflow

NA



### Behavior description

BO\_GDPR\_TRACKING\_001 : Let to copy the Summary table (TODO add a link to 5)) in the buffer

BO\_GDPR\_TRACKING\_002 : Let to download an Excel file with datas of the Summary table&#x20;

{% file src="../../../../../.gitbook/assets/Module Manager • PrestaShop.xlsx" %}

BO\_GDPR\_TRACKING\_003 : Let to download a csv file with datas of the Summary table&#x20;

{% file src="../../../../../.gitbook/assets/Module Manager • PrestaShop.csv" %}



BO\_GDPR\_TRACKING\_004 : : Let to download a PDF file with datas of the Summary table&#x20;

{% file src="../../../../../.gitbook/assets/Module Manager • PrestaShop.pdf" %}

BO\_GDPR\_TRACKING\_005 This search let to filter on Client name/Id and Type of request in the table.



## Error messages

This section COULD list all errors messages / Exceptions for the page / workflow

## Limitations

This section SHOULD list limitations of the page.



