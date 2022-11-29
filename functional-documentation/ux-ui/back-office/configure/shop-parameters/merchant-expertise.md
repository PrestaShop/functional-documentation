# Merchant expertise

Merchant expertise page help PrestaShop users keep track of their progress. Unblocked badges helps to see how much expertise as e-merchants have grown and progressed during time.

<figure><img src="../../../../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Merchant expertise user interface</p></figcaption></figure>

## Common components

* ​[Breadcrumbs navigation](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/breadcrumbs) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/heading-of-the-page) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* ​[Help button](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/bFfZ6x0W3PrldLavAttl/functional-documentation/ux-ui/common-components/help-button) - [Buttons outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* PrestaShop logo (todo link)
* PrestaShop version number (todo link)
* Search (todo link)
* Bell icon (todo link)
* Trophy icon (todo link)
* Account icon (todo link)
* Shop switcher (todo link)

## Become an e-commerce expert in leaps and bounds! block

This block contains these elements:

* **List icon** - it is in the left side of block.
* **Title** - it is centered on top of block and it is:\
  _Become an e-commerce expert in leaps and bounds!_
*   _**Message** -_ is under title and it is:\
    _In order to make you succeed in the e-commerce world, we have created a system of badges and points to help you monitor your progress as a merchant. The system has three levels:_

    _1.Your use of key e-commerce features on your store_ \
    _2.Your sales performances_ \
    _3.Your presence in international markets_ \
    _The more progress your store makes, the more badges and points you earn. Take advantage and check it out below!_
* **Find an expert** block - it has a person icon and a message:\
  _Our team of experts is available to help, feel free to contact them!_\
  __It also has CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)) with text: _Find an expert._ Button text become underlined when the button is hovered. Once button clicked opens page _Find a PrestaShop agency or expert_ in the same window.
* **Completion level** - is shown in progress bar ([Progress bar UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/progress-bar--progress-bar)), level progress number and progress in percent.

## Merchant expertise badges

There are three blocks of badges that shows merchant expertise:

* Features
* Achievements
* International

Each block has filter on its left side. Badges are laid out in rows. Badge shows tooltip on top ([Tooltips UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/tooltips--tooltips)) when the mouse pointer is hovered. \
Each validated badges are shown in color. Badges that are not validated yet are shown uncolored. Badges have hexagon shape frame around badge icon and stars.\
Badges has differen number of stars. Stars number shows level of badge. There are these levels by stars number:

* **One star** - Beginner
* **Two stars** - Pro
* **Three stars** - Expert
* **Four stars** - Wizard
* **Five stars** - Guru
* **Six stars** - Legend.

### Feature badges block&#x20;

#### Filter unit

This block has filtered unit for filtration by Type, Status and Level.&#x20;

**Type filter** has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Partners
* SEO
* Site Performance
* Payment
* Shipping
* Catalog Size
* Contact information
* Customization
* Addons
* Multistores
* Your Team's Employees
* Product Pictures
* WebService

By default, filter is selected on All. When other filter option is chosen shows only that type of badges.

**Status filter** has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Validated
* Not Validated

By default, filter is selected on All. When other filter option is chosen shows only certain status badges.

**Level filter** - has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Beginner
* Pro
* Expert
* Wizard
* Guru
* Legend

By default, filter is selected on All. When other filter option is chosen shows only that level badges. When there are no badges after filtration appear notification and it is:\
_No badge in this section._\
__While filtering, badges appear or disappear with smooth animation.

#### **Features badges**

