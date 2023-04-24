# Product comments (productcomments)

## Description

This feature is available together with the Prestashop module. Once the module is Enabled, these functionalities will be seen.

It is a great way to build more confidence to the webshop visitors. The module allows visitors to review or comment certain products or items. It enables the possibility to filter and manage all the reviews from the back-office, and to choose, what reviews will be in front-office.

![Product Comments module User Interface](<../../../../../.gitbook/assets/image (1) (2) (2).png>)

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/modules/productcomments.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/breadcrumbs) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/heading-of-the-page) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Save button](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/save-button) - [Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics).
* [E-commerce logo](../../../common-components/e-commerce-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* Search input (todo link)
* [Shop switcher with eye icon](../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Language dropdown for input fields](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/KjeTPSLSN1LXBZMsI7JI/functional-documentation/ux-ui/common-components/language-dropdown-for-input-fields)
* [Checkmark navigation CTA buttons](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/diff/\~/changes/nP8KXOMgKF7kv32ktPkt/functional-documentation/ux-ui/common-components/checkmark-navigation-cta-buttons)
* [Configuration block](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/cReeZTZCiwqi5rIeUSjb/functional-documentation/ux-ui/common-components/configuration-block)

## The UI elements

### All reviews must be validated by an employee toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#all-reviews-must-be-validated-by-an-employee-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Allow guest reviews toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#allow-guest-reviews-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Enable upvotes / downvotes on reviews toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#enable-upvotes-downvotes-on-reviews-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Anonymize the user's last name toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>No</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Display only initials, e.g. John D.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#anonymize-the-users-last-name-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Minimum time between 2 reviews from the same user input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>30</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#minimum-time-between-2-reviews-from-the-same-user-input-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Number of comments per page input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>5</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#number-of-comments-per-page-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Approve dropdown with button split

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td></td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Approve</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#approve-dropdown-with-button-split-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Delete dropdown with button split

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td></td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Delete</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#delete-dropdown-with-button-split-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Plus icon&#x20;

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Add new criterion</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#plus-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Refresh icon

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Refresh list</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#refresh-icon-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Edit dropdown with button split

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td></td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Edit</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#edit-dropdown-with-button-split-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Criterion name input

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value      </td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Maximum length: 64 characters</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#criterion-name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Active toggle switch

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Yes</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#active-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Delete button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>No</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Delete</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="product-comments-productcomments.md#delete-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Configuration header of the block** behavior

&#x20;Configuration header of the block is shown with configuration icon.

### **All reviews must be validated by an employee toggle switch behavior**

It is a toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that triggers the ability to let the webshop employees validate the reviews.

### **Allow guest reviews toggle switch behavior**

It is a toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that triggers the ability to let the webshop guests to write the reviews.

### **Enable upvotes / downvotes on reviews toggle switch behavior**

It is a toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that triggers the ability to let the up-voting and down-voting of the reviews.

### **Anonymize the user's last name toggle switch behavior**

It is a toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) that triggers the ability to show or hide the last name of the user.

### **Minimum time between 2 reviews from the same user input**

This is input with text **seconds** ([Forms input group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group)). It sets the time in seconds, to do a delay for generating a review. It is a prevention of spamming huge amount of reviews at once.

### **Number of comments per page input behavior**

This is input with text **comments** ([Forms input group UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--input-group)). It sets the limit for comments in one page.

### Reviews waiting for approval block behavior

It is a table ([Tables hoverable UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--hoverable)) where all the reviews are listed for the approval. \
The table headers are:

* **ID** - shows the review ID.
* **Review title** - shows the review title.
* **Review** - shows the review text content.
* **Rating** - shows the rating as in a 5-star rating in front-office.
* **Author** - shows the user, that created a review.
* **Product** - shows the product name.
* **Time of publication** - shows the time when the review was submitted.

### Approve dropdown with button split behavior

This is dropdown with CTA button in one component ([Dropdown with button split UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)) in Reviews waiting for approval block. When hover mouse pointer on it, button color changes.\
Clicking **Approve** will approve the pending review, and it will appear in the front-office. Clicking the dropdown and selecting **Delete** - will reject the pending review. There will be a confirmation pop-up with the exclamation mark icon and the following text:\
_Delete selected item?_\
_Name: {name of the entry}_\
_**Yes** and **No** buttons_\
**Yes** - executes the deletion.\
**No** - closes the popup with no action.

If there are no entries in the table, there will be a notification in the middle of the table - _No records found_ with the exclamation mark icon.

### Reported Reviews block behavior

It is a table ([Tables hoverable UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--hoverable)) where all the reported reviews are listed for the approval. Reported Reviews are retrieved once the visitor from front-office clicks the Flag icon near the review. \
The table headers are:

* **ID** - shows the review ID.
* **Review title** - shows the review title.
* **Review** - shows the review text content.
* **Rating** - shows the rating as in a 5-star rating in front-office.
* **Author** - shows the user, that created a review.
* **Product** - shows the product name.
* **Time of publication** - shows the time when the review was submitted.

### Delete dropdown with button split behavior

