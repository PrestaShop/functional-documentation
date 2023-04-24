# Dashboard Goals (dashgoals)

This dashboard is constructed as a module, but the front-end interface is shown in the Dashboard page. It shows valuable Traffic, Conversion, Average Cart Value and Sales forecasts, depending on the active sales through the timeline.

<figure><img src="../../../../../.gitbook/assets/image (67).png" alt="Dashboard Goals Interface"><figcaption><p>Dashboard Goals Interface</p></figcaption></figure>

## Main block components

### Header part of the block

* **Chart material icon** - icon identifying the block.
* **Forecast** - the title of the block.
* **Active year** - displays the current year information.
* **Arrows** - switching the year forward or backward by one step.&#x20;
* **Refresh icon** - once clicked, refreshes the whole block with the updated information.

### Configuration grid wheel

Allows to manually update the values of the Forecast chart. Once clicked, there will be a UI animation in the same block, flipping down the configuration table from [Tables Hoverable UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--hoverable). There are these elements:&#x20;

* **12 months**.
* Each has **Traffic**.
* **Conversion Rate** (percentage value).
* **Average Cart Value**.
* **Sales** (automatically generated).
* **Save** - this call-to-action button (from [Button Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics)), saves the desired configuration and closes the table, refreshes the page.

### Tabs

The component is made from the [Button With Radio Buttons UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--button-group-with-radio-buttons). Custom tabs are made with different color circles and titles. These are:

* **Purple** circle and **Traffic.**
* **Green** circle and **Conversion.**
* **Blue** circle and **Average Cart Value.**
* **Orange** circle and **Sales.**

If the one of the tabs is active and showing the information, it will be shown as selected and greyed.&#x20;

### The chart

The information chart is made aligned with the **X** and **Y** coordinates.&#x20;

**X** - shows the timeline of the annual year, with the 4 months.

**Y** - shows the value coordinates from negative to positive.
