# Shop switcher

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Shop switcher dropdown UI</p></figcaption></figure>

Shop switcher is dropdown ([Dropdowns basics UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/dropdowns--basics)) in multistore webshop. It is in center of subheader under main header. \
Once clicked on shop name or arrow next to shop name opens dropdown. In dropdown opened context is marked with check mark icon other are shown with color mark next to name. \
There are following components in dropdown.

## Components description

### Search input

<table><thead><tr><th width="200">Description</th><th>Value</th><th align="center">Error message</th><th data-hidden></th></tr></thead><tbody><tr><td>Mandatory</td><td>NO</td><td align="center">-</td><td>Error message if not allowed</td></tr><tr><td>Allowed/Forbidden values</td><td>                    -</td><td align="center">-</td><td></td></tr><tr><td>Default value</td><td>                    -</td><td align="center">-</td><td></td></tr><tr><td>Help text</td><td>Search shop name</td><td align="center">-</td><td></td></tr><tr><td>Tool tips</td><td>                      -</td><td align="center">-</td><td></td></tr><tr><td>Lower limit</td><td>                      2</td><td align="center">-</td><td>Error message if bellow the limit</td></tr><tr><td>Upper limit</td><td>                      -</td><td align="center">-</td><td>Error message if up to the limit</td></tr><tr><td>Behavior</td><td><a href="shop-switcher.md#behaviors-description">link to the behavior</a></td><td align="center">-</td><td></td></tr></tbody></table>

## Behaviors description

### Search CTA

Search is input field. For search needs to enter shop name to input. When enter second and further symbols, under search input appear matching shops names. Once clicked on shop from list, opens that shop back office.\
If searching takes some time under input is shown notification:\
_Searching for "x"_ here x means entered information.\
If there is no results of symbols in search shows this notification message:\
_No results found for "x"_ here x means entered information.

### All shops

Once clicked switches to all shop context, shows all shops information and changes will be made in all multistore shops. \
When hover mouse pointer on All shops in dropdown, text changes color.

### Shop group

Once clicked shop group name switches to this shop group, shows group shops information and changes will be made in all this group shops. \
When hover mouse pointer on shop group name in dropdown, text changes color. \
The group must be created when user create second shop in Multistore page ([Multishop page](https://docs.prestashop-project.org/1.7-documentation/user-guide/configuring-shop/advanced-parameters/multistore)). First group is named Default but user can enter and change shop group name.

### Shop

Once clicked switches to chosen shop back office, shows this shop information and changes will be made only in this shop. \
When hover mouse pointer on shop name in dropdown, shop name changes color. \
In shop name row is link _View my shop_. When hover mouse pointer on this link it becomes underlined. Once clicked link opens this shop front office.

### Color

All shops, each shop group and shop could have it color ([color picker](color-picker.md)). All shops color by default is blue. Color for shop groups and shops is added in Multistore page ([Multishop page](https://docs.prestashop-project.org/1.7-documentation/user-guide/configuring-shop/advanced-parameters/multistore)). When all shops, shop group or shop is switched, color applied  in subheader under main PrestaShop header.
