# Theme customization (ps\_themecusto)

## Description

Theme customization page allows changing the look of the store. This page consists of three tabs: homepage, category page and product page. Each tab configures its page in front office.

<figure><img src="../../../../../../.gitbook/assets/image (13).png" alt="Pages configuration User Interface"><figcaption><p>Pages configuration User Interface</p></figcaption></figure>

## QA&#x20;

[Link to the test](https://build.prestashop-project.org/test-scenarios/scenarios/core/functional/bo/design/theme-logo/page-configuration.html)

## Common components

* [Breadcrumbs navigation](../../../../common-components/breadcrumbs.md) - [Breadcrumb UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/breadcrumb--breadcrumb).
* [Heading of the page](../../../../common-components/heading-of-the-page.md) - [Headings UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/headings--headings).
* [Help button](../../../../common-components/help-button.md) - [Buttons outline UI Kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline).
* [E-commerce logo](../../../../common-components/back-office-header/prestashop-logo.md)&#x20;
* [PrestaShop version number](../../../../common-components/prestashop-version-number.md)&#x20;
* [Quick access dropdown](../../../../common-components/back-office-header/quick-access-dropdown.md)&#x20;
* [Search input](../../../../common-components/search-input-field.md)
* [Shop switcher with eye icon](../../../../common-components/shop-switcher-with-eye-icon.md)
* Bell icon (todo link)
* [Account icon](../../../../common-components/account-icon.md)&#x20;

## Pages configuration Homepage tab

### Interactive banner

Interactive banner has hover function and it shows which page part is customized. This banner helps to customers to understand which part can be edited. There are the following banner parts:

* **Menu**
* **Slider**
* **Home products**
* **Text block**
* **Banner**
* **Social & newsletter**
* **Footer**

### Menu

There are following elements:

* **Categories** - has description and it is: \
  _Create here a full range of categories and subcategories to classify your products and manage your catalog easily._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Categories page.
* **Content pages** - has description and it is: \
  _Add and manage your content pages to make your store interesting and trustworthy._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Design > Pages.
* **Brands and suppliers** - has description and it is: \
  _Manage both your brands and suppliers at the same place!_\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Brands & Suppliers > Brands page.
* **Main menu** - has description and it is: \
  _Make it easy for your visitors to find their way on your store, select the right link and turn it into a menu item._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Main menu module page. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.

### Slider

**Image slider** - has description and it is: \
_Add sliding images to your homepage to welcome your visitors in a visual and friendly way._\
Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Image slider module page. There are dropdown options:&#x20;

* **Uninstall** - uninstalls the module.
* **Disable** - disables the module.
* **Enable mobile** - enables the module on mobile devices.
* **Reset** - resets the module.

### Home products

There are following elements:

* **Featured products** - has description and it is: \
  _Pick a category and highlight its items, enhance customer experience with a lively homepage._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Featured products module page. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **New products block** - has description and it is: \
  _Displays a block featuring your store's newest products._\
  Also this component has CTA button **Install** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). Once clicked **Install** button spinner will come out ([Spinner UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/spinner--spinner)) In few seconds appears CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens New products block module. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Top-sellers block** - has description and it is: \
  _Adds a block displaying your store's top-selling products._\
  Also this component has CTA button **Install** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)).Once clicked **Install** button spinner will come out ([Spinner UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/spinner--spinner)) In few seconds appears CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Top-sellers block module. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Specials block** - has description and it is: \
  _Provides information on special offers in a specific block._\
  Also this component has CTA button **Install** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). Once clicked **Install** button spinner will come out ([Spinner UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/spinner--spinner)) In few seconds appears CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Specials block module. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.

### Text block

**Custom text block** - has description and it is: \
_Give your visitors extra information, display a customized block of content on your homepage._ \
Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Custom text block module page. There are dropdown options:&#x20;

* **Uninstall** - uninstalls the module.
* **Disable** - disables the module.
* **Disable mobile** - disables the module on mobile devices.
* **Reset** - resets the module.

### Banner