This is dropdown with CTA button in one component ([Dropdown with button split UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)) in Reported Reviews block. When hover mouse pointer on it, button color changes. \
Clicking the dropdown and **Not abusive**, will leave the reported review written, and it will remain appearing in the front-office. \
Clicking the **Delete** - will reject the reported review. There will be a confirmation pop-up with the exclamation mark icon and the following text:\
_Delete selected item?_\
_Name: {name of the entry}_\
_**Yes** and **No** buttons_\
**Yes** - executes the deletion.\
**No** - closes the popup with no action.

If there are no entries in the table, there will be a notification in the middle of the table - _No records found_ with the exclamation mark icon.

### Review Criteria block behavior

It is a table ([Tables hoverable UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--hoverable)) where all the Review Criteria entries are listed. \
The table headers are:

* **Title** - Review Criteria.
* **Numeric value** - shows the number of Criteria in list.
* **ID** - review criteria ID.
* **Name** -  name of the criteria.
* **Type** - can be 3 different types of Criteria that can be created:
  * **Valid for the entire catalog**
  * **Restricted to some categories**
  * **Restricted to some products**
* **Status** - Enabled or Disabled statuses marked as red cross icon and green checkmark.

### Filtering the Review Criteria block behavior

Ability to filter the Review Criteria listing. \
There are these elements for filtering:

* **ID** - input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)), here specific text can be typed to search for a certain ID.
* **Name** - input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)), here specific text can be typed to search for a certain Name.
* **Type** - input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)), here specific text can be typed to search for a certain Type.
* **Status** - dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)), here specific selection can be selected for a certain Status.
* **Search CTA button** ([Buttons outline UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--outline)) - once clicked executes the search and returns the results. When hover mouse pointer on it, button color changes.

### Sorting the Review Criteria block behavior

Ability to sort the Review Criteria listing by clicking the arrow-up or arrow-down near the headline of the title.

* **Arrow-up** - lists the entries in alphabetical and numerical order, Z-A, 9-1.
* **Arrow-down** - lists the entries in alphabetical and numerical order, A-Z, 1-9.

### Plus icon behavior

Once clicked (+) Plus icon in Review Criteria block redirects to the adding or editing new criterion page. When new criterion saved it appears in Review criteria list. When hover mouse pointer on icon, its color changes.

### Refresh icon behavior

One clicked Refresh icon in Review Criteria block, it refreshes the whole page. When hover mouse pointer on icon, its color changes.

### Edit dropdown with button split behavior

This is dropdown with CTA button in one component ([Dropdown with button split UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)) in Review Criteria block. When hover mouse pointer on it, button color changes.\
Clicking the **Edit**, will redirect to the Review Criteria edition page.\
Clicking the dropdown and **Delete** - will delete the Criteria. There will be a confirmation pop-up with the exclamation mark icon and the following text:\
_Delete selected item?_\
_Name: {name of the entry}_\
_**Yes** and **No** buttons_\
**Yes** - executes the deletion with the green alert success message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)):\
_Criterion deleted_\
**No** - closes the popup with no action.

If there are no entries in the table, there will be a notification in the middle of the table - _No records found_ with the exclamation mark icon.

### Adding / Editing the Review Criteria entry behavior

Review Criteria can be added by clicking the plus (+) icon in the header row or clicking Edit dropdown with button split.\
Once the Review Criteria is added or edited, there will be a redirection to the new UI page.\
There are these elements in block:

* **Title** - Add new criterion.
* [**Criterion name**](product-comments-productcomments.md#criterion-name-behavior)&#x20;
* **Application scope of the criterion** - dropdown, which has available options:
  * Valid for the entire catalog
  * Restricted to some categories
  * Restricted to some products
* **Criterion will be restricted to the following categories** - some categories can be excluded from the criterion, it can be adjusted by the Category table. Each Category box can be marked or unmarked. Helper text contains:\
  _Mark the boxes of categories to which this criterion applies._
* [**Active toggle switch**](product-comments-productcomments.md#active-toggle-switch-behavior)

### Criterion name behavior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) to enter certain Criterion name.

### Active toggle switch behavior

Active toggle switch ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) with options to Enable or Disable the criterion.

### Approved Reviews block behavior

It is a table ([Tables hoverable UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tables--hoverable)) where all the approved reviews are listed. Approved Reviews in the list are stored once the back-office administrator approves the pending reviews. \
The table headers are:

* **ID** - shows the review ID.
* **Review title** - shows the review title.
* **Review** - shows the review text content.
* **Rating** - shows the rating as in a 5-star rating in front-office.
* **Author** - shows the user, that created a review. If the author name is registered in webshop system, then it is linked to the profile page.
* **Product** - shows the product name.
* **Time of publication** - shows the time when the review was submitted.

### Delete button behavior

This is dropdown with CTA button in one component ([Dropdown with button split UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)) in Approved Reviews block. It deletes the Approved Review. There will be a confirmation pop-up with the exclamation mark icon and the following text:\
_Delete selected item?_\
_Name: {name of the entry}_\
_**Yes** and **No** buttons_\
**Yes** - executes the deletion with the green alert success message ([Alerts Basics UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/alerts--basics)):\
_Criterion deleted_\
**No** - closes the popup with no action.

If there are no entries in the table, there will be a notification in the middle of the table - _No records found_ with the exclamation mark icon.

## Multistores functionality

Page is [Multistore dependent](../../../common-components/multistores-dependent.md).

## Limitations

'Time between 2 reviews' textfield : non-numeric values are allowed

'Number of comments per page' : non-numeric values are allowed
