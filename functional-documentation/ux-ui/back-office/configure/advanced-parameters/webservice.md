# Webservice

Webservice is the page of webservice keys list and webservice configuration block.&#x20;





<figure><img src="../../../../../.gitbook/assets/image (21) (1).png" alt=""><figcaption><p>Webservice user interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (22) (1).png" alt=""><figcaption><p>Webservice list user interface</p></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/advanced-parameters/webservice.html)

## Common components

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../common-components/help-button.md) - [Buttons outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cEqmt5dokN7isI6zTmSs/functional-documentation/ux-ui/common-components/save-button) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [Setting wheel](../../../common-components/settings-wheel.md)&#x20;
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* Search input (todo link)
* [Shop switcher](../../../common-components/shop-switcher.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;

## The UI elements

### Add new webservice key button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Add new webservice key</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#add-new-webservice-key-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable PrestaShop's webservice toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td><p>Before activating the webservice, you must be sure to:</p><ol><li>Check that URL rewriting is available on this server.</li><li>Check that the five methods GET, POST, PUT, DELETE and HEAD are supported by this server.</li></ol></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#enable-prestashopss-webservice-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable CGI mode for PHP toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Before choosing "Yes", check that PHP is not configured as an Apache module on your server.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#enable-cgi-mode-for-php-toggle-switch-bahavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Search key input&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#search-key-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Search description input&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#search-description-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Search button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Search</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#search-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enabled toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>YES</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#enabled-toggle-switch-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Edit icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Edit</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="webservice.md#edit-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Add new webservice key button behavior

Add new webservice key is CTA button ([Buttons with icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) it opens Webservice Accounts page.

### Alert message behavior

On the top of page there is alert message ([Alerts basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/docs/alerts--basics)) and it is:\
_It is preferable to use SSL (https:) for webservice calls, as it avoids the "man in the middle" type security issues._

### **Enable PrestaShops's webservice** toggle switch behavior

This is mandatory on-off toggle switch ([Forms switch story UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story)) in Configuration block.&#x20;

### **Enable CGI mode for PHP toggle switch bahavior**

This is mandatory on-off toggle switch ([Forms switch story UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story)) in Configuration block.&#x20;

### Webservice listing behavior

Webservice block shows the list of created web. Next to the heading of block, there are a number of webservice keys in the list.\
Webservice list is shown when some Keys are created. There are Top block and Content block of list elements.&#x20;

### **Webservice keys sorting by Key behavior**

Once clicked arrow down next to Key title, sorts keys by alphabet from A to Z and keys that start by number in the end. When clicked arrow up - sorts keys from number and then from Z to A.&#x20;

### **Webservice keys sorting by Enabled Behavior**

Once clicked arrow up sorts enabled keys on top. When clicked arrow down - sort disabled keys on top.

### Search key input behavior

This input field ([Forms normal Ui kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) with place holder and it is: _Search key._

### Search description input behavior

This input field ([Forms normal Ui kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) with place holder and it is: _Search description._

### Enabled dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) to filter disabled and enabled keys. By default dropdown is empty and all keys are shown in list.&#x20;

### Search button behavior

Once clicked Search CTA button with icon ([Buttons with icons UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) filters webservice keys by entries in Key, Key description inputs and Enabled dropdown. When hover mouse pointer on it, button color changes.

### Enabled toggle switch

This toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) is is every key row. It enables or disables this particular webservice key.

### Edit icon behavior

Once clicked this icon opens this particular webservice page to make some changes.

### Three-dot menu icon

Once clicked it opens popup with Delete option. When clicked on Delete, deletes the webservice.

### Checkbox behavior&#x20;

**Checkbox** on top of list ([Forms Stylised checkboxes UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)) when marked, mark all webservice keys. When unmarked, unmark all webservice keys. By default this checkbox is unmarked.\
There are checkboxes in each webservice key row. By default all these checkboxes are unmarked.\
When checkboxes marked allows actions of bulk action dropdown ([Dropdowns basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--basics)). There are these options:

* Enable selection - enable marked webservices.
* Disable selection - disable marked webservices.
* Delete selected - deletes marked webservices form the list.

### Key column behavior

This column shows webservice key name of 32 symbols.

### Key description column behavior

This column shows key description.

## Multistores behavior

This page is [Multistores dependent](../../../common-components/multistores-dependent.md) page

