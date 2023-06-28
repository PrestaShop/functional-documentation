# Import

## Description

This UI page and functionality is based on the import actions of the PrestaShop application. The listing is specified of all the visible sections in page.

<figure><img src="../../../../../.gitbook/assets/image (79).png" alt="Import User Interface"><figcaption><p>Import User Interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (83) (1).png" alt="Match your data User Interface"><figcaption><p>Match your data User Interface</p></figcaption></figure>

<figure><img src="../../../../../.gitbook/assets/image (69).png" alt="Importing your data popup User Interface"><figcaption><p>Importing your data popup User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/advanced-parameters/import.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../common-components/breadcrumbs.md)  -  [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../common-components/heading-of-the-page.md)   - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../common-components/help-button.md)  - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../common-components/search-input-field.md)
* [Shop switcher](../../../common-components/shop-switcher.md)
* Bell icon (todo link)
* [Account icon](../../../common-components/account-icon.md)&#x20;
* [Cancel button ](../../../common-components/cancel-button.md) - [Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)

## The UI elements

### What do you want to import? dropdown

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Categories</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#what-do-you-want-to-import-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Select a file to import input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">The extension of your file should be .csv.</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>Categories</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Allowed formats: .csv, .xls, .xlsx, .xlst, .ods, .ots Only UTF-8 and ISO 8859-1 encodings are allowed You can also upload your file via FTP to the following directory: /var/www/html/admin1/import/ .</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>No file chosen</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#select-a-file-to-import-and-the-import-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Language of the file dropdown

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>English (English)</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>The locale must be installed</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#language-of-the-file-dropdown-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Field separator input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>;</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>e.g. 1; Blouse; 129.90; 5</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#field-separator-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Multiple value separator input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>,</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>e.g. Blouse; red.jpg, blue.jpg, green.jpg; 129.90</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#multiple-value-separator-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Delete all (What do you want to import? dropdown value elements) before import toggle switch

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#delete-all-what-do-you-want-to-import-dropdown-value-elements-before-import-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### **Use product reference as key** toggle switch

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>If enabled, the product's reference number MUST be unique!</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#use-product-reference-as-key-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Skip thumbnails regeneration toggle switch

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#skip-thumbnails-regeneration-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Force all ID numbers toggle switch

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Enable this option to keep your imported items’ ID number as is. Otherwise, PrestaShop will ignore them and create auto-incremented ID numbers.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#force-all-id-numbers-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Send notification email toggle switch

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Receive an email when the import is complete. It can be useful when handling large files, as the import may take some time.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#send-notification-email-toggle-switch-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Save your data matching configuration input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                       -</td><td align="center">Please name your data matching configuration in order to save it.</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#save-your-data-matching-configuration-input-beahvior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Rows to skip input

<table><thead><tr><th>Description</th><th width="264.3333333333333">Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                          -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>1</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Indicate how many of the first rows of your file should be skipped when importing the data. For instance set it to 1 if the first row of your file contains headers.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="import.md#rows-to-skip-input-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### **Blue information notification behavior**

This is alert message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)) with the useful links to the documentation about import and CSV format. The text is:\
_You can read information on import at:_ [_https://docs.prestashop-project.org/1.7-documentation/user-guide/configuring-shop/advanced-parameters/import_](https://docs.prestashop-project.org/1.7-documentation/user-guide/configuring-shop/advanced-parameters/import)\
_Read more about the CSV format at:_ [_https://en.wikipedia.org/wiki/Comma-separated\_values_](https://en.wikipedia.org/wiki/Comma-separated\_values)

### **What do you want to import? dropdown behavior**

This dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) functionality can be used for choosing the subjects that can be imported to PrestaShop. \
The importing subjects are:

* Categories
* Products
* Combinations
* Customers
* Addresses
* Brands
* Suppliers
* Alias
* Store contacts

### &#x20;Yellow **information notification behavior**

This is alert message ([Alerts basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics)). Only the Categories and Products import is associated with the following yellow type warnings and they are:&#x20;

* _Note that the Category import does not support having two categories with the same name._&#x20;
* _Note that you can have several products with the same reference._&#x20;

### **Select a file to import and the import input behavior**

This is the file input field ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)), where CSV files can be browsed and imported to the PrestaShop. Input field has label inside “Choose file(s)”.\
Once clicked on it opens a native OS popup to navigate to the file to import. \
Once the file has been uploaded, the green success UI notification will appear, indicating, that the file has been attached. There will be a pen icon notification, indicating, that the file attached can be re-attached with other file.

