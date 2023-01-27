# Description

This python-flask application is a simple food placement application with features such as login food menu and item cart.
The food menu is directly fetched from the SQL database that have the total number of food item and their respective 
prices, the cart functions allows you to add the respective amount of the item and the total cost of the order is calculated using respective queries and is shown in the cart page with the item list and total rice

Their is also a signup/login page to give a proper feeling of using a personalized food placement application.

# Screenshots


![Screenshot from 2023-01-27 21-53-13](https://user-images.githubusercontent.com/84196130/215138770-e9e96d02-7988-4be0-99ad-0b005d929cbd.png)

![Screenshot from 2023-01-27 21-53-23](https://user-images.githubusercontent.com/84196130/215138815-02b2c4d2-521a-4614-a8d9-964eaccb1f31.png)




Translations
============

WTForms uses gettext to provide translations. Translations for various
strings rendered by WTForms are created and updated by the community. If
you notice that your locale is missing, or find a translation error,
please submit a fix.


Create
------

To create a translation, initialize a catalog in the new locale:

```
$ python setup.py init_catalog --locale <your locale>
```

This will create some folders under the locale name and copy the
template.

Edit
----

After creating a translation, or to edit an existing translation, open
the ``.po`` file. While they can be edited by hand, there are also tools
that make working with gettext files easier.

Make sure the `.po` file:

- Is a valid UTF-8 text file.
- Has the header filled out appropriately.
- Translates all messages.


Verify
------

After working on the catalog, verify that it compiles and produces the
correct translations.

```
$ python setup.py compile_catalog
```

Try loading your translations into some sample code to verify they look
correct.


Submit
------

To submit your translation, create a pull request on GitHub.
