# Webservice's key management rules

## Business rule description

An user can access PrestaShop's Webservice if they are provided an access key. This access key is created through a form alongside its associated permissions.

An access key can be generated through a button on the form but it can also be set manually. If done manually, the access key must follow these rules in creation and edition :&#x20;

* The key must be at least 32 characters long
* The key must not be a duplicate of another key
* Only letters and numbers are valid characters, all other characters are forbidden

Each key has the following attributes which are optional :&#x20;

* A free text description
* A state : Active or Inactive
* A list of permissions allowing to query the Webservice using certain verbs from the HTTP syntax on specific resources

### UX/UI impact of this BR

Both the Webservice page and the creation / edition form are impacted by this BR.

### Behat test link

[Github link](https://github.com/PrestaShop/PrestaShop/blob/develop/tests/Integration/Behaviour/Features/Scenario/Webservice/webservice\_key\_management.feature)
