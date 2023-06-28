# Logs

## Description

In this page, all of the logs from the shop are displayed, from modules as well, all the logs have information about the employee when the log was registered, and other information.

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2022-09-12 at 17-43-00 Logs • Faire178.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2022-09-12 at 17-44-50 Logs • Faire178.png" alt=""><figcaption></figcaption></figure>

## Components descriptions

### Severity levels

In this section the meaning of the logs is shown. 4 levels are presented

Meaning of severity levels:

* Informative only, green colored
* Warning - colored yellow
* Error
* Major issue (crash!)

## Components behavior

### Settings wheel

This is a standard component&#x20;

Except it add  "**Erase all"** item in the list : CTA erase all &#x20;

When clicking on the Erase all, a modal asks if you are sure to delete it, after clicking "OK" deletes all the logs, if pressed "Cancel", closes the modal.

#### Logs sorting

The logs sorting rule can be found [here](https://app.gitbook.com/o/-MAz0PPl5s9ulE9xyliu/s/eRh5ljXXvELkmmdiRmg8/\~/changes/LBfyCScRUjOVa2zoG5Ub/functional-documentation/ux-ui/common-components/sorting-rule).

#### Call to action

* Save, when pressed shows the following message: "Successful update." If the "Send emails to" field is input incorrectly, when saving will show: "Invalid email:" [(read here)](./#logs-by-email).



### Logs

<figure><img src="../../../../../../.gitbook/assets/Screenshot 2022-09-13 at 15-41-03 Logs • test.png" alt=""><figcaption></figcaption></figure>

11 Rows are displayed in this section:

#### Search options:

* ID: When searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
* Employee: When searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
* Severity: Searching allows only the following selection from the drop-down: "Informative only, warning, error, major issue(crash)".
* Message: When searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
* Object type: When searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
* Object ID: When searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
* Error code: When searching, there are no limitations or allowed/forbidden values, pressing "Search" will list the needed selections, if there are none found will just show: "No records found".
* Date: 2 date fields are present, when pressed can select specific date by year/month/day from-to, and then search, if no records found will show: "No records found".



#### Sorting options:

* ID: Can be sorted by asc or desc.
* Employee: Can be sorted by asc or desc.
* Severity: Can be sorted by asc or desc.
* Message: Can be sorted by asc or desc.
* Object type: Can be sorted by asc or desc.
* Object ID: Can be sorted by asc or desc.
* Shop context: Can be sorted by asc or desc.
* Language: Can be sorted by asc or desc.
* Error code: Can be sorted by asc or desc.
* Date: Can be sorted by asc or desc.

Only "search" button is available, when any of the previous search fields are entered, it's possible to search, when the search is done, a button below: "reset" appears, when pressed it clears the search, and restores the previous view of all the logs.

At the bottom of this section, if there are more than 1 page of logs, all the possible pages will be shown that can be scrolled, there will be shown: " Viewing 1-10 out of 502 (page 1 / 51)"

Also, "Items per page:" in this drop-down field it's possible to select the display for: 10, 20, 50, 100.



## Logs by email

In this section 2 fields are present:



#### Minimum severity level

This is a drop-down field, has a help text below "Click on "None" to disable log alerts by email or enter the recipients of these emails in the following field." the drop-down field has the possible options:

* Major issue (crash)! (default option)
* Error
* Warning
* Informative only
* None

#### Send emails to

| Description              | Value                                                                                                                           | Error message                |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| Mandatory                | Yes                                                                                                                             | "Please fill out this field" |
| Allowed/Forbidden values | valid email address                                                                                                             | "Invalid email:"             |
| Default value            | 5                                                                                                                               |                              |
| Help text                | "Log alerts will be sent to these emails. Please use a comma to separate them (e.g. pub@prestashop.com, anonymous@psgdpr.com)." |                              |
| Tool tips                | -                                                                                                                               |                              |
| Lower limit              | -                                                                                                                               |                              |
| Upper limit              | -                                                                                                                               |                              |
| Behavior                 | "Successful update." after saving                                                                                               |                              |

####

