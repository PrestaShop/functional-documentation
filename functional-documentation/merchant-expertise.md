# Merchant expertise

Merchant expertise page help PrestaShop users keep track of their progress. Unblocked badges helps to see how much expertise as e-merchants have grown and progressed during time.

<figure><img src="../../../../../.gitbook/assets/image (2) (3) (2).png" alt=""><figcaption><p>Merchant expertise user interface</p></figcaption></figure>

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
  It also has CTA button ([Buttons basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/buttons--basics)) with text: _Find an expert._ Button text become underlined when the button is hovered. Once button clicked opens page _Find a PrestaShop agency or expert_ in the same window.
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
While filtering, badges appear or disappear with smooth animation.

#### **Features badges**

<table><thead><tr><th width="201">Title</th><th width="148">Stars number</th><th width="167">Icon</th><th width="181">Tooltip</th></tr></thead><tbody><tr><td>SEO</td><td>1</td><td>Magnifying glass</td><td>You enabled the URL rewriting through the tab "Preferences > SEO and URLs".</td></tr><tr><td>Site Performance</td><td>1</td><td>Speedometer</td><td>You enabled CCC (Combine, Compress and Cache), Rijndael and Smarty through the tab Advanced parameters > Performance.</td></tr><tr><td>Site Performance</td><td>2</td><td>Speedometer</td><td>You enabled media servers through the tab Advanced parameters > Performance.</td></tr><tr><td>Payment</td><td>1</td><td>Wallet</td><td>You configured a payment solution on your shop.</td></tr><tr><td>Payment</td><td>2</td><td>Wallet</td><td>You offer two different payment methods to your customers.</td></tr><tr><td>Payment</td><td>3</td><td>Wallet</td><td>You offer three different payment methods to your customers.</td></tr><tr><td>Shipping</td><td>1</td><td>Truck</td><td>You configured a carrier on your shop. </td></tr><tr><td>Shipping</td><td>2</td><td>Truck</td><td>You offer two shipping solutions  (carriers) to your customers.</td></tr><tr><td>Shipping</td><td>3</td><td>Truck</td><td>You offer three shipping solutions  (carriers) to your customers.</td></tr><tr><td>Catalog Size</td><td>1</td><td>Catalog</td><td>You added your first product to your catalog.</td></tr><tr><td>Catalog Size</td><td>2</td><td>Catalog</td><td>You have 10 products within your catalog.</td></tr><tr><td>Catalog Size</td><td>3</td><td>Catalog</td><td>You have 100 products within your catalog.</td></tr><tr><td>Catalog Size</td><td>4</td><td>Catalog</td><td>You have 1,000 products within your catalog.</td></tr><tr><td>Catalog Size</td><td>5</td><td>Catalog</td><td>You have 10,000 products within your catalog.</td></tr><tr><td>Catalog Size</td><td>6</td><td>Catalog</td><td>You have 100,000 products within your catalog.</td></tr><tr><td>Contact Information</td><td>1</td><td>Phone</td><td>You configured your phone number so your customers can reach you!</td></tr><tr><td>Contact Information</td><td>2</td><td>Phone</td><td>You added a third email address to your contact form.</td></tr><tr><td>Contact Information</td><td>3</td><td>Phone</td><td>You suggest a total of 5 departments to be reached by your customers via your contact form.</td></tr><tr><td>Customization</td><td>1</td><td>Art supplies</td><td>You uploaded your own logo.</td></tr><tr><td>Customization</td><td>2</td><td>Art supplies</td><td>You installed a new template.</td></tr><tr><td>Customization</td><td>3</td><td>Art supplies</td><td>First CMS page added to your catalog.</td></tr><tr><td>Addons</td><td>1</td><td>Puzzle</td><td>You connected your back-office to the Addons platfor using your PrestaShop Addons account.</td></tr><tr><td>Multistores</td><td>1</td><td>Multistore</td><td>You enabled the Multistores feature.</td></tr><tr><td>Multistores</td><td>2</td><td>Multistore</td><td>You manage two shops with the Multistores feature.</td></tr><tr><td>Multistores</td><td>3</td><td>Multistore</td><td>You manage two different groups of shops with the Multistores feature.</td></tr><tr><td>Multistores</td><td>4</td><td>Multistore</td><td>You manage five shops with the Multistores feature.</td></tr><tr><td>Multistores</td><td>5</td><td>Multistore</td><td>You manage five different groups of shops with the Multistores feature.</td></tr><tr><td>Your Team's Employees</td><td>1</td><td>Team</td><td>First employee account added to your shop.</td></tr><tr><td>Your Team's Employees</td><td>2</td><td>Team</td><td>3 employee accounts added to your shop.</td></tr><tr><td>Your Team's Employees</td><td>3</td><td>Team</td><td>5 employee accounts added to your shop.</td></tr><tr><td>Your Team's Employees</td><td>4</td><td>Team</td><td>10 employee accounts added to your shop.</td></tr><tr><td>Your Team's Employees</td><td>5</td><td>Team</td><td>20 employee accounts added to your shop.</td></tr><tr><td>Your Team's Employees</td><td>6</td><td>Team</td><td>40 employee accounts added to your shop.</td></tr><tr><td>Product Pictures</td><td>1</td><td>Camera</td><td>First photo added to your catalog.</td></tr><tr><td>Product Pictures</td><td>2</td><td>Camera</td><td>50 photos added to your catalog.</td></tr><tr><td>Product Pictures</td><td>3</td><td>Camera</td><td>100 photos added to your catalog.</td></tr><tr><td>Product Pictures</td><td>4</td><td>Camera</td><td>1,000 photos added to your catalog.</td></tr><tr><td>Product Pictures</td><td>5</td><td>Camera</td><td>10,000 photos added to your catalog.</td></tr><tr><td>Product Pictures</td><td>6</td><td>Camera</td><td>50,000 photos added to your catalog.</td></tr><tr><td>Webservice x1</td><td>1</td><td>Repair</td><td>First webservice account added to your shop.</td></tr><tr><td>Webservice x2</td><td>2</td><td>Repair</td><td>2 webservice accounts added to your shop.</td></tr><tr><td>Webservice x3</td><td>3</td><td>Repair</td><td>3 webservice accounts added to your shop.</td></tr><tr><td>Webservice x4</td><td>4</td><td>Repair</td><td>4 webservice accounts added to your shop.</td></tr></tbody></table>

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

