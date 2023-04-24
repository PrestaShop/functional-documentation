# Edit or Add Cart Rule

## Description

When you enter the Cart rule editing UI, there are 3 separate tabs - Information, Conditions and Actions. Each of them are combined together with the general cart rules functionality.

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2023-01-04 at 11-47-00 Cart Rules Edit CART_RULE • PrestaShop.png" alt="Edit or add Cart rule Information tab UI"><figcaption><p>Edit or add Cart rule Information tab UI</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2023-01-04 at 11-52-31 Cart Rules Edit CART_RULE • PrestaShop.png" alt="Edit or add Cart rule Conditions tab UI"><figcaption><p>Edit or add Cart rule Conditions tab UI</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2023-01-04 at 11-54-42 Cart Rules Edit CART_RULE • PrestaShop.png" alt="Edit or add Cart rule Actions tab UI"><figcaption><p>Edit or add Cart rule Actions tab UI</p></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2023-01-04 at 12-00-41 Cart Rules Edit CART_RULE • PrestaShop (1).png" alt="Conditions tab Restrictions part UI"><figcaption><p>Conditions tab Restrictions part UI</p></figcaption></figure>

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](../../../../common-components/help-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [Save button](../../../../common-components/save-button.md) - [Buttons basics UI Kit.](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics)
* [Save and Stay button](../../../../common-components/save-and-stay-button.md) - [Buttons basics UI Kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics).
* [Cancel button](../../../../common-components/cancel-button.md) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)
* [Quick access dropdown](../../../../common-components/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)&#x20;
* Bell icon (todo link)
* Trophy icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;

## Information tab

The explanations of the input fields, dropdowns, switch toggle buttons and text fields are stated below:

### **Name**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">The field name is required at least in English (English).</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>If there is another code already created - error.</td><td align="center">This cart rule code is already used (conflict with cart rule 2)</td><td></td></tr><tr><td>Default value</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                   -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This will be displayed in the cart summary, as well as on the invoice.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                   -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                   -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#name-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Description

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>For your eyes only. This will never be displayed to the customer.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#description-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Code

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Forbidden non unique code</td><td align="center">This cart rule code is already used (conflict with cart rule %Id of the cart rule%).</td><td></td></tr><tr><td>Default value</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Caution! If you leave this field blank, the rule will automatically be applied to benefiting customers.</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>This is the code users should enter to apply the voucher to a cart. Either create your own code or generate one by clicking on "Generate".</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td></td><td align="center"></td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td></td><td align="center"></td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#code-1">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Highlight

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                       -</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>If the voucher is not yet in the cart, it will be displayed in the cart summary. </td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#highlight-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Partial use switch toggle button

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                       -</td><td align="center"></td><td></td></tr><tr><td>Default value</td><td>YES</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Only applicable if the voucher value is greater than the cart total. If you do not allow partial use, the voucher value will be lowered to the total order amount. If you allow partial use, however, a new voucher will be created with the remainder.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                        -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                        -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#partial-use-switch-toggle-button-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Priority

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Can only be number</td><td align="center">The priority field is invalid.</td><td></td></tr><tr><td>Default value</td><td>1</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Cart rules are applied by priority. A cart rule with a priority of.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                        -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                        -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#priority-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Status

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>YES</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                       -</td><td align="center"> -</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                       -</td><td align="center"> -</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#status-2">link to the behavior</a></td><td align="center">-</td><td>Status - switch toggle button - Status toggle button is enabled by default. Disabling the toggle will disable the cart ru<strong>atus</strong> - switch toggle button - Status toggle button is enabled by default. Disabling the toggle will disable the cart rule and won't be useable.</td></tr></tbody></table>

## Conditions tab

The condition tab, allows the ability to specify cart rule conditions to determine how the cart rule will be used in the Prestashop.

### Limit to a single customer

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>It can only be an array corresponding to a selected user </td><td align="center">expects parameter 2 to be array, bool given</td><td></td></tr><tr><td>Default value</td><td>Empty</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>Optional: The cart rule will be available to everyone if you leave this field blank.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                       -</td><td align="center"> -</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                       -</td><td align="center"> -</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#limit-to-a-single-customer-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Valid

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>Yes</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Only Dates are allowed</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>"From" date is the date and the "round" hour of the cart rule's creation. <br>"To" date is one month after</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                       -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>The default period is one month.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                       -</td><td align="center"> -</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                       -</td><td align="center"> -</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#valid-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Minimum amount

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Allowed numbers only</td><td align="center">The minimum<strong>_</strong>amount field is invalid.</td><td></td></tr><tr><td>Default value</td><td>0; Default currency of PrestaShop; Tax excluded; Shipping excluded</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>You can choose a minimum amount for the cart either with or without the taxes and shipping.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#minimum-amount-behavior">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