### **Choose from history / FTP input behavior**

By default this field ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) is disabled, but becomes enabled, once the first CSV file is uploaded through this interface or directly through FTP upload. \
After the first CSV upload, the history input becomes active with the upload history files. Then the chosen file can be selected, downloaded or deleted from the history list. \
Once the file has been uploaded, the green success UI notification will appear, indicating, that the file has been attached. There will be a pen icon notification, indicating, that the file attached can be re-attached with other file.

### Language of the file dropdown behavior

This is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) - the language must be set manually for the importing. This dropdown input is set to English by default, or in the other case - to the default PrestaShop's installation language. The locale must be installed.&#x20;

### Field separator input  behavior

This is input field ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) there specific alphabetic symbol must be set, in order to separate the CSV data values.

### Multiple value separator input behavior

This is input field ([Forms files UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--files)) - if values are very similar-typed and should be separated, there should be a multiple value separator defined.

### Delete all (What do you want to import? dropdown value elements) before import toggle switch behavior

This is toggle switch button ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)), that configures, if the old import entries will be erased before the new import execution. Note, that if this setting is enabled, there will be a pop-up notification from browser, with the confirmation of the deletion. \
This toggle switch appears for all What do you want to import? dropdown elements.

### **Use product reference as key** toggle switch behavior

This is toggle switch button ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)), this option can be enabled, if there are possible Product ID duplications between the existing and the importing products. PrestaShop sets the reference instead of Product ID to the product.\
This toggle switch appears for Products and Combinations only.

### Skip thumbnails regeneration toggle switch behavior

This is toggle switch button ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)), that configures, if the thumbnails regeneration should be executed aligned with the import. \
This toggle switch appears for Categories, Products, Brands, Suppliers and Store contacts only.

### Force all ID numbers toggle switch behavior

This is toggle switch button ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)), that configures, if to keep imported items' ID number as is already, otherwise, PrestaShop will ignore them and create auto-incremented ID numbers during import process.\
This toggle switch appears for all What do you want to import? dropdown elements.

### Send notification email toggle switch behavior

This is toggle switch button ([Forms switch story UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)), that configures the email sending, when the import is complete.\
This toggle switch appears for all What do you want to import? dropdown elements.

### Next step button behavior

