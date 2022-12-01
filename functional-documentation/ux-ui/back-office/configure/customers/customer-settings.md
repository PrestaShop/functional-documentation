# Customer Settings

This page defines the general Customer settings of the webshop.

![Customers Settings UI](<../../../../../.gitbook/assets/image (7).png>)

## Common components

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## Tabs section

The active selected tab is highlighted using [Navigation Tab UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/navigation--navigation-tabs).

## General section components

**Section header** - named General, with an icon near, from material icons class family.

**Re-display cart at login** - required setting __ from [Switch Story UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story). By default, it is disabled. Once enabled, the customer can see his or her last shopping cart that was made. The helper text is:

_After a customer logs in, you can recall and display the content of his/her last shopping cart._

**Send an email after registration** - required setting __ from [Switch Story UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story). By default, it is enabled. Once enabled, the customer can see his or her registration information sent into the email. The helper text is:

_Send an email with a summary of the account information after registration._

**Password reset delay** - required input from [Input Group UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--input-group). By default, the value is set to 360 minutes. This function sets the time delay, between the first password change request and the second password confirmation action. The input key factors:

* Maximum 19 characters are allowed.
* Only numbers are allowed.

The helper text is:

_Minimum time required between two requests for a password reset._

Error, if the field doesn't match the input key factors:

_{exclamation mark icon} This value is not valid._

**Enable B2B mode** - required setting __ from [Switch Story UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story). By default, the option is enabled. Once this feature is enabled, B2B features will be visibly enabled in Back-Office. The new input fields will be in the customer registration form. The helper text is:

_Activate or deactivate B2B mode. When this option is enabled, B2B features will be made available._

**Ask for birth date** - required setting __ from [Switch Story UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story). By default, the option is enabled. Once this feature is enabled, the registering customers will be asked to provide the date of birth. The helper text is:

_Display or not the birth date field._

**Enable partner offers** - required setting __ from [Switch Story UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story). By default, the option is enabled. Once this feature is enabled, the webshop customers will get an opportunity (during the registration) to subscribe to the other webshop partners. The helper text is:

_Optional check box for affiliate links._

**Save call-to-action button** - once clicked, the page will reload and save the settings, with the green success notification from [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics):

_Update successful_

## Error messages

No [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) errors, only single input field error.

## Multistores

This page is [multistores dependent](../../../common-components/multistores-dependent.md).

__

__

__
