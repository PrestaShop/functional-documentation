# Shopping Cart

## Description

This dashboard is displaying the information about the Shopping Cart initiator - the customer, visitor or guest visitor who generated the Cart. It can be accessed by selecting the Shopping Cart row and clicking on the View button on the right of the row.

<figure><img src="../../../../../.gitbook/assets/image (1) (4) (1).png" alt="View Shoppinc Cart UI"><figcaption><p>View Shopping Cart User Interface</p></figcaption></figure>

### QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/orders/shopping-carts.html)

## Common components <a href="#common-components" id="common-components"></a>

* [Breadcrumbs navigation](broken-reference) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](broken-reference) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help Button](broken-reference) - [Buttons Outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).

## The elements of the page UI

### Registered customer in Prestashop

* **Total Cart** - Total amount of the cart
* **Customer information** - a section, that lists the customer:
  * first name,
  * last name,
  * account registration date,
  * valid orders placed - total number of orders, that user has fully completed.
  * total spent since registration,
  * the customer email. The customer name and last name contains a link, that directs to the Customer Account page in Prestashop. Email link is also implemented with a link, once clicked initiates the email composing.
* **Order information** - if the Order is made, then the link appears with the Order number with the hashtag near. This link is clickable, it redirects to the specific order of the Customer has made. If Order is not made and Cart is stated as Non ordered cart - then new Order can be created by clicking the button _Create an order from this cart_.
* **Made on** - the exact timestamp registered when the Order was made.

### Unregistered customer in Prestashop

* **Total Cart** - the numeric value, that describes the total amount that a single customer has so far.
* **Customer information** - the indication that _Guest is not registered_, so none of the additional information available.
* **Order information** - the indication that _No order was created from this cart_.
* **Made on** - the exact timestamp registered when the Order was made.

#### Cart Summary

The whole section table, where the orders of the customer are displayed. The elements of UI are basic: product image, product name with the link into the product editing, unit price, quantity, stock and total cart sum.

**Total cost of products, Total shipping costs** and **Total** summary is also defined, counting the total sum from the products.

Tax included or Tax excluded yellow warning notification is displayed _For this particular customer group, prices are displayed as: Tax included_ or _For this particular customer group, prices are displayed as: Tax excluded_ in the end of the Cart summary list.

## Multistores functionality

Multistores independent (todo link) page.

There is a Multistore switcher in the top-middle of the page, however the View Shopping Cart page is not impacted by any of the Multistore in Prestashop.
