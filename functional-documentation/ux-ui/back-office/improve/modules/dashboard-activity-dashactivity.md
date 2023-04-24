# Dashboard activity (dashactivity)

## Description

The Back-Office module represents the specific UI block in the main Prestashop dashboard page. The block contains some segmented information returned from the Prestashop behavior. The part of the UI is called _Activity overview_.

<figure><img src="../../../../../.gitbook/assets/image (9) (3).png" alt="Dashboard activity UI - full scale"><figcaption><p>Dashboard activity User Interface - full scale</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/dashboard.html)

## Common components

* [Filtering components in stats](../../../common-components/stats-page-specific-component/filtering-components-in-stats.md)
* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/back-office-header/quick-access-dropdown.md)&#x20;
* Search input (todo link)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Save button](../../../common-components/save-button.md)

## Activity overview block

The block starts with the clock-style icon, title Activity overview, Settings gear icon, Refresh icon:

* **Gear icon** - opens the Settings UI in the same position, after smooth animation executed. After clicking the icon once again, the block smoothly flips back to the default position.
* **Refresh icon** - initiates the UI block numbers refreshing, after clicking the icon.

### Online visitors

Shows the numeric statistics of the Online visitors in the latest 30 minutes range. Clicking Online visitors redirects to the live statistics.

### Active Shopping Carts

Shows the numeric statistics of the Active Shopping Carts in the Prestashop in the latest 30 minutes range. Clicking the link redirects to the Shopping Carts page.

### Currently pending

#### Orders

Shows the pending Orders - link to the Orders page.

#### Return/Exchanges

Shows the pending Returns or Exchanges - link to the Merchandise Returns page.

#### Abandoned Carts

Shows the pending Abandoned Carts - link to the Shopping Carts page.

#### Out of Stock Products

Shows the Out of Stock Products - link to the Monitoring page.

### Notifications

#### New messages

Shows the last messages that has been received - link to the Customer Service page.

#### Product reviews

Shows the latest Product reviews - link to the Configure module page.

### Customers & Newsletters

This section shows the title and the date range - FROM and TO, depending on what time range is set.

**New Customers** - shows the recent customers, that has been created - link to the Manage your Customers page.

**New Subscribers** - shows the recent new subscribers, that has been created - link to the Newsletter stats page.

**Total Subscribers** - shows the Total Subscribers that has been signed up recently - link to the _ps\_emailsubscription_ module configuration page.

### Traffic

The section contains the title Traffic and the date range - FROM and TO, depending on what time range is set.

**Link to your Google Analytics account** - links to the GA module settings page. If there is no module, it will redirect to the Module Manager page.

**Visits** - shows the last visits of the webshop - link to the Dashboard module statistics page.

**Unique Visitors** - shows the unique visitors of the webshop - link to the unique visitors' calculation module.

**Traffic Sources** - shows the incoming traffic sources. More precisely, it shows the direct traffic linking values with the blue circle notification nearby. &#x20;

### Configuration block

#### Active cart

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Allowed: 15, 30, 45, 60, 90, 120</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>30</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>How long (in minutes) a cart is to be considered as active after the last recorded change (default: 30 min).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-activity-dashactivity.md#active-cart-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Online visitor

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Allowed: 15, 30, 45, 60, 90, 120</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>30</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>How long (in minutes) a visitor is to be considered as online after their last action (default: 30 min).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-activity-dashactivity.md#online-visitor-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Abandoned cart (min)

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>24</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>How long (in hours) after the last action a cart is to be considered as abandoned (default: 24 hrs).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-activity-dashactivity.md#abandoned-cart-min-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

#### Abandoned cart (max)

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>48</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>How long (in hours) after the last action a cart is to be considered as abandoned (default: 24 hrs).</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-activity-dashactivity.md#abandoned-cart-max-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Configuration block behavior descriptions

#### Active cart behavior

Component from the [Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics). The activity duration of the statistical entry displaying can be adjusted here.

#### Online visitor behavior

Component from the [Dropdowns Basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics). The activity duration in minutes of the statistical entry.

#### Abandoned cart (min) behavior

Component from the [Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group). The activity duration in hours of the statistical entry.

#### Abandoned cart (max) behavior

Component from the [Input Group UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group). The activity duration in hours of the statistical entry.
