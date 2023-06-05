# Alias

## **SPECIFICATIONS - SEARCH PAGE**

### Search

_As a merchant, I want to make sure visitors can find the product they are looking for on my online store._

A table lists all the aliases defined by the merchant. The user can add and edit aliases.

## Add an alias

Clicking 'Add new alias' or on the '+' icon on the top right-hand corner of the table should redirect to a new page, where there are two fields to fill:

**Alias.** \
Users can **associate as many aliases as they want to the same result** as long as they separate them by a comma. \
\
A tooltip is available for the field, `Enter each alias separated by a comma (e.g. 'prestshop,preztashop,prestasohp').` in `Admin.Shopparameters.Help`, followed by `Forbidden characters: <>;=#{}` in `Admin.Shopparameters.Help`.

If the input contains the forbidden characters mentioned in the tooltip (_<>;=#{}_), the user should stay on the page and see an error notification displayed: `%s is not a valid alias.` in `Admin.Shopparameters.Notification`.

If the user saves the alias(es) without filling the _Result_ field, the user should stay on the page and see an error notification displayed: `Aliases and results are both required.` in `Admin.Shopparameters.Notification`. \
\
If everything goes right, he/she should go back to the listing and see a success notification.

**Result.** \
\
Users can **define the searching result matching the previously defined alias(es)**.&#x20;

A search bar is displayed. While typing, it displays all the Results containing the typed string. If the string is not present, a message is displayed in the result list: " "xxxx" does not exist. When saved, it will be added to the new result term."\
\
A tooltip is available for the field, `Search this word instead.` in `Admin.Shopparameters.Help`.

If the input contains forbidden characters (_<>;=#{}_), the user should stay on the page and see an error notification displayed: `%s is not a valid result.` in `Admin.Shopparameters.Notification`.

If the user saves the result without filling the _Alias_ field, he/she should stay on the page and see an error notification displayed: `Aliases and results are both required.` in `Admin.Shopparameters.Notification`. If everything goes right, he/she should go back to the listing and see a success notification.

## Edit an alias

Clicking 'Edit' or anywhere on the table line opens the alias page with the two fields to fill out. Same behavior than already described: when saving, the user goes back to the listing and see a success notification. In the list, the alias should be updated.

\[TO BE COMPLETED]