| Title                 | Stars number | Icon             | Tooltip                                                                                                               |
| --------------------- | ------------ | ---------------- | --------------------------------------------------------------------------------------------------------------------- |
| SEO                   | 1            | Magnifying glass | You enabled the URL rewriting through the tab "Preferences > SEO and URLs".                                           |
| Site Performance      | 1            | Speedometer      | You enabled CCC (Combine, Compress and Cache), Rijndael and Smarty through the tab Advanced parameters > Performance. |
| Site Performance      | 2            | Speedometer      | You enabled media servers through the tab Advanced parameters > Performance.                                          |
| Payment               | 1            | Wallet           | You configured a payment solution on your shop.                                                                       |
| Payment               | 2            | Wallet           | You offer two different payment methods to your customers.                                                            |
| Payment               | 3            | Wallet           | You offer three different payment methods to your customers.                                                          |
| Shipping              | 1            | Truck            | You configured a carrier on your shop.                                                                                |
| Shipping              | 2            | Truck            | You offer two shipping solutions  (carriers) to your customers.                                                       |
| Shipping              | 3            | Truck            | You offer three shipping solutions  (carriers) to your customers.                                                     |
| Catalog Size          | 1            | Catalog          | You added your first product to your catalog.                                                                         |
| Catalog Size          | 2            | Catalog          | You have 10 products within your catalog.                                                                             |
| Catalog Size          | 3            | Catalog          | You have 100 products within your catalog.                                                                            |
| Catalog Size          | 4            | Catalog          | You have 1,000 products within your catalog.                                                                          |
| Catalog Size          | 5            | Catalog          | You have 10,000 products within your catalog.                                                                         |
| Catalog Size          | 6            | Catalog          | You have 100,000 products within your catalog.                                                                        |
| Contact Information   | 1            | Phone            | You configured your phone number so your customers can reach you!                                                     |
| Contact Information   | 2            | Phone            | You added a third email address to your contact form.                                                                 |
| Contact Information   | 3            | Phone            | You suggest a total of 5 departments to be reached by your customers via your contact form.                           |
| Customization         | 1            | Art supplies     | You uploaded your own logo.                                                                                           |
| Customization         | 2            | Art supplies     | You installed a new template.                                                                                         |
| Customization         | 3            | Art supplies     | First CMS page added to your catalog.                                                                                 |
| Addons                | 1            | Puzzle           | You connected your back-office to the Addons platfor using your PrestaShop Addons account.                            |
| Multistores           | 1            | Multistore       | You enabled the Multistores feature.                                                                                  |
| Multistores           | 2            | Multistore       | You manage two shops with the Multistores feature.                                                                    |
| Multistores           | 3            | Multistore       | You manage two different groups of shops with the Multistores feature.                                                |
| Multistores           | 4            | Multistore       | You manage five shops with the Multistores feature.                                                                   |
| Multistores           | 5            | Multistore       | You manage five different groups of shops with the Multistores feature.                                               |
| Your Team's Employees | 1            | Team             | First employee account added to your shop.                                                                            |
| Your Team's Employees | 2            | Team             | 3 employee accounts added to your shop.                                                                               |
| Your Team's Employees | 3            | Team             | 5 employee accounts added to your shop.                                                                               |
| Your Team's Employees | 4            | Team             | 10 employee accounts added to your shop.                                                                              |
| Your Team's Employees | 5            | Team             | 20 employee accounts added to your shop.                                                                              |
| Your Team's Employees | 6            | Team             | 40 employee accounts added to your shop.                                                                              |
| Product Pictures      | 1            | Camera           | First photo added to your catalog.                                                                                    |
| Product Pictures      | 2            | Camera           | 50 photos added to your catalog.                                                                                      |
| Product Pictures      | 3            | Camera           | 100 photos added to your catalog.                                                                                     |
| Product Pictures      | 4            | Camera           | 1,000 photos added to your catalog.                                                                                   |
| Product Pictures      | 5            | Camera           | 10,000 photos added to your catalog.                                                                                  |
| Product Pictures      | 6            | Camera           | 50,000 photos added to your catalog.                                                                                  |
| Webservice x1         | 1            | Repair           | First webservice account added to your shop.                                                                          |
| Webservice x2         | 2            | Repair           | 2 webservice accounts added to your shop.                                                                             |
| Webservice x3         | 3            | Repair           | 3 webservice accounts added to your shop.                                                                             |
| Webservice x4         | 4            | Repair           | 4 webservice accounts added to your shop.                                                                             |

### **Achievements badges block**

#### Filter unit

This block has filter unit for filtration by Type, Status and Level.&#x20;

**Type filter** has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Days of Experience
* Revenue
* Visitors
* Customer Carts
* Orders
* Customer Service Threads
* Customers
* Cart Rules&#x20;
* International Orders
* Store

By default filter is selected on All. When other filter option is chosen shows only that type badges.

**Status filter** has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Validated
* Not Validated

By default filter is selected on All. When other filter option is chosen shows only that status badges.

**Level filter** - has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Beginner
* Pro
* Expert
* Wizard
* Guru
* Legend

By default, filter is selected on All. When the other filter option is chosen, it shows only certain level badges.

**Achievements badges**