Next step is CTA button with Arrow to right icon ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)). Once clicked executes the redirection to the second UI of the import process [Match your data](import.md#match-your-data-behavior). When hover mouse pointer on it, button color changes.

### History of uploaded files list behavior

There is a history list to use already uploaded files. This widget is displayed once the _Choose from history / FT_ button is clicked. The list contains the actual file name with the file extension name and dropdown UI ([Dropdowns with button split UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)) with button use and dropdown with options to download or delete the file. When hover mouse pointer on it, button color changes.

### Available fields UI section behavior

Fields listed, that are included into the import execution process. Under fields list is notification: \
_\* Required field._

#### Categories fields

* ID
* Active
* Name\*
* Parent category
* Root category it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _A category root is where a category tree can begin. This is used with multistore._
* Description
* Meta title
* Meta keywords
* Meta description
* Rewritten URL
* Image URL
* ID / Name of shop it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Ignore this field if you don't use the Multistore tool. If you leave this field empty, the default shop will be used._

#### Products fields

* ID
* Active
* Name\*
* Categories (x,y,z...)
* Price tax excluded
* Price tax included
* Tax rule ID
* Cost price
* On sale (0/1)
* Discount amount
* Discount percent
* Discount from (yyyy-mm-dd)
* Discount to (yyyy-mm-dd)
* Reference #
* Supplier reference #
* Supplier
* Brand
* EAN13
* UPC
* MPN
* Ecotax
* Width
* Height
* Depth
* Weight
* Delivery time of in-stock products:
* Delivery time of out-of-stock products with allowed orders:
* Quantity
* Minimal quantity
* Low stock level
* Send me an email when the quantity is under this level
* Visibility
* Additional shipping cost
* Unit for base price
* Base price
* Summary
* Description
* Tags (x,y,z...)
* Meta title
* Meta keywords
* Meta description
* Rewritten URL
* Label when in stock
* Label when backorder allowed
* Available for order (0 = No, 1 = Yes)
* Product availability date
* Product creation date
* Show price (0 = No, 1 = Yes)
* Image URLs (x,y,z...)
* Image alt texts (x,y,z...)
* Delete existing images (0 = No, 1 = Yes)
* Feature (Name:Value:Position:Customized)
* Available online only (0 = No, 1 = Yes)
* Condition
* Customizable (0 = No, 1 = Yes)
* Uploadable files (0 = No, 1 = Yes)
* Text fields (0 = No, 1 = Yes)
* Action when out of stock
* Virtual product (0 = No, 1 = Yes)
* File URL
* Number of allowed downloads - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Number of days this file can be accessed by customers. If setting configured to zero, it will be configured for unlimited access._
* Expiration date (yyyy-mm-dd)
* Number of days - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Number of days this file can be accessed by customers. Set to zero for unlimited access._
* ID / Name of shop - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Field can be ignored if Multishop is used. If this field is left empty, the default shop will be used._
* Advanced Stock Management - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Enabling Advanced Stock Management on product (0 = No, 1 = Yes)._
* Depends on stock - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _0 = Using quantity set in product, 1 = Using quantity from warehouse._
* Warehouse - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _ID of the warehouse to set as storage._
* Accessories (x,y,z...)

#### Combinations fields

* Product ID
* Product reference
* Attribute (Name:Type:Position)\*
* Value (Value:Position)\*
* Supplier reference
* Reference
* EAN13
* UPC
* MPN
* Cost price
* Impact on price
* Ecotax
* Quantity
* Minimal quantity
* Low stock level
* Send me an email when the quantity is under this level
* Impact on weight
* Default (0 = No, 1 = Yes)
* Combination availability date
* Choose among product images by position (1,2,3...)
* Image URLs (x,y,z...)
* Image alt texts (x,y,z...)
* ID / Name of shop - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Field can be ignored if Multishop is used. If this field is left empty, the default shop will be used._
* Advanced Stock Management - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Enabling Advanced Stock Management on product (0 = No, 1 = Yes)._
* Depends on stock - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _0 = Using quantity set in product, 1 = Using quantity from warehouse._
* Warehouse - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _ID of the warehouse to set as storage._

#### Customers fields

* ID
* Active (0/1)
* Titles ID (Mr = 1, Ms = 2, else 0)
* Email\*
* Password (required)
* Birth date (yyyy-mm-dd)
* Last name\*
* First name\*
* Newsletter (0/1)
* Partner offers (0/1)
* Registration date (yyyy-mm-dd)
* Groups (x,y,z...)
* Default group ID
* ID / Name of shop - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Field can be ignored if Multishop is used. If this field is left empty, the default shop will be used._

#### Addresses fields

* ID
* Alias\*
* Active (0/1)
* Customer email\*
* Customer ID
* Brand
* Supplier
* Company
* Last name\*
* First name\*
* Address\*
* Address (2)
* Zip/Postal code\*
* City\*
* Country\*
* State
* Other
* Phone
* Mobile Phone
* VAT number
* Identification number

#### Brands fields

* ID
* Active (0/1)
* Name\*
* Description
* Short description
* Meta title
* Meta keywords
* Meta description
* Image URL
* ID / Name of group shop - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Field can be ignored if Multishop is used. If this field is left empty, the default shop will be used._

#### Suppliers fields

* ID
* Active (0/1)
* Name\*
* Description
* Short description
* Meta title
* Meta keywords
* Meta description
* Image URL
* ID / Name of group shop - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: _Field can be ignored if Multishop is used. If this field is left empty, the default shop will be used._

#### Alias fields

* ID
* Alias\*
* Search\*
* Active

#### Store contacts fields

* ID
* Active (0/1)
* Name
* Address\*
* Address (2)
* Zip/Postal code
* State
* City\*
* Country\*
* Latitude\*
* Longitude\*
* Phone
* Fax
* Email address
* Note
* Hours (x,y,z...)
* Image URL
* ID / Name of shop - it has the Tooltip ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) notification: Field can be ignored if Multishop is used. If this field is left empty, the default shop will be used.

