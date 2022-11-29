# Translations

At the top of the page the statistics are displayed for:

"Enabled languages" (when pressed on, redirects to the localization -> languages), "Main country" and '"Front office translations".

The statistics can be refreshed with a button on the top right of the block.

#### Recommended&#x20;



This page consists of 4 different sections:

1.  #### Modify translations


2.  #### Add / Update a language


3.  #### Export a language


4.  #### Copy

    ![](<../../../../../../.gitbook/assets/image (4).png>)

### Components description

**Modify translations**

**Has a tool tip - "Here you can modify translations for every line of text inside Prestashop. First, select a type of translation (such as "Back office" or "Installed modules"), and then select the language you want to translate strings in."**

In this section the 2 drop-down input fields are shown:

* Type of translation (drop-down list with the following options below)
  * Back office translations
  * Front office translations
  * Installed modules translations
  * Email translations
  * Other translations
*   Select your language (drop-down list with the following options below)

    * Language
    * \*Any other language installed on the shop will be listed as well in the drop-down\*.



**Modify - call to action button is at the bottom of this section.**

#### Add / Update a language

**Has a tool tip - "You can add or update a language directly from the Prestashop website here".**

In this section 1 drop-down selection is shown:

* Please select the language you want to add or update - in the drop-down firstly the languages already installed are sectioned in a "Update a language" section. Below that all the languages are listed that can be added in a section called "Add a language".

**Add or update a language - call to action button is at the bottom of this section.**

#### Export language

**Has a tool tip - "Export data from one language to a file (language pack). Select which theme you would like to export your translations to."**

In this section 2 fields with sub fields are present:

* Language - this is a drop-down selection list which when pressed displays all the installed languages on the shop.
* Export - this selection has sub selections below:
  * Back office
  * Front office
  * Email
  * Other
* Theme translations - this is a drop-down selection list:
  * Displays all the themes installed on the shop
* Installed module translations - this is a drop-down selection list:
  * Lists all the installed modules on the shop

**Export - call to action button is at the bottom of this section.**

#### Copy

Alert box is present in this section stating:

"Copies data from one language to another.\
Warning: This will replace all of the existing data inside the destination language.\
If necessary [_launch_ you must first create a new language](https://efafda2a9c8c.eu.ngrok.io/PS1784/admin492oe0k3i/index.php/improve/international/languages/new?\_token=xcb8PZr0zrxBs\_6rEyg9o9RHGOdbk6Oa5x-kY7zjn9s)."

This section provide with 4 drop-down fields in total.&#x20;

* From&#x20;

2 drop-downs are present one next to other, 1 for the languages installed for the shop, the other for the type of the language

* To

2 drop-downs are present one next to other, 1 for the languages installed for the shop, the other for the type of the language

**Copy - call to action button is at the bottom of this section.**

### Behavior description

#### Modify translations

Modify - call to action

If no language is selected, shows a message by the "select your language field": "Please select an item in the list".

#### Add / Update a language

Add or update a language - call to action

When pressed, a success message is shown: "The translations have been successfully added."

#### Export a language

Export - call to action

This call to action button is only allowed when language is selected, and what will be exported.

#### Copy

Help message in this section is provided:

"Copies data from one language to another.\
Warning: This will replace all of the existing data inside the destination language.\
If necessary [_launch_ you must first create a new language](https://150cb880d96f.eu.ngrok.io/PS1784/admin492oe0k3i/index.php/improve/international/languages/new?\_token=M9i8cabfv3WKQbJ6F0\_LxvtIqowjWHRSF85KePaYC44)."

Copy - call to action

Works when different "from" and "to" is selected.

### Error messages

#### Copy

"There is nothing to copy (same language and theme)."

"Impossible to copy "/path/"."
