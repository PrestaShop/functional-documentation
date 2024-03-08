# Categories

Below the form group of the **Friendly URL**, there is the form group **Redirection when not displayed**.\
\
The form group is composed of the label **"Redirection when not displayed"** and a dropdown with 4 options:

* Permanent redirection to a category (301)
* Temporary redirection to a category (302)
* No redirection (404)
* No redirection (410)

if it is the default category, only list:

* No redirection (404)
* No redirection (410)

The default value is “Permanent redirection to a category (301)” with default category select ("Home") and for default category edition, the value is "- No redirection (410)"

When “Permanent redirection to a category (301)” or “Temporary redirection to a category (302)” is selected \
Then **Target category** field is displayed. \
\
This search field is displayed if you select in the dropdown Permanent redirection to a category or Temporary redirection to a category.

There is a placeholder: `“To which category the page should redirect ?”`

If no category is selected, the Home Category is used.

You can search by category name. When you start typing, if there are results, they are displayed under and you can click on it. Then, the selected category is displayed under the field.

Information message is displayed below the droplist:

```
"Permanent redirection (301) = Permanently display another category instead.

Temporary redirection (302) = Temporarily display another  category instead.

No redirection (404), display error page = Do not redirect anywhere and display a 404 "Not Found" page.

No redirection (410), display error page = Do not redirect anywhere and display a 410 "Gone" page."
```