### Total available

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Allowed numbers only</td><td align="center">The quantity field is invalid.</td><td></td></tr><tr><td>Default value</td><td>                     1</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>The cart rule will be applied to the first</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#total-available-behavior">link to the behavior</a></td><td align="center">-</td><td> </td></tr></tbody></table>

### **Total available for each user**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>Allowed numbers only</td><td align="center">The quantity_per_user field is invalid.</td><td></td></tr><tr><td>Default value</td><td>                     1</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>A customer will only be able  to use a cart rule</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#total-available-for-each-user-behavior">link to the behavior</a></td><td align="center">-</td><td><strong>Total available for each user behavior</strong></td></tr></tbody></table>

### Restrictions

Certain conditions can be set for the main cart rule condition.\
Once the first restriction checkbox is marked, the external options will expand. Those are the following:

* **Country selection** - there is a small description text below the checkbox - _This restriction applies to the country of delivery._ Once checkboxed, there will be 2 fields prompted in UI - Selected or Unselected text field values. The values can be transferred to appropriate inputs with the buttons Add or Remove. By default, it is set as uncheckboxed condition.
* **Carrier selection** - this field can set certain carriers, that could be affected by the rule condition. Once checkboxed, there will be 2 fields prompted in UI - Selected or Unselected text field values. The values can be transferred to appropriate inputs with the buttons Add or Remove. By default, it is set as uncheckboxed condition.
* **Customer group selection** - it can be restricted by a Prestashop customers group - by default - Customer, Visitor or Guest. Once checkboxed, there will be 2 fields prompted in UI - Selected or Unselected text field values. The values can be transferred to appropriate inputs with the buttons Add or Remove. By default, it is set as uncheckboxed condition.
* **Compatibility with other cart rules** - this option sets the including of what cart rules can be combined with another cart rules. By default, it is set as uncheckboxed condition, and this option is hidden, when there are no rules created, at least 1 rule should be created in list.
* **Product selection** - this is kind of important condition for cart rule - it can be selected with specific products from whole webshop, that can have the cart rule. By default, it is set as uncheckboxed condition.
* Once the **Product selection** checkbox is marked, the UI will additioinally extend with the appropriate options to adjust. The CTA button with "(+) Product selection" will appear. Clicking the button will show additional operating values - "Number of products required in the cart to enjoy the discount", "Add a rule concerning", "The product(s) are matching one of these" list, Add (+), Remove (X), Choose, Product selection buttons and appropriate text input fields.
* **Number** of products required in the cart to enjoy the discount - defines the operating value, how many products should be added to the cart in Prestashop application in order to get the ability to get a discount. There is a numeric value input field near, which can be set.
* **Add a rule concerning** - defines the operating value, which will be included in creating the rule conditions for certain product (s). By default the dropdown option will be as null value --Choose--. The default values, that are installed by Prestashop are Products, Attributes, Categories, Brands and Suppliers. Choosing, for example, Products, as the value, clicking the (+) Add button will extend the UI with the Product list below. By default, there will be no products added. Once clicking the Choose button, pop-up will appear, and there will be a possibility to add the certain products from left section to the right and backwards. It can be adjusted by clicking the Add or Remove buttons. After closing the popup, the new products will be added to the list. There are options to add additional value once again, modify the existing one or deleting the value from the list.
* **Shop selection** - this selection sets the shop in Prestashop, where to apply the Cart Rule. By default, this field is hidden, if there is no Multistores configured. Once the Shop selection checkbox is marked, the addition UI part will extend with the 2 input area fields. There will be field with Selected shops and Unselected shops. The Multistore Shops can be transferred to the Selected or Unselected fields by appropriate needs. Add or Remove buttons are performing the actions here.

## Actions tab

### Free shipping

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#free-shipping-switch-toggle-button">link to the behavior</a></td><td align="center">-</td><td><strong>Total available for each user behavior</strong></td></tr></tbody></table>

### **Apply a discount**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>None</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#apply-a-discount-behavior">link to the behavior</a></td><td align="center">-</td><td><strong>Total available for each user behavior</strong></td></tr></tbody></table>

### **Exclude discounted products**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>If enabled, the voucher will not apply to products already on sale.</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#exclude-discounted-products-behavior">link to the behavior</a></td><td align="center">-</td><td><strong>Total available for each user behavior</strong></td></tr></tbody></table>

### **Send a free gift**

<table><thead><tr><th>Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>YES</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>NO</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                     -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                     -</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                     -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="edit-or-add-cart-rule.md#send-a-free-gift-1">link to the behavior</a></td><td align="center">-</td><td><strong>Total available for each user behavior</strong></td></tr></tbody></table>

## Behaviors descriptions

### **Name behavior**

