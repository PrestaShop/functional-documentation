# Search

## Description

This page enables the ability to configure the webshop's searching parameters.

<figure><img src="../../../../../../.gitbook/assets/image (114).png" alt="Search UI"><figcaption><p>Search User Interface</p></figcaption></figure>

## QA

[Link to the tests](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/shop-parameters/search/search.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](../../../../common-components/save-button.md) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/back-office-header/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;
* [Configuration block](../../../../common-components/configuration-block.md)
* 4 table header tools (todo link)
* [Cancel button](../../../../common-components/cancel-button.md)
* [Language dropdown for input fields](../../../../common-components/language-dropdown-for-input-fields.md)

## Add new alias CTA button

Button from the [Buttons with icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons). Clicking the button redirects to the adding a new Alias page.

## Tabs navigation

The page has a navigation component from the [Navigation Pills UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/navigation--navigation-pills). The tabs are:

* **Search** (active tab)
* **Tags**

## **Search section**

The block starts with the title _Search_ and a numeric value of the total search entries.

### 5 table header tools

The top right header side displays the 4 table header tools (todo link), plus another fifth cloud-styled **Import** button. Clicking on this could-style icon will redirect to the Import page of the webshop.

### Sorting the table

Sorting the table uses the [Sorting rules](../../../../common-components/sorting-rules.md) functionality. The sorting headers of the table are:

* **Aliases**
* **Search**

Sorting the **Status** header has only 2 values:

* **Yes**
* **No**

### Table filtering

Table uses standard input fields for filtering. The filtering can be made in these inputs:

* **Aliases**
* **Search**

