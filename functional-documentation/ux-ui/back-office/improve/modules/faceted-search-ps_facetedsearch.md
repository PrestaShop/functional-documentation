# Faceted search (ps\_facetedsearch)

The module is used for filtering the catalog and helping the visitors to see the category tree and to browse the webshop store easily.

![Faceted search User Interface](<../../../../../.gitbook/assets/image (72).png>)

## Common components

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Page header call to action buttons (modules)](../../../common-components/module-page-specific-component/page-header-call-to-action-buttons-modules.md).
* [Configuration block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block).

## Indexes and caches block

There are 4 types of buttons ([Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)) for indexing and caching the category tree:

* **Index all missing prices** - clicking the button executes the indexation of all missing prices. The progress status of the indexed items will be shown on the button and after successful indexation, there will be a green success message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) called:\
  _Price indexing finished._
* **Rebuild entire price index** - clicking the button executes the indexation of entire prices. The progress status of the indexed items will be shown on the button and after successful indexation, there will be a green success message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) called:\
  _Price indexing finished._\
  During the progress, it will be a yellow alert message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)):\
  _Indexing is in progress. Please do not leave this page_
* **Build attributes and features** - clicking the button executes the indexation of entire attributes and features. The progress status of the indexed items will be shown on the button and after successful indexation, there will be a green success message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) called:\
  _Attribute indexing finished._\
  During the progress, it will be a yellow alert message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)):\
  _Indexing is in progress. Please do not leave this page_
* **Clear cache** - clicking the button executes the clearing the cache. The progress status of the indexed items will be shown on the button and after successful indexation, there will be a green success message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)) called:\
  _Attribute indexing finished._\
  During the progress, it will be a yellow alert message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)):\
  _Indexing is in progress. Please do not leave this page_

Information section has these notifications ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)):

_You can set a cron job that will rebuild price index using the following URL:_\
_**{host URL}/modules/ps\_facetedsearch/ps\_facetedsearch-price-indexer.php?token={token}**_\
\
_You can set a cron job that will rebuild attribute index using the following URL:_\
_**{host URL}/modules/ps\_facetedsearch/ps\_facetedsearch-attribute-indexer.php?token={token}**_

_A nightly rebuild is recommended._

## Filters templates block

The templates are listed in the table ([Tables Basic UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/tables--basic)). The table title has a numeric value near, showing the total value of templates. There are the following headers of the table:

* **ID** - the ID of the template.
* **Name** - the name of the template.
* **Categories** - shows how many categories are in the templates.
* **Created on** - shows the creation timestamp.
* **Actions** - **Edit** button ([Buttons With Icons UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)) - redirects to the adding a new filter template form, and the dropdown, where **Delete** action is. Clicking **Delete** shows the browser-type pop-up UI with the question:\
  _Do you really want to delete this filter template?_\
  **Cancel** closes the pop-up, **OK** - deletes the template with the alert message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)):\
  _Filter template deleted, categories updated (reverted to default Filter template)._
* **Add new template CTA button** - redirects to adding a new filter template form.

## New filters template section

A page for editing or adding a new filter template.

### Common components:

* [Shop association block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/8Fxl8PmetHDkJRhZgFH2/functional-documentation/ux-ui/common-components/shop-association-block).
* [Checkmark navigation CTA buttons](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/nP8KXOMgKF7kv32ktPkt/functional-documentation/ux-ui/common-components/checkmark-navigation-cta-buttons).
* [Configuration block.](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block)

**Template name** - ability to name the template. Helper text:\
_Only as a reminder_

**Categories used for this template** - ability to mark the required categories and to use [Checkmark navigation CTA buttons](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/nP8KXOMgKF7kv32ktPkt/functional-documentation/ux-ui/common-components/checkmark-navigation-cta-buttons).

**Choose shop association** - ability to mark the required Shops using [Shop association block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/8Fxl8PmetHDkJRhZgFH2/functional-documentation/ux-ui/common-components/shop-association-block) and to use [Checkmark navigation CTA buttons](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/nP8KXOMgKF7kv32ktPkt/functional-documentation/ux-ui/common-components/checkmark-navigation-cta-buttons).

### Filters

This block has multiple filter blocks, that can be drag-and-dropped, positioned in any way. The filter criteria have the following elements:

* **Toggle switch button (**[**Toggle Switch Storybook UI**](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story)**)** - for Enabling or Disabling the filter.
* **Filter name** - name of the filter.
* **Filter style** - selection with the dropdown - **Checkbox**, **Radio button** or **Drop-down list**.&#x20;
* **Filter result limit** - selection with the dropdown - from **No limit** to **20**.

**Cancel** - call to action CTA which redirects to the Faceted Search configuration page.

**Save** - call to action CTA which saves the form and returns green success notification ([Alerts basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)):\
_Your filter "Template name" was updated successfully._

If the submission fails, the message will be:\
_You must select at least one category._

### Configuration block

[Configuration block.](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block)

## Configuration block from Faceted Search

These settings contain [Forms Switch UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--switch-story) and [Forms Normal UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/forms--normal) elements.

* **Enable cache system** - Disabled or Enabled (By default Enabled).
* **Show the number of matching products** - Disabled or Enabled (By default Enabled).
* **Show products from subcategories** - Disabled or Enabled (By default Enabled).
* **Show products only from default category** - Disabled or Enabled (By default Disabled). The helper text is:\
  _Works only if "Show products from subcategories" is off._
* **Category filter depth (0 for no limits, 1 by default)** - input field by default the value is 1.
* **Use tax to filter price** - Disabled or Enabled (By default Enabled).
* **Use rounding to filter price** - Disabled or Enabled (By default Enabled).
* **Show unavailable, out of stock last** - Disabled or Enabled (By default Disabled).
* **Save CTA** - once the form is submitted, there will be an alert from [Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics) with the message:\
  _Settings saved successfully_

## Configuration block

[Configuration block.](faceted-search-ps\_facetedsearch.md#configuration-block-1)

## Multistores functionality

[Multistores dependent.](faceted-search-ps\_facetedsearch.md#multistores-functionality)
