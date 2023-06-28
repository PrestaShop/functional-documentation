# Performance

## Description

In this section, the performance of the shop can be edited.&#x20;

<figure><img src="../../../../../.gitbook/assets/image (57).png" alt="Performance UI"><figcaption><p>Performance User Interface</p></figcaption></figure>

## QA

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/performance.html)

## Common Components

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../common-components/help-button.md) - [Buttons outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cEqmt5dokN7isI6zTmSs/functional-documentation/ux-ui/common-components/save-button) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* Search input (todo link)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;

## Clear cache CTA button

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Clear cache</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#clear-cache-cta-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Smarty block

### Template compilation

The section starts with a bag-style icon and a title _Smarty_.

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Never recompile template files</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#template-compilation-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Cache

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Should be enabled except for debugging.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#cache-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Multi-front optimizations

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Should be enabled if you want to avoid to store the smarty cache on NFS.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#multi-front-optimizations-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Clear cache

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Clear cache everytime something has been modified</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#clear-cache-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Debug mode block

The block starts with the bug-style icon and the title _Debug mode_.

### Disable all overrides

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable or disable all classes and controllers overrides.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#disable-all-overrides-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Debug mode

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable or disable debug mode.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#debug-mode-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Modules block

The block starts with the bug-style icon and the title _Modules_. Next to the title, there is a hoverable helpbox component from the [Helpbox UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/helpbox--helpbox). The hovered text is:

_This feature allows you to identify modules that might be causing bugs on your store. Disable all non-built-in modules (not listed in composer.json). Then, re-enable each module one by one and check that everything works properly before moving on to the next one._

### Disable non built-in modules

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled CTA</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#disable-non-built-in-modules-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Optional features

The block starts with the puzzle-style icon and the title _Optional features_. Next to the title, there is a hoverable helpbox component from the [Helpbox UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/helpbox--helpbox). The hovered text is:

_Some features can be disabled in order to improve performance._

### Combinations

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Choose "No" to disable Product Combinations. You cannot set this parameter to No when combinations are already used by some of your products</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#combinations-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Features

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Choose "No" to disable Product Features.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#features-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Customer groups

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Enabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Choose "No" to disable Customer Groups.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#customer-groups-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## CCC (Combine, Compress and Cache) block

The block starts with the arrow-style icon and the title _CCC (Combine, Compress and Cache_. Next to the title, there is a hoverable helpbox component from the [Helpbox UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/helpbox--helpbox). The hovered text is:

_CCC allows you to reduce the loading time of your page. With these settings you will gain performance without even touching the code of your theme. Make sure, however, that your theme is compatible with PrestaShop 1.7+. Otherwise, CCC will cause problems._

### Smart cache for CSS

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#smart-cache-for-css-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Smart cache for JavaScript

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#smart-cache-for-javascript-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Apache optimization

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>This will add directives to your .htaccess file, which should improve caching and compression.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#apache-optimization-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Media servers (use only with CCC)

The block starts with the arrow-style icon and the title _Media servers (use only with CCC)_. Next to the title, there is a hoverable helpbox component from the [Helpbox UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/helpbox--helpbox). The hovered text is:

_CCC allows you to reduce the loading time of your page. With these settings you will gain performance without even touching the code of your theme. Make sure, however, that your theme is compatible with PrestaShop 1.7+. Otherwise, CCC will cause problems._

### Media server #1

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Name of the second domain of your shop, (e.g. myshop-media-server-1.com). If you do not have another domain, leave this field blank.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#media-server-1-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Media server #2

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Name of the third domain of your shop, (e.g. myshop-media-server-2.com). If you do not have another domain, leave this field blank.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#media-server-2-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Media server #3

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Empty input</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Name of the fourth domain of your shop, (e.g. myshop-media-server-3.com). If you do not have another domain, leave this field blank.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#media-server-3-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Caching

### Use cache

<table><thead><tr><th>Description</th><th width="274.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Disabled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td></td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="performance.md#use-cache-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behavior descriptions

### Clear cache CTA button behavior

Component is from the [Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics). Clears the all Prestashop caches instantly, success message ([Alerts Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) appears right after the page reload.&#x20;

### Template compilation behavior

Component is from the [Dropdown Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics). There are 3 values of the dropdown:

* **Never recompile template files** - after there are some design template files changes in the webshop, the design template of the webshop will not be recompiled.
* **Recompile templates if the files have been updated** - after there are some design template files changes in the webshop, the design template of the webshop will be recompiled.
* **Force compilation** - after any of the webshop files changes, the design template will be fully recompiled.&#x20;

### Cache behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). This functionality enables to load some sort of files much faster in some pages in the webshop. Once this feature is enabled, there are the _Multi-front optimizations_ and _Clear cache_ functionalities right after the Cache behavior. If the switch is Disabled, those 2 fields are not displayed.

### Multi-front optimizations behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). This type of caching is a way of improving a Web page's performance by saving the executed version of a page as a static file. This allows the server to handle multiple requests for the same page with only one execution of the underlying PHP script.

### Clear cache behavior

Component is from the [Dropdown Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics). There are 2 values of the dropdown:

* **Never clear cache files** - system saves the cache every file change, and cache continues to fill up.
* **Clear cache everytime something has been modified** - system clears the cache every file change, so that the user will notice the latest front-end and back-end changes in the UI.

### Disable all overrides behavior

This functionality enables or disables all the classes and controllers overrides.

### Debug mode behavior

Enable or disable the debug mode in the webshop. Debug mode helps to detect the errors in a programmatic way.&#x20;

### Disable non built-in modules behavior

Component is from the [Buttons Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics). Clicking the button _Disable_, disables the all non built-in modules in the webshop.

### Combinations behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). By default this option is enabled. If there are used combinations already, the user can not set the option to disabled.

### Features behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). Ability to Enable or Disable the Product Features.

### Customer groups behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). Ability to Enable or Disable the Customer Groups.

### Smart cache for CSS behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). Enables or Disables the smart cache for CSS. This cache is referred to the front-end design rules caching.

### Smart cache for JavaScript behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). Enable or Disable the smart cache for JavaScript. This cache is referred to the JavaScript code recurring usage.

### Apache optimization behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story). Enable or Disable the smart cache for Apache server usage. This cache is referred to the better server performance and updating the .htaccess file with appropriate links and directives.

### Media server #1 behavior

This component is from the [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal). Ability to name the second domain of the webshop, if there is one, and to connect that domain to the main domain.

### Media server #2 behavior

This component is from the [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal). Ability to name the third domain of the webshop, if there is one, and to connect that domain to the main domain.

### Media server #3 behavior

This component is from the [Forms Normal UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal). Ability to name the fourth domain of the webshop, if there is one, and to connect that domain to the main domain.

### Use cache behavior

The component is from the [Forms Switch UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story).&#x20;

## Multistore functionality

No ability to change the settings for separate multistore. [Multistores independent](../../../common-components/multistores-independent.md) page.

####