After the filtering has been inputted, CTA button ([Buttons with Icons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) **Search** can be executed for the search results.

### Table content

By the default installation of the webshop, there are 2 entries already saved to the search engine:

* **Aliases** - bloose, blues
* **Result** - blouse

The rest of the content:

* **Checkbox** - [Forms Checkboxes UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--checkboxes) element. Marks or unmarks the desired selection of entry.
* **Alias name** - displays the alias name.
* **Search query** - displays the final output value of the aliased search query.
* **Status checkmark** - checkmark, that can be Enabled (green checkmark) and Disabled (red cross) by toggle clicking separately.
* **Edit or Delete dropdown** - [Dropdowns With Button Split UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split) component, that lets delete or edit the certain Alias.

### Bulk actions

Clicking on the _Bulk actions_ button allows users to perform bulk actions for selected features (using the checkboxes). A user can:

* **Enable selection** - this button will enable all the checkboxes that are selected.
* **Disable selection** - this button will disable all the checkboxes that are selected.
* **Delete selected** - This button will delete the selected employees. After clicking on "Delete selected", a modal with the title "Delete selection" is opened, asking to confirm or cancel the action: "Are you sure you want to delete the selected item(s)?" (See issue [#14462](https://github.com/PrestaShop/PrestaShop/issues/14462)). The action can be canceled by clicking on the cross or on the cancel button. After clicking on "Delete" button, the selected employee will be deleted, a successful message is displayed "The selection has been successfully deleted."

If nothing is selected, and the execution is made, there will be an [Alert Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) message:

_You must select at least one element to delete._

## Indexing section

The block starts with the gear-style icon and the title _Indexing_.

Furthermore, there are some text paragraphs:

_The "indexed" products have been analyzed by PrestaShop and will appear in the results of a front office search._\
_Indexed products **{numeric value / numeric value}**._

_Building the product index may take a few minutes. If your server stops before the process ends, you can resume the indexing by clicking "Add missing products to the index"._

_**{arrow\_icon} Add missing products to the index** - adds the missing products to the index. Successful attempt indicated by_ [_Alerts Basics UI Kit_](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) _message._

_**{arrow\_icon} Re-build the entire index** - rebuilds entire index of the search. Successful attempt indicated by_ [_Alerts Basics UI Kit_](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) _message._

_You can set a cron job that will rebuild your index using the following URL:_

_{URL\_with\_cronjob\_parameters}_

### Indexing

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable the automatic indexing of products. If you enable this feature, the products will be indexed in the search automatically when they are saved. If the feature is disabled, you will have to index products manually by using the links provided in the field set.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#indexing-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Search section

The section starts with the magnifying-glass-styled icon and the title _Search_.

There are 2 links in the beginning:

_**{arrow\_icon} Signaler un problème sur GitHub** - redirects to the GitHub issues page, where to search for possible bug._

_**{arrow\_icon} Proposer une idée d'amélioration sur GitHub** - redirects to the GitHub issues page, where to report a possible bug._

### Search within word

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>By default, to search for “blouse”, you have to enter “blous”, “blo”, etc (beginning of the word) – but not “lous” (within the word). With this option enabled, it also gives the good result if you search for “lous”, “ouse”, or anything contained in the word.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Enable search within a whole word, rather than from its beginning only. It checks if the searched term is contained in the indexed word. This may be resource-consuming.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#search-within-word-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Search exact end match

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>By default, if you search "book", you will have "book", "bookcase" and "bookend". With this option enabled, it only gives one result “book”, as exact end of the indexed word is matching.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Enable more precise search with the end of the word. It checks if the searched term is the exact end of the indexed word.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#search-exact-end-match-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Fuzzy search

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>By default, the fuzzy search is enabled. It means spelling errors are allowed, e.g. you can search for "bird" with words like "burd", "bard" or "beerd". Disabling this option will require exact spelling for the search to match results.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Enable approximate string matching.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#fuzzy-search-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Maximum approximate words allowed by fuzzy search

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values are allowed.</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>4</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum approximate words allowed by fuzzy search</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Maximum approximate words allowed by fuzzy search field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#maximum-approximate-words-allowed-by-fuzzy-search-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Maximum word length (in characters)

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">field Maximum word length (in characters) is required.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values only allowed.</td><td align="center">The Maximum word length (in characters) field is invalid.</td><td></td></tr><tr><td>Default value</td><td>15</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>This parameter will only be used if the fuzzy search is activated: the lower the value, the more tolerant your search will be.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Maximum word length (in characters)</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">field Maximum word length (in characters) is required.</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>11</td><td align="center">The Maximum word length (in characters) field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#maximum-word-length-in-characters">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Minimum word length (in characters)

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Numeric values only allowed.</td><td align="center">The Maximum word length (in characters) field is invalid.</td><td></td></tr><tr><td>Default value</td><td>English or other language set earlier</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Only words this size or larger will be indexed.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>11</td><td align="center">The Minimum word length (in characters) field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#minimum-word-length-in-characters-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Blacklisted words

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Any characters</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Values with blacklisted words, separated by |</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Please enter the index words separated by a "</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#blacklisted-words-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Weight section

The section starts with the gear-style icon, and a title _Weight_.

The following text is:

_The "weight" represents its importance and relevance for the ranking of the products when completing a new search. A word with a weight of eight will have four times more value than a word with a weight of two._

_We advise you to set a greater weight for words which appear in the name or reference of a product. This will allow the search results to be as precise and relevant as possible._

_Setting a weight to 0 will exclude that field from search index. Re-build of the entire index is required when changing to or from 0_

### Product name weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Product name weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>6</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Product name weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#product-name-weigh-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Reference weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Reference weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>10</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Reference weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Short description weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Short description weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>1</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Short description weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Description weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Description weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>1</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Description weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#description-weight-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Category weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Category weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>3</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Category weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td>link to the behavior</td><td align="center">-</td><td></td></tr></tbody></table>

### Brand weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Brand weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>3</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Brand weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#brand-weight-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Tags weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Tags weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>4</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Tags weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#tags-weight-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Attributes weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Attributes weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>2</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Attributes weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#attributes-weight-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Features weight

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only numeric values allowed.</td><td align="center">The Features weight field is invalid.</td><td></td></tr><tr><td>Default value</td><td>2</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>10</td><td align="center">The Features weight field is invalid.</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="./#features-weight-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Indexing behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Automatically adds every new product to the indexing range.

### Search within word behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. After enabling this function, users can search the desired item within the root of the targeted word, not targeted from the beginning of the word.

### Search exact end match behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. After enabling this function, users can find the desired item (or items) by searching only for the exact word.

### Fuzzy search behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Enabling this functionality, lets users to search between very familiar root words, like _bird_, _bard_, _breed_ etc_._

### Maximum approximate words allowed by fuzzy search behavior

[Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal) component. Specific amount of words can be set, for fuzzy search.

### Maximum word length (in characters) behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Maximum amount of characters can be set, for fuzzy search results tolerance. The lower the value the more tolerant the search will be.

### Minimum word length (in characters) behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Minimum amount of characters can be set, for search results tolerance. The lower the value the more tolerant the search will be.

### Blacklisted words behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. Blacklisted words can be stored in this field, separated by "|" pipe character.

### Product name weigh behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Reference weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Short description weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Description weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Category weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Brand weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Tags weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Attributes weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

### Features weight behavior

[Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story) component. This field represents the importance for the ranking of the products, after executing a new search. Setting a weight to 0 will exclude that field from the search eindex.

## Multistores functionality

This page is [Multistores indpendent](../../../../common-components/multistores-independent.md) page.
