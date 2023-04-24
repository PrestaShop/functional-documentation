# Shop association block

<figure><img src="../../../.gitbook/assets/image (57).png" alt="Shop association User Interface"><figcaption><p>Shop association User Interface</p></figcaption></figure>

## Description

The shop association block is displayed when you add or edit something.\
The shop association block displays all groups and all shops.\
Check boxes ([Forms stylised checkboxes UI kit](https://build.prestashop-project.org/prestashop-ui-kit/?path=/story/forms--stylised-checkboxes)) allow to select / unselect groups and shops.\
It's possible to expand / collapse the wall tree and expand / collapse each group\
If you select / unselect a group, all shops of this group are selected / unselected

The shop association block allows to choose for which store(s) you want to associate or disassociate the current element.

When you add something, the shop(s) selected in the context are automatically checked in the shop association block.\
But it's possible to select / unselect shops, no matter the context selected.

When you edit something, you can unselect shop(s) previously selected and therefore disassociate it from these shops.\
And you can also, select shop(s) not previously selected and therefore associate it with these shops.\
If the merchant unselect all the check boxes (all the shops), then an error message in red is displayed below the shop association block to inform of the obligation to have at least one shop checked: "You have to select at least one shop to associate this item with" + the save button is disabled.
