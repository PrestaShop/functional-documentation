# Dashboard Goals (dashgoals)

## Description

This module does not have any configuration/settings page, the only option is to either enable or disable it. If enabled, it will be displayed as Forecast block in the Dashboard section.

<figure><img src="../../../../../.gitbook/assets/image (15).png" alt="Dashboard goals in Modules manager page User Interface"><figcaption><p>Dashboard goals in Modules manager page User Interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/Screenshot 2022-06-17 at 14-38-33 Dashboard • test.png" alt="Dashboard goals in Dashboard User Interface"><figcaption><p>Dashboard goals in Dashboard User Interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (49).png" alt="Dashboard goals configuration board in Dashboard User Interface"><figcaption><p>Dashboard goals configuration board in Dashboard User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/modules/module-manager/modules.html)

## The UI elements

### Settings icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Configure</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-goals.md#settings-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Refresh icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Refresh</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-goals.md#refresh-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Traffic inputs

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All characters can be entered but only numbers are saved</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-goals.md#traffic-inputs-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Conversion Rate inputs

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All characters can be entered but only numbers are saved</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-goals.md#conversion-rate-inputs-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Average Cart Value inputs

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>All characters can be entered but only numbers are saved</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>0</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>-</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>-</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>-</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="dashboard-goals.md#average-cart-value-inputs-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Title of Forecast behavior

This title includes the title and statistics icon. Next to title there are years shown and left-right arrows to change years to earlier or later ones.

### Settings icon behavior

Once clicked it opens configuration board. There statistics can be customizable.

### Refresh icon behavior

Once clicked it refreshes Forecast block.

### Forecast buttons group behavior

This block has buttons group of 4 buttons ([Buttons group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--button-group)) and they are:

* **Traffic** with purple dot
* **Conversion** with green dot
* **Average Cart Value** with light blue dot
* **Sales** with orange dot

Once clicked chosen button, its statistic is shown in block. When hover mouse pointer on button, its color changes.

### Forecast Configuration block behavior

This block allows to customize statistics. It contains one year table divided into months. Table has these columns:

* [Traffic](dashboard-goals.md#traffic-inputs-behavior)
* [Conversion Rate](dashboard-goals.md#conversion-rate-inputs-behavior)
* [Average Cart Value](dashboard-goals.md#average-cart-value-inputs-behavior)
* Sales&#x20;

Each table cells in Traffic, Conversion Rate and Average Cart Value columns has input fields. Sales cell shows the result immediately after data entered in this row  inputs.\
Once clicked Save button, entered data saved, Configuration block closes and Forecast block statistic is shown.

### Traffic inputs behavior

This is number input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter traffic data.

### Conversion Rate inputs behavior

This is number input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter conversion rate data. Next to input is percent sign.

### Average Cart Value inputs behavior

This is number input ([Forms number UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) to enter average cart value data. Next to input is shown currency of shop.

## Multistores functionality

[Multistores dependent](../../../common-components/multistores-dependent.md) page.
