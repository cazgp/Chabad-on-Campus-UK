
Conditional Fields:
--------------------
A Drupal module


Author:
--------------------
Gregorio Magini (peterpoe) <gmagini@gmail.com> - http://www.twitter.com/peterpoe/
Initially inspired by the Explainfield module -> http://drupal.org/project/explainfield/


Short Description:
--------------------
Define dependencies between fields based on their states and values. Conditional Fields for Drupal 7 is basically an user interface for the States API, plus the ability to hide fields on certain conditions when viewing content.


Description:
--------------------
Conditional Fields allows you to manage sets of dependencies between fields. When a field is “dependent”, it will only be available for editing and displayed if the state of the “dependee” field matches the right condition.
When editing a node (or any other entity type that supports fields, like users, terms and files), the dependent fields are dynamically modified with the States API. 
You can, for example, define a custom “Article teaser" field that is shown only if a "Has teaser" checkbox is checked.


Dependencies:
--------------------
- Drupal core: 7.x or 6.x
- (Only with Drupal 6) CCK  > http://drupal.org/project/cck/
- (Optional, only with Drupal 6) Fieldgroups (included in CCK) > If enabled you can also set groups as controlled fields


Installation:
--------------------
- Copy the unpacked folder "conditional_fields" in your modules folder (usually [base_path]/sites/all/module).
- Go to the modules administration page (admin/build/modules) and activate the module.
- Assign the "Administer conditional fields" permission to the desired user roles.


Usage:
--------------------
Users with the “administer site configuration” permission can administer dependencies at admin/structure/dependencies.

For more information, read the Conditional Fields handbook:
http://drupal.org/node/475488


Limitations:
--------------------
- Conditional Fields, for now, supports only core fields and widgets as dependee fields. Fields from other modules might work, but probably won't. 


To Do:
--------------------
Any help is welcome!
--------------------
Check the issue queue of this module for more information:
http://drupal.org/project/issues/conditional_fields

These are the top priority future features:
- Polish and bugfix!
- Extend compatibility with non-core CCK modules
- Views integration
- Field group integration