<table><thead><tr><th width="164">Title</th><th width="95">Stars number</th><th width="115">Icon</th><th>Tooltip</th></tr></thead><tbody><tr><td>Days of Experience</td><td>1</td><td>Calendar</td><td>You just installed PrestaShop!</td></tr><tr><td>Days of Experience</td><td>2</td><td>Calendar</td><td>You installed PrestaShop a week ago!</td></tr><tr><td>Days of Experience</td><td>3</td><td>Calendar</td><td>You installed PrestaShop a month ago!</td></tr><tr><td>Days of Experience</td><td>4</td><td>Calendar</td><td>You installed PrestaShop six months ago!</td></tr><tr><td>Days of Experience</td><td>5</td><td>Calendar</td><td>You installed PrestaShop a year ago!</td></tr><tr><td>Days of Experience</td><td>6</td><td>Calendar</td><td>You installed PrestaShop two years ago!</td></tr><tr><td>Revenue</td><td>1</td><td>Cash</td><td>You get this badge when you reach 200 USD in sales. </td></tr><tr><td>Revenue</td><td>2</td><td>Cash</td><td>You get this badge when you reach 1000 USD in sales. </td></tr><tr><td>Revenue</td><td>3</td><td>Cash</td><td>You get this badge when you reach 1000 USD in sales. </td></tr><tr><td>Revenue</td><td>4</td><td>Cash</td><td>You get this badge when you reach 200 USD in sales. </td></tr><tr><td>Revenue</td><td>5</td><td>Cash</td><td>You get this badge when you reach 1000 USD in sales. </td></tr><tr><td>Revenue</td><td>6</td><td>Cash</td><td>You get this badge when you reach 1000 USD in sales. </td></tr><tr><td>Visitors</td><td>1</td><td>Visitor</td><td>You reached 10 visitors!</td></tr><tr><td>Visitors</td><td>2</td><td>Visitor</td><td>You reached 100 visitors!</td></tr><tr><td>Visitors</td><td>3</td><td>Visitor</td><td>You reached 1,000 visitors!</td></tr><tr><td>Visitors</td><td>4</td><td>Visitor</td><td>You reached 10,000 visitors!</td></tr><tr><td>Visitors</td><td>5</td><td>Visitor</td><td>You reached 100,000 visitors!</td></tr><tr><td>Visitors</td><td>6</td><td>Visitor</td><td>You reached 1,000,000 visitors!</td></tr><tr><td>Customer Carts</td><td>1</td><td>Shopping cart</td><td>Two carts have been created by visitors.</td></tr><tr><td>Customer Carts</td><td>2</td><td>Shopping cart</td><td>Ten carts have been created by visitors.</td></tr><tr><td>Customer Carts</td><td>3</td><td>Shopping cart</td><td>A hundred carts have been created by visitors on your shop.</td></tr><tr><td>Customer Carts</td><td>4</td><td>Shopping cart</td><td>A thousand carts have been created by visitors on your shop.</td></tr><tr><td>Customer Carts</td><td>5</td><td>Shopping cart</td><td>10,000 carts have been created by visitors.</td></tr><tr><td>Customer Carts</td><td>6</td><td>Shopping cart</td><td>100,000 carts have been created by visitors.</td></tr><tr><td>Orders</td><td>1</td><td>Order</td><td>You received your first order.</td></tr><tr><td>Orders</td><td>2</td><td>Order</td><td>10 orders have been placed through your online shop.</td></tr><tr><td>Orders</td><td>3</td><td>Order</td><td>You received 100 orders through your online shop.</td></tr><tr><td>Orders</td><td>4</td><td>Order</td><td>You received 1,000 orders through your online shop, congrats.</td></tr><tr><td>Orders</td><td>5</td><td>Order</td><td>You received 10,000 orders through your online shop, cheers.</td></tr><tr><td>Orders</td><td>6</td><td>Order</td><td>You received 100,000 orders through your online shop!</td></tr><tr><td>Customer Service Threads</td><td>1</td><td>Text message</td><td>You received your first customer's message.</td></tr><tr><td>Customer Service Threads</td><td>2</td><td>Text message</td><td>You received 10 messages form your customers.</td></tr><tr><td>Customer Service Threads</td><td>3</td><td>Text message</td><td>You received 100 messages form your customers.</td></tr><tr><td>Customer Service Threads</td><td>4</td><td>Text message</td><td>You received 1,000 messages form your customers.</td></tr><tr><td>Customer Service Threads</td><td>5</td><td>Text message</td><td>You received 10,000 messages form your customers.</td></tr><tr><td>Customer Service Threads</td><td>6</td><td>Text message</td><td>You received 100,000 messages form your customers.</td></tr><tr><td>Customers</td><td>1</td><td>Customer</td><td>You got the first customer registered on your shop!</td></tr><tr><td>Customers</td><td>2</td><td>Customer</td><td>You have over 10 customers registered on your shop.</td></tr><tr><td>Customers</td><td>3</td><td>Customer</td><td>You have over 100 customers registered on your shop.</td></tr><tr><td>Customers</td><td>4</td><td>Customer</td><td>You have over 1,000 customers registered on your shop.</td></tr><tr><td>Customers</td><td>5</td><td>Customer</td><td>You have over 10,000 customers registered on your shop.</td></tr><tr><td>Customers</td><td>6</td><td>Customer</td><td>You have over 100,000 customers registered on your shop.</td></tr><tr><td>Cart Rules</td><td>1</td><td>Discount</td><td>First cart rules configured on your shop.</td></tr><tr><td>Cart Rules</td><td>2</td><td>Discount</td><td>You have 10 cart rules configured on your shop.</td></tr><tr><td>Cart Rules</td><td>3</td><td>Discount</td><td>You have 100 cart rules configured on your shop.</td></tr><tr><td>Cart Rules</td><td>4</td><td>Discount</td><td>You have 500 cart rules configured on your shop.</td></tr><tr><td>Cart Rules</td><td>5</td><td>Discount</td><td>You have 1,000 cart rules configured on your shop.</td></tr><tr><td>Cart Rules</td><td>6</td><td>Discount</td><td>You have 5,000 cart rules configured on your shop.</td></tr><tr><td>International Orders</td><td>1</td><td>Earth globe</td><td>First international order placed on your shop.</td></tr><tr><td>International Orders</td><td>2</td><td>Earth globe</td><td>10 international orders placed on your shop.</td></tr><tr><td>International Orders</td><td>3</td><td>Earth globe</td><td>100 international orders placed on your shop!</td></tr><tr><td>International Orders</td><td>4</td><td>Earth globe</td><td>1,000 international orders placed on your shop!</td></tr><tr><td>International Orders</td><td>5</td><td>Earth globe</td><td>5,000 international orders placed on your shop!</td></tr><tr><td>International Orders</td><td>6</td><td>Earth globe</td><td>10,000 international orders placed on your shop!</td></tr><tr><td>Store</td><td>1</td><td>Store</td><td>First store configured on your shop!</td></tr><tr><td>Store</td><td>2</td><td>Store</td><td>You have 2 stores configured on your shop.</td></tr><tr><td>Store</td><td>3</td><td>Store</td><td>You have 5 stores configured on your shop.</td></tr><tr><td>Store</td><td>4</td><td>Store</td><td>You have 10 stores configured on your shop.</td></tr><tr><td>Store</td><td>5</td><td>Store</td><td>You have 20 stores configured on your shop.</td></tr><tr><td>Store</td><td>6</td><td>Store</td><td>You have 50 stores configured on your shop.</td></tr></tbody></table>

### **International badge block**

#### Filter unit

This block has filtered unit for filtration by Status.&#x20;

**Status filter** has dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) with these options:

* All
* Validated
* Not Validated

By default, filter is selected on All. When other filter option is chosen shows only that status badges.

#### **International badge**

<table><thead><tr><th width="203">Title</th><th width="155">Icon</th><th></th></tr></thead><tbody><tr><td>North America</td><td>Earth globe</td><td>You got your first sale in North America.</td></tr><tr><td>Oceania</td><td>Earth globe</td><td>You got your first sale in Oceania.</td></tr><tr><td>South America</td><td>Earth globe</td><td>You got your first sale in South America.</td></tr><tr><td>Asia</td><td>Earth globe</td><td>You got your first sale in Asia.</td></tr><tr><td>Europe</td><td>Earth globe</td><td>You got your first sale in Europe!</td></tr><tr><td>Africa</td><td>Earth globe</td><td>You got your first sale in Africa.</td></tr><tr><td>Maghreb</td><td>Earth globe</td><td>You got your first sale in Maghreb.</td></tr></tbody></table>

## Multistores behavior

This page is Multistores independent page.
