# Google analytics (module) description

## Description

This is the page for Google analytics module configuration. It has two blocks: information and settings.

<figure><img src="../../../../../../.gitbook/assets/image (9).png" alt="Google analytics User Interface"><figcaption><p>Google analytics User Interface</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (21).png" alt="Google analytics Settings block User Interface"><figcaption><p>Google analytics Settings block User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## Common components <a href="#common-components" id="common-components"></a>

* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md).
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md).
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md).
* [Search input](../../../../common-components/search-input-field.md) - [Forms input with dropdown UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-with-dropdown).
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md).&#x20;
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md).
* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI ](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings)[kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../../common-components/page-header-call-to-action-buttons-modules.md) - [Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../common-components/save-button.md) -  [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).&#x20;
* [Configuration block](../../../../common-components/configuration-block.md).

## The UI elements

### Google Analytics Tracking ID input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This information is available in your Google Analytics account.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="google-analytics-module-description.md#google-analytics-tracking-id-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable User ID tracking toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="google-analytics-module-description.md#enable-user-id-tracking-toggle-switch-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Anonymize IP toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td></td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Use this option to anonymize the visitor's IP to comply with data privacy laws in some countries</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="google-analytics-module-description.md#anonymize-ip-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable Back Office Tracking toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Use this option to enable the tracking inside the Back Office</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="google-analytics-module-description.md#enable-back-office-tracking-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Cancelled order states input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Canceled</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Choose order states, in which you consider the given order cancelled. This will be usually only the default "Cancelled" state, but some shops may have extra states like "Returned" etc.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="google-analytics-module-description.md#cancelled-order-states-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable Cross-Domain tracking toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="google-analytics-module-description.md#enable-cross-domain-tracking-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Google analytics information block behavior

This block that shows information about Google analytics module. On the top it has module title **Google Analytics** and module icon. On the upper right corner is CTA button **Create your account to get started.** ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)). Once clicked it redirects to google support page.&#x20;

In the middle of block on the left side is shown information about module and it is:\
_Your customers go everywhere; shouldn't your analytics._ \
_Google Analytics shows you the full customer picture across ads and videos, websites and social tools, tables and smartphones. That makes it easier to serve your current customers and win new ones._\
_With ecommerce functionality in Google Analytics you can gain clear insight into important metrics about shopper behavior and conversion, including:_

* **Product detail views** and view icon
* **"Add to cart" actions** and add to cart icon
* **Internal campaign clicks** and click icon
* **Internal merchandising Success** and price tag icon
* **The checkout process** and shopping cart icon
* **And purchase** and credit card icon

In the middle of block on the right side there is image of Shopping Behavior Analysis example. It has a caption: _Merchants are able to understand how far along users get in the buying process and where they are dropping off._

On the bottom right corner is a link **Create your account to get started.**, once clicked it redirects to google support page. When hover mouse pointer on it, link text becomes underlined.

### Google Analytics Tracking ID input behavior

This is input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter tracking ID. After saving green notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) is shown: S_ettings for User ID updated successfully._

### Enable User ID tracking toggle switch

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) to enable or disable user ID tracking.  After saving green notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) is shown: _Settings for User ID updated successfully._

### Anonymize IP toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) to enable or disable IP anonymizing.  After saving green notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) is shown: _Settings for Anonymize IP updated successfully_.

### Enable Back Office Tracking toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) to enable or disable Back Office tracking.  After saving green notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) is shown: _Settings for Enable Back Office tracking updated successfully._

### Cancelled order states input behavior

This is input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter cancelled order status. Once clicked it also opens dropdown with all shops order statuses in alphabetic order. When input is empty, shows place holder: _Select Some Options_. After saving green notification ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) is shown: _Settings for cancelled order states updated successfully._

### Enable Cross-Domain tracking toggle switch behavior

This is toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) to enable or disable Cross-Domain tracking.

## Multistores functionality

[Multistores dependent](../../../../common-components/multistores-dependent.md) page.