| Title                    | Stars number | Icon          | Tooltip                                                       |
| ------------------------ | ------------ | ------------- | ------------------------------------------------------------- |
| Days of Experience       | 1            | Calendar      | You just installed PrestaShop!                                |
| Days of Experience       | 2            | Calendar      | You installed PrestaShop a week ago!                          |
| Days of Experience       | 3            | Calendar      | You installed PrestaShop a month ago!                         |
| Days of Experience       | 4            | Calendar      | You installed PrestaShop six months ago!                      |
| Days of Experience       | 5            | Calendar      | You installed PrestaShop a year ago!                          |
| Days of Experience       | 6            | Calendar      | You installed PrestaShop two years ago!                       |
| Revenue                  | 1            | Cash          | You get this badge when you reach 200 USD in sales.           |
| Revenue                  | 2            | Cash          | You get this badge when you reach 1000 USD in sales.          |
| Revenue                  | 3            | Cash          | You get this badge when you reach 1000 USD in sales.          |
| Revenue                  | 4            | Cash          | You get this badge when you reach 200 USD in sales.           |
| Revenue                  | 5            | Cash          | You get this badge when you reach 1000 USD in sales.          |
| Revenue                  | 6            | Cash          | You get this badge when you reach 1000 USD in sales.          |
| Visitors                 | 1            | Visitor       | You reached 10 visitors!                                      |
| Visitors                 | 2            | Visitor       | You reached 100 visitors!                                     |
| Visitors                 | 3            | Visitor       | You reached 1,000 visitors!                                   |
| Visitors                 | 4            | Visitor       | You reached 10,000 visitors!                                  |
| Visitors                 | 5            | Visitor       | You reached 100,000 visitors!                                 |
| Visitors                 | 6            | Visitor       | You reached 1,000,000 visitors!                               |
| Customer Carts           | 1            | Shopping cart | Two carts have been created by visitors.                      |
| Customer Carts           | 2            | Shopping cart | Ten carts have been created by visitors.                      |
| Customer Carts           | 3            | Shopping cart | A hundred carts have been created by visitors on your shop.   |
| Customer Carts           | 4            | Shopping cart | A thousand carts have been created by visitors on your shop.  |
| Customer Carts           | 5            | Shopping cart | 10,000 carts have been created by visitors.                   |
| Customer Carts           | 6            | Shopping cart | 100,000 carts have been created by visitors.                  |
| Orders                   | 1            | Order         | You received your first order.                                |
| Orders                   | 2            | Order         | 10 orders have been placed through your online shop.          |
| Orders                   | 3            | Order         | You received 100 orders through your online shop.             |
| Orders                   | 4            | Order         | You received 1,000 orders through your online shop, congrats. |
| Orders                   | 5            | Order         | You received 10,000 orders through your online shop, cheers.  |
| Orders                   | 6            | Order         | You received 100,000 orders through your online shop!         |
| Customer Service Threads | 1            | Text message  | You received your first customer's message.                   |
| Customer Service Threads | 2            | Text message  | You received 10 messages form your customers.                 |
| Customer Service Threads | 3            | Text message  | You received 100 messages form your customers.                |
| Customer Service Threads | 4            | Text message  | You received 1,000 messages form your customers.              |
| Customer Service Threads | 5            | Text message  | You received 10,000 messages form your customers.             |
| Customer Service Threads | 6            | Text message  | You received 100,000 messages form your customers.            |
| Customers                | 1            | Customer      | You got the first customer registered on your shop!           |
| Customers                | 2            | Customer      | You have over 10 customers registered on your shop.           |
| Customers                | 3            | Customer      | You have over 100 customers registered on your shop.          |
| Customers                | 4            | Customer      | You have over 1,000 customers registered on your shop.        |
| Customers                | 5            | Customer      | You have over 10,000 customers registered on your shop.       |
| Customers                | 6            | Customer      | You have over 100,000 customers registered on your shop.      |
| Cart Rules               | 1            | Discount      | First cart rules configured on your shop.                     |
| Cart Rules               | 2            | Discount      | You have 10 cart rules configured on your shop.               |
| Cart Rules               | 3            | Discount      | You have 100 cart rules configured on your shop.              |
| Cart Rules               | 4            | Discount      | You have 500 cart rules configured on your shop.              |
| Cart Rules               | 5            | Discount      | You have 1,000 cart rules configured on your shop.            |
| Cart Rules               | 6            | Discount      | You have 5,000 cart rules configured on your shop.            |
| International Orders     | 1            | Earth globe   | First international order placed on your shop.                |
| International Orders     | 2            | Earth globe   | 10 international orders placed on your shop.                  |
| International Orders     | 3            | Earth globe   | 100 international orders placed on your shop!                 |
| International Orders     | 4            | Earth globe   | 1,000 international orders placed on your shop!               |
| International Orders     | 5            | Earth globe   | 5,000 international orders placed on your shop!               |
| International Orders     | 6            | Earth globe   | 10,000 international orders placed on your shop!              |
| Store                    | 1            | Store         | First store configured on your shop!                          |
| Store                    | 2            | Store         | You have 2 stores configured on your shop.                    |
| Store                    | 3            | Store         | You have 5 stores configured on your shop.                    |
| Store                    | 4            | Store         | You have 10 stores configured on your shop.                   |
| Store                    | 5            | Store         | You have 20 stores configured on your shop.                   |
| Store                    | 6            | Store         | You have 50 stores configured on your shop.                   |

### **International badge block**

#### Filter unit

This block has filtered unit for filtration by **** Status.&#x20;

**Status filter** has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Validated
* Not Validated

By default, filter is selected on All. When other filter option is chosen shows only that status badges.

#### **International badge**

| Title         | Icon        |                                           |
| ------------- | ----------- | ----------------------------------------- |
| North America | Earth globe | You got your first sale in North America. |
| Oceania       | Earth globe | You got your first sale in Oceania.       |
| South America | Earth globe | You got your first sale in South America. |
| Asia          | Earth globe | You got your first sale in Asia.          |
| Europe        | Earth globe | You got your first sale in Europe!        |
| Africa        | Earth globe | You got your first sale in Africa.        |
| Maghreb       | Earth globe | You got your first sale in Maghreb.       |

## Multistores behavior

This page is Multistores independent page.
