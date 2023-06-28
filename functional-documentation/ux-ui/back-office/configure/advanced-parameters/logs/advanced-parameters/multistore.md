# Multistore

Main interface of the Multistore configuration page. In this section, all the general Multistore settings can be adjusted.

<figure><img src="../../../../../../../.gitbook/assets/image (128).png" alt=""><figcaption><p>Multistores main page User Interface</p></figcaption></figure>

### Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* Saving Button (todo link)

## Multistore tree block

The section contains the tree segmentation icon, title _Multistore tree,_ additional buttons from [Buttons with icons UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons) and the tree content.

* **Icon** - identifies the section theme.
* **Multistore tree** - unique name of the section.
* **Collapse All** - button, once clicked, collapses all the Multistore tree interface scheme.
* **Expand All** - button, once clicked, expands all the Multistore tree interface scheme.
* **Content of the tree** - it is displayed in this hierarchic structure:\

*   _Folder name (with the folder icon);_

    * _Prestashop Multistore name (bolded text);_
      * _URL of Multistore (bolded text);_



## Multistore listing block

The section contains the title _Multistore_ and the content.&#x20;

### Sorting section

* **ID** - the ID's of the Multistores can be sorted by ascending and descending arrangement (A-Z, 0-9 or Z-A, 9-0) by toggling the clicking of the small triangles icons. After each triangle click, the listing will refresh with the page load.&#x20;
* **Shop group** - the Shop Groups of the Multistores can be sorted by ascending and descending arrangement (A-Z, 0-9 or Z-A, 9-0) by toggling the clicking of the small triangles icons. After each triangle click, the listing will refresh with the page load.&#x20;

### Filtering section

#### ID filtering input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">Please fill at least one field to perform a search in this list.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty field</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="multistore.md#bahavior-of-id-filtering-input">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of ID filtering input

After typing numbers or letters, the search returns the results in the Multistore content section. If there are no results found, the section will contain an Exclamation mark icon warning and _No records found message_.

#### Shop group input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">Please fill at least one field to perform a search in this list.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>Empty field</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>1</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>Unlimited</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="multistore.md#bahavior-of-id-filtering-input">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of Shop group input

After typing numbers or letter, the search returns the results in the Multistore content section. If there are no results found, the section will contain an Exclamation mark icon warning and _No records found message_.

#### Search CTA button

Button from [Buttons with icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). Click initiates searching action.

#### Reset CTA button

Yellow button from [Buttons with icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). Click initiates resetting and clearing the filtering inputs action.

## Multistore options section

The block header contains a gear-style icon and, title _Multistore options_ and the content. The content contains a single dropdown.

### Default shop dropdown

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>First shop in list.</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="multistore.md#behavior-of-shop-group-input-1">Behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Behavior of Default shop dropdown

The element is a single dropdown component, with the selections of the whole shop names. It defines the Default shop in the whole webshop.

#### Saving button CTA

Saving button CTA.&#x20;