Text input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) - it is a mandatory field with a language selector.

### **Description behavior**

Text input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) - to describe the cart rule in more details.

### **Code** behavior

Text input field ([Forms normal UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--normal)) - If the user decide to use a Code for the cart rule then the code has to be unique to validate the form. By clicking Generate, a code is generated automatically with a unique code name. If the code is left empty, then the cart rule will automatically be applied to customers' cart that matches the cart rule conditions.

### **Highlight** behavior

Switch toggle button ([Forms switch UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story))- If enabled, the cart rule will be displayed in cart summary. When there is no Code set, the Highlight switch toggle button is hidden.

### **Partial use switch toggle button** behavior

If this switch toggle button ([Forms switch UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) is enabled, when the total cart of the checkout amount is smaller than the cart rule amount, a cart rule is created with the remaining sum. Note, that partial usage function becomes as a new cart rule and with the new cart rule name with "-2" prefix added and with the remaining sum. The conditions remain the same, except the cart rule quantity availability - it remains just 1 for each user.

### **Priority** behavior

This numeric input field ([Forms numbers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) defines the calculation priority of the cart rules at the checkout process. A cart rule with the priority set to 1 will be applied before the cart rule set to 2. The lower the priority value, the higher the priority of the cart rule. If there are multiple cart rules applied at the checkout with the identical priority value, the priority will be defined between the cart rule by their Cart Rule ID, the lower is the cart rule ID, the higher the priority.

### Status behavior

Switch toggle button  ([Forms switch UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) - when enabled button enables cart rule. Disabling the toggle will disable the cart rule and won't be useable.

### **Limit to a single customer** behavior

Search input - the user can search by customer name or email in order to set the Cart rule condition for one customer.

### **Valid** behavior

2 dates picker - The date picker "From" and "To" define the period of availability of the cart rule. Past these dates or before these dates, the cart rule can't be used.&#x20;

### **Minimum amount** behavior

This numeric input field ([Forms numbers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) sets minimum amount from which the customers will can use the cart rule. As well, the currency can be set, if prices should affected with taxes or without taxes and if shipping is affected too.&#x20;

### **Total available** behavior

This numeric input field ([Forms numbers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) describes the quantity of the cart rules that can be used.

### **Total available for each user behavior**

This numeric input field ([Forms numbers UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--number)) sets the price rules amount for certain users separately.&#x20;

### **Free shipping behavior**&#x20;

This setting creates rule that will initiate a free shipping method for customer in checkout form.

### **Apply a discount** behavior

The Apply a discount setting has radio buttons ([Forms radio buttons UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--radio-buttons)) and its options are:

#### Percentage

It canan be set, and the cart price will be affected by certain amount of percentage discount, after executing the voucher. If this value is set, the following elements will load in the UI:

* **Value** - numeric input field with percentage icon, to set the percentage amount.
* **Apply a discount to** - available values to set for:
  * **Order (without shipping)**
  * **Specific product** - search product field appears below - it will set the ability to search the certain product.
  * **Matching products dropdown** - it will appear when there will be some characters typed in the "Product" field.
  * **Cheapest product** - apply the discount contidions to the cheapest product.
  * **Selected product(s)** - appears only when Conditions tab is assigned to some product or products, as the exclamation mark indicator with link displays this as well.
* **Exclude discounted products** - toggle switch button, if enabled, voucher will not apply to products already on sale.

#### Amount

The user will get a discount of a certain amount of price. Also the **Currency** can be set and the **Taxes conditions** in the following inputs as well.

* **Apply a discount to** - available values to set for:
  * **Order (without shipping)**
  * **Specific product** - search product field appears below - it will set the ability to search the certain product.
  * **Matching products dropdown** - it will appear when there will be some characters typed in the "Product" field.

#### None

In that case user of the checkout will not get any discounting at all.

### **Exclude discounted products** behavior&#x20;

Exclude discounted products toggle switch button ([Forms switch UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)) appears when Apply a discount Percent radio button is checked. With other Apply a discount options this toggle button is hidden. If enabled Exclude discount products, voucher will not apply to products already on sale.

### **Send a free gift behavior**&#x20;

Switch toggle button ([Forms switch UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--switch-story)), once Enabled, it shows Search a product field, where a specific product can be added as a gift.

## Multistores functionality

This page is Multistores independent (todo link) page.

Once the Multistores are configured in Prestashop, Cart Rules can be applied for certain shop. Applying the Cart Rule for certain shop can be configured by navigating to Cart Rules > Edit section > Configure Tab. There is a checkbox in Restriction option. Clicking the checkbox of **Shop selection** option, enables switching the appropriate Prestashop shop to the "Selected shops" area. This enables applying the Cart Rule for certain Prestashop Multistore.

