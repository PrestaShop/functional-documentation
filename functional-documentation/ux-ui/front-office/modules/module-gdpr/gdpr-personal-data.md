# GDPR - Personal data

## Description

## Description

This page gathers the client's requests concerning

&#x20;\- Access and portability of personal data&#x20;

\-  Right to erasure



[A link to related tests](https://build.prestashop.com/test-scenarios/scenarios/core/functional/bo/catalog/attributes-and-features/attributes.html) (TODO)



<figure><img src="../../../../../.gitbook/assets/image (17).png" alt=""><figcaption><p>GDPR - Personal data</p></figcaption></figure>

### Access to my data

Get My data to pdf (button)

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td> Get my data to pdf</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior/Workflow</td><td><a href="gdpr-personal-data.md#fo_b_gdpr_data_001">FO_W_GDPR_DATA_001</a></td><td align="center">-</td><td>cd829e07342f4c6e9017c9808ca68fba</td></tr></tbody></table>



Get My data to CSV (button)

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td> Get my data to csv</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior/Workflow</td><td><a href="gdpr-personal-data.md#fo_b_gdpr_data_002">FO_B_GDPR_DATA_002</a></td><td align="center">-</td><td>cd829e07342f4c6e9017c9808ca68fba</td></tr></tbody></table>

### Rectification & Erasure requests



<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NA</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>NA</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>You have the right to modify all the personal information found in the "My Account" page. For any other request you might have regarding the rectification and/or erasure of your personal data, please contact us through our <a href="https://maboutique801.demo-niak.prestashop.net/gb/contact-us">contact page</a>. We will review your request and reply as soon as possible.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>NA</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>NA</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>NA</td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior/Workflow</td><td><h4><a href="gdpr-personal-data.md#fo_w_gdpr_data_001-1">FO_W_GDPR_DATA_001</a></h4></td><td align="center">-</td><td>cd829e07342f4c6e9017c9808ca68fba</td></tr></tbody></table>

###

## Behaviors description



### Workflow

#### FO\_W\_GDPR\_DATA\_001

When you click on the contact page link you are redirected to[ Contact us](../../contact-us.md)

### Behavior description (TODO ajouter un mapping décrivant les fichiers ci-dessous)

#### FO\_B\_GDPR\_DATA\_001

Let to download a pdf file with datas of the customer (warning multistore)

{% file src="../../../../../.gitbook/assets/personal-data-2023-03-16.pdf" %}

#### FO\_B\_GDPR\_DATA\_002

Let to download a csv file with datas of the customer

Separator is coma and is base on unicode in UTF-8

{% file src="../../../../../.gitbook/assets/personal-data-_2023-03-16_155020.csv" %}

## Error messages

This section COULD list all errors messages / Exceptions for the page / workflow

## Limitations

This section SHOULD list limitations of the page.