### Download sample csv files UI section behavior

This section helps to orientate, how is the CSV file structure made. Administrators can download the file examples, and to test the import actions and analyze what values and fields are managed by PrestaShop. Those CSV files contain random dummy values. The following CSV templates names and the file sizes are:

* **Sample Categories file** - 969 B
* **Sample Products file** - 4.6 KB
* **Sample Combinations file** - 5.8 KB
* **Sample Customers file** - 1.1 KB
* **Sample Addresses file** - 2.6 KB
* **Sample Brands file** - 17.4 KB
* **Sample Suppliers file** - 1.6 KB
* **Sample Aliases file** - 135 B
* **Sample Store Contacts file** - 1.3 KB

### Match your data behavior

This is the title of redirected interface contains the imported data matching table.

### **Blue information notification behavior**

This is information message ([Alerts basics UI kit)](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/alerts--basics) for the matching columns of the import process and it is: _Please match each column of your source file to one of the destination columns._

### **Save your data matching configuration** input beahvior

This is input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) where special data matching configuration can be saved for future import processes.  It can be saved by clicking CTA Save button ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), after giving a name for the configuration. When hover mouse pointer on it, button color changes.

### **Load a data matching configuration** dropdown behavior

This dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) appears if there is any data match configuration file saved. There are two CTA button on the right side of dropdown. After choosing the configuration file and click Load button  ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), it loads the configurational data. Once clicked Delete button  ([Buttons with icons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--buttons-with-icons)), it removes the configurational data from the saved list.\
When hover mouse pointer on each button, button color changes.

### **Rows to skip input behavior**

&#x20;This is numeric input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)), that indicates how many of the first rows of the importing file should be skipped when importing the data.

### Matching table behavior

There is a brief table listed, in order to do a final check of the importing elements. Each table column header has a dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)), with the values of the import type. \
The purpose of this dropdown is to match the targeted values with the values that were stored in the importing CSV file. \
Note, that there is a value _Ignore this column_, which prevents the import process of the specific column values from the CSV file.

### Import button behavior

This is CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)), once clicked finalizes the Import stage and initiates the import process. When hover mouse pointer on it, button color changes.\
After the successful importing action, the interface prompts the popup element, where there is a success message _Data imported Look at your listings to make sure it's all there as you wished._, progress bars ([Progress bars UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/progress-bar--progress-bar)) with the percentage and numeric values of the processes - Validated and Imported. Also there is the Close CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)) to close the popup.\
If there is no CSV file attached to the Import submission form, the outcoming message will be prompted _Please upload a file in order to continue._\
If the file is too large, the UI will be prompted with the error notification _File is too large_.\
If the file is with the incorrect extension, the UI will be prompted with the error notification _The extension of your file should be .csv._

## Multistores functionality

Multistores independent (todo link) page.\
Prestashop multistores maintaining the same configuration in the import page, for all the multistores and shop groups, as administrator switches them. All the data values from the import process in CSV will be directly transferred to the selected multistore independently.
