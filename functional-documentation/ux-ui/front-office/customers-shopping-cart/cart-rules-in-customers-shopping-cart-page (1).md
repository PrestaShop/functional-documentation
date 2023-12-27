# Cart Rules in customer's shopping cart page



<figure><img src="../../../../.gitbook/assets/Frame 3.png" alt=""><figcaption><p>Fig. 1</p></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/Frame 5.png" alt=""><figcaption><p>Fig. 2</p></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/Frame 6.png" alt=""><figcaption><p>Fig. 3</p></figcaption></figure>



This page is where a customer can see every item previously added to his cart.

A customer land on this page when :

* Clicking on the “Shopping cart” (1 on fig.4) button to access the content of the cart and finalize their order.
* Clicking on “Proceed to checkout” (2 on fig.5) after a product has been successfully added to the shopping cart.

<figure><img src="../../../../.gitbook/assets/Frame 4.png" alt=""><figcaption><p>Fig. 4</p></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/Frame 2.png" alt=""><figcaption><p>Fig. 5</p></figcaption></figure>

###

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/fo/classic/cart.html)

### [Tests](https://github.com/PrestaShop/PrestaShop/blob/7f9fb70c179f3b014656c28a5157ec6739a16a81/tests/UI/pages/FO/cart/index.js)



1 – Header

*   a – Contact Us Link

    | Description   | Value                                                                   |
    | ------------- | ----------------------------------------------------------------------- |
    | Mandatory     | -                                                                       |
    | Default value | -                                                                       |
    | Help text     | -                                                                       |
    | Tool tips     | -                                                                       |
    | Behavior      | When clicking on that element, the visitor is sent to the contact page. |
*   b – Shop Logo

    | Description   | Value                                                                    |
    | ------------- | ------------------------------------------------------------------------ |
    | Mandatory     | -                                                                        |
    | Default value | -                                                                        |
    | Help text     | -                                                                        |
    | Tool tips     | -                                                                        |
    | Behavior      | When clicking on that element, the visitor is sent to the shop homepage. |
*   c – Shop Menu

    | Description   | Value                                                                                   |
    | ------------- | --------------------------------------------------------------------------------------- |
    | Mandatory     | -                                                                                       |
    | Default value | -                                                                                       |
    | Help text     | -                                                                                       |
    | Tool tips     | -                                                                                       |
    | Behavior      | When clicking on one of the shop menu element, the visitor is sent to the related page. |
*   d – Sign-in/Sign-out Link with Icon

    | Description   | Value                                                                                                           |
    | ------------- | --------------------------------------------------------------------------------------------------------------- |
    | Mandatory     | -                                                                                                               |
    | Default value | -                                                                                                               |
    | Help text     | -                                                                                                               |
    | Tool tips     | -                                                                                                               |
    | Behavior      | When clicking on that element, the visitor is sent to the sign-in page or is disconnected if he previously was. |
*   e – Cart Button

    | Description   | Value                                                                |
    | ------------- | -------------------------------------------------------------------- |
    | Mandatory     | -                                                                    |
    | Default value | -                                                                    |
    | Help text     | -                                                                    |
    | Tool tips     | -                                                                    |
    | Behavior      | When clicking on that element, the visitor is sent to the cart page. |
*   f – Search our catalog field

    | Description   | Value                                                                                                                                                                   |
    | ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | Mandatory     | -                                                                                                                                                                       |
    | Default value | -                                                                                                                                                                       |
    | Help text     | -                                                                                                                                                                       |
    | Tool tips     | -                                                                                                                                                                       |
    | Behavior      | When clicking on the field, the visitor can write any word related to the product he wants to find, and when hitting enter, he will be sent to the search results page. |

2 – Shopping Cart bloc

* a – Bloc title

3 – Cart item

* a – Product Picture
* b – Product Name
* c – Product Initial Price
* d – Product New Price
* e – Specific Price Impact
* f – Product Characteristics
*   g – Product Quantity

    | Description   | Value                                                                            |
    | ------------- | -------------------------------------------------------------------------------- |
    | Mandatory     | YES                                                                              |
    | Default value | 1                                                                                |
    | Help text     | -                                                                                |
    | Tool tips     | -                                                                                |
    | Behavior      | This field can be filled manually or by using arrows to upper or lower the value |
* h – Product Final Price
*   i – Remove Product Action

    | Description   | Value                                                               |
    | ------------- | ------------------------------------------------------------------- |
    | Mandatory     | -                                                                   |
    | Default value | -                                                                   |
    | Help text     | -                                                                   |
    | Tool tips     | -                                                                   |
    | Behavior      | When clicking on that element, the product is removed from the cart |

4 – Continue shopping link

5 – Pricing bloc

* a – Number of items
* b – Total of items’ final prices
* c – Total after applying discounts, taxes included
* d – Taxes included details
*   e – Link to open or close the code form when at least one cart rule is available and should be applied using a code

    | Description   | Value                                                                                                          |
    | ------------- | -------------------------------------------------------------------------------------------------------------- |
    | Mandatory     | -                                                                                                              |
    | Default value | -                                                                                                              |
    | Help text     | -                                                                                                              |
    | Tool tips     | -                                                                                                              |
    | Behavior      | When clicking on that link, it rather opens or closes the discount code form, according to its previous state. |
* f – Discount(s) amount
* g – Name of an applied / an available cart rule
* h – Discount amount related to the applied cart rule
*   i – Remove Discount icon

    | Description   | Value                                                                |
    | ------------- | -------------------------------------------------------------------- |
    | Mandatory     | -                                                                    |
    | Default value | -                                                                    |
    | Help text     | -                                                                    |
    | Tool tips     | -                                                                    |
    | Behavior      | When clicking on that element, the discount is removed from the cart |
* j – Code related to an available cart rule
* k – code form when at least one cart rule is available and should be applied using a code

6 – Proceed to checkout Button

| Description   | Value                                                                    |
| ------------- | ------------------------------------------------------------------------ |
| Mandatory     | -                                                                        |
| Default value | -                                                                        |
| Help text     | -                                                                        |
| Tool tips     | -                                                                        |
| Behavior      | When clicking on that element, the visitor is sent to the checkout page. |

### Error messages



* This Voucher has expired
* This voucher is disabled
* This voucher has already been used
* This voucher is not valid yet
* You cannot use this voucher anymore (usage limit reached)
* You cannot use this voucher
* You cannot use this voucher with these products
* You must choose a delivery address before applying this voucher to your order
* You cannot use this voucher in your country of delivery
* You must choose a carrier before applying this voucher to your order
* You cannot use this voucher with this carrier
* You cannot use this voucher on products on sale
* You have not reached the minimum amount required to use this voucher
* This voucher is already in your cart
* This voucher is not combinable with an other voucher already in your cart: %s
* You cannot use this voucher in an empty cart
* You cannot use this voucher because it has manually been removed.
* You must enter a voucher code.
* The voucher code is invalid.
* This voucher does not exist.
