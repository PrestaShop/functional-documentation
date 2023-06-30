# Favicon Notifications in the Back-office (ps\_faviconnotificationbo)

This module is responsible for showing favicon in the browser tabs.

![Order Notifications on the Favicon UI](<../../../../../.gitbook/assets/image (159).png>)

### favicon into the tab

![](<../../../../../.gitbook/assets/Capture d’écran du 2023-04-24 16-32-59.png>)

## Common components

* [Backoffice Headers](../../../common-components/back-office-header/)
* [Configuration block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block).

## Configuration block

The block has a small title:

_Display notifications in the browser tab for:_

The following elements are from [Forms Switch UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story) and color picker widget popups:

* **New orders** - switch button. By default, the value is set to Enabled. The number of new orders will be add in the favicon of the tab
* **New customers** - switch button. By default, the value is set to Enabled. The number of new customers will be add in the favicon of the tab
* **New messages** - switch button. By default, the value is set to Enabled. The number of new messages will be add in the favicon of the tab
* **Notification background color** - a [color picker](../../../common-components/color-picker.md) style pop-up widget, with the color selection UI, once clicked. Also, there can be a color hex code typed in the fields.
* **Notification textfield color** - a [color picker](../../../common-components/color-picker.md) style pop-up widget, with the color selection UI, once clicked. Also, there can be a color hex code typed in the fields.
* **Save CTA** - once clicked, a green success alert message will be shown from [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics):\
  _The settings have been successfully updated._

## Limitations

The orders title is wrong : it also inlcude the new customers and new messages.