**Banner** - has description and it is: \
_Add a banner to the homepage of your store to highlight your sales and new products in a visual and friendly way._\
Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Banner module page. There are dropdown options:&#x20;

* **Uninstall** - uninstalls the module.
* **Disable** - disables the module.
* **Enable mobile** - enables the module on mobile devices.
* **Reset** - resets the module.

### Social & newsletter

There are following elements:

* **Newsletter subscription** - has description and it is: \
  _Keep in touch with your customers the way you want, add a form to the homepage of your store and allow all the curious to subscribe to your newsletter._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Custom text block module page. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
*   **Social media follow links** - has description and it is: \
    _Facebook, Twitter, let your customers know where to follow you and increase your community._

    Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Social media follow links module page. There are dropdown options:&#x20;

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.

### Footer

There are following elements:

* **Customer Reassurance** - has description and it is: \
  _Connect with your visitors and reassure them about secure payment, free shipping or returns._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Customer reassurance module page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Link list** - has description and it is: \
  _Give more visibility to your content/static pages (CMS, external pages, or else), where you want and when you want, to make your visitors feel like shopping on your store._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Design > Link list page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Shop details** - has description and it is: \
  _Display additional information about your store or how to contact you to make it easy for your customers to reach you._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Stores page.

### See all themes module's button button

This CTA button ([Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics)) opens Modules page that contains all modules.

## Pages configuration Category page tab

### Interactive banner

Interactive banner has hover function and it shows which page part is customized. This banner helps to customers to understand which part can be edited. There are the following banner parts:

* **Menu**
* **Categories**
* **Navigation column**
* **Content**
* **Social & newsletter**
* **Footer**

### Menu

There are following elements:

* **Content pages** - has description and it is: \
  _Add and manage your content pages to make your store interesting and trustworthy._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Design > Pages.
* &#x20;**Brands and suppliers** - has description and it is: \
  _Manage both your brands and suppliers at the same place !_\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Brands & Suppliers > Brands page.
*   **Main menu** - has description and it is: \
    _Make it easy for your visitors to find their way on your store, select the right link and turn it into a menu item._

    Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Main manu module page. There are dropdown options:

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.

### Categories

**Categories** - has description and it is: \
_Create a full range of Categories and Subcategories to classify your products, add categoryies desciptions and manage your catalog easily._\
Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Catalog > Categories page.

### Navigation column

There are following elements:

*   **Category tree links** - has description and it is: \
    _Help navigation on your store, show your visitors current category and subcategories._

    Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Category tree links module page. There are dropdown options:

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.
*   **Faceted search** - has description and it is:\
    _Filter your catalog to help visitors picture the category tree and browse your store easily._

    Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Faceted search module page. There are dropdown options:

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.

### Content

There is **Pagination** in Content part. **Pagination** - has description and it is: \
_Set the numbers of products you want to display per page and how._\
Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Shop parameters > Product settings page.

### Social & newsletter

There are following elements:

* **Newsletter subscription** - has description and it is: \
  _Keep in touch with your customers the way you want, add a form to the homepage of your store and allow all the curious to subscribe to your newsletter._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Newsletter subscription module page. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
*   **Social media follow links** - has description and it is: \
    _Facebook, Twitter, let your customers know where to follow you and increase your community._

    Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Social media follow links module page. There are dropdown options:&#x20;

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.

### Footer

There are following elements:

* **Customer Reassurance** - has description and it is: \
  _Connect with your visitors and reassure them about secure payment, free shipping or returns._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Customer reassurance module page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Link list** - has description and it is: \
  _Give more visibility to your content/static pages (CMS, external pages, or else), where you want and when you want, to make your visitors feel like shopping on your store._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Design > Link list page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Shop details** - has description and it is: \
  _Display additional information about your store or how to contact you to make it easy for your customers to reach you._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Stores page.

### See all themes module's button button

This CTA button ([Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics)) opens Modules page that contains all modules.

## Pages configuration Product page tab

### Interactive banner

Interactive banner has hover function and it shows which page part is customized. This banner helps to customers to understand which part can be edited. There are the following banner parts:

* **Menu**
* **Product management**
* **Product detail**
* **Product block**
* **Social & newsletter**
* **Footer**

