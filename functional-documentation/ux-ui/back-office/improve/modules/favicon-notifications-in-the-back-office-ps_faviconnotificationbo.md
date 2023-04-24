# Favicon Notifications in the Back-office (ps\_faviconnotificationbo)

This module is responsible for showing favicon in the browser tabs.

![Order Notifications on the Favicon UI](<../../../../../.gitbook/assets/image (62).png>)

## Common components

* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Configuration block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block).

## Configuration block

The block has a small title:

_Display notifications in the browser tab for:_

The following elements are from [Forms Switch UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story) and color picker widget popups:

* **New orders** - switch button with Enabled and Disabled values. By default, the value is set to Enabled.
* **New customers** - switch button with Enabled and Disabled values. By default, the value is set to Enabled.
* **New messages** - switch button with Enabled and Disabled values. By default, the value is set to Enabled.
* **Notification background color** - a color picker style pop-up widget, with the color selection UI, once clicked. Also, there can be a color hex code typed in the fields.
* **Save CTA** - once clicked, a green success alert message will be shown from [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics):\
  _The settings have been successfully updated._