### Menu

There are following elements:

* **Categories** - has description and it is: \
  _Create here a full range of categories and subcategories to classify your products and manage your catalog easily._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Catalog > Categories.
* &#x20;**Content pages** - has description and it is: \
  _Add and manage your content pages to make your store interesting and trustworthy._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Design > Pages.
* **Brands and suppliers** - has description and it is: \
  _Manage both your brands and suppliers at the same place !_\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Brands & Suppliers > Brands page.
*   **Main menu** - has description and it is: \
    _Make it easy for your visitors to find their way on your store, select the right link and turn it into a menu item._

    Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Main manu module page. There are dropdown options:

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.

### Product management

There are following elements:

*   **Catalog** - has description and it is: \
    _Access your list of products to manage your catalog efficiently._

    Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Catalog > Products page.
* **Stock** - has description and it is:\
  _Manage your stock and edit product quantities right here._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Catalog > Stock management > Stock page.
* **Product attributes** - has description and it is:\
  _Create or manage your attributes : colors, sizes, materials, ..._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Attributes page.

### Product detail

There are following elements:

* **Customer Reassurance** - has description and it is: \
  _Connect with your visitors and reassure them about secure payment, free shipping or returns._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Customer reassurance module page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Social media share buttons** - has description and it is: \
  I_nstagram, YouTube, gather your community with social media sharing buttons on product pages._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Social media share buttons module page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
* **Product comments** - has description and it is:\
  _Allow users to post reviews on your products and/or rate them based on specific criteria._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Product comments module page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.

### Product block

There are following elements:

* **Cross-selling** - has description and it is: \
  _Offer your customers the possibility to buy matching items when on a product page._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Cross-selling module page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
*   **Products in the same category** - has description and it is: \
    _Adds a block on the product page that displays products from the same category._

    Also this component has CTA button **Install** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). Once clicked **Install** button spinner will come out ([Spinner UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/spinner--spinner)) In few seconds appears CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Products in the same category module page. There are dropdown options:&#x20;

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.
*   **Viewed products block** - has description and it is:\
    _Display a kind of showcase on your product pages with recently viewed products._

    Also this component has CTA button **Install** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). Once clicked **Install** button spinner will come out ([Spinner UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/spinner--spinner)) In few seconds appears CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Viewed products block module page. There are dropdown options:&#x20;

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.

### Social & newsletter

There are following elements:

* **Newsletter subscription** - has description and it is: \
  _Keep in touch with your customers the way you want, add a form to the homepage of your store and allow all the curious to subscribe to your newsletter._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Newsletter subscription module page. There are dropdown options:&#x20;
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.
*   **Social media follow links** - has description and it is: \
    _Facebook, Twitter, let your customers know where to follow you and increase your community._

    Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Social media follow links module page. There are dropdown options:&#x20;

    * **Uninstall** - uninstalls the module.
    * **Disable** - disables the module.
    * **Disable mobile** - disables the module on mobile devices.
    * **Reset** - resets the module.

### Footer

There are following elements:

* **Shop details** - has description and it is: \
  _Display additional information about your store or how to contact you to make it easy for your customers to reach you._\
  Also this component has CTA button **Configure** ([Buttons outline UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--outline)). It opens Stores page.
* **Link list** - has description and it is: \
  _Give more visibility to your content/static pages (CMS, external pages, or else), where you want and when you want, to make your visitors feel like shopping on your store._\
  Also this component has CTA button **Configure with dropdown menu** ([Dropdowns with button split UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/dropdowns--with-button-split)). **Configure** button opens Design > Link list page. There are dropdown options:
  * **Uninstall** - uninstalls the module.
  * **Disable** - disables the module.
  * **Disable mobile** - disables the module on mobile devices.
  * **Reset** - resets the module.

### See all themes module's button

This CTA button ([Buttons basics UI kit](https://build.prestashop.com/prestashop-ui-kit/?path=/story/buttons--basics)) opens Modules page that contains all modules.

### **Multistores behavior**

This page is [Multistores dependent](../../../../common-components/multistores-dependent.md) page.

