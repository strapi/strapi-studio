# Databases

## What do I see ?

You're seeing the DataBases list linked with your application.
Strapi offers you the possibility to connect to multiple DataBases.

## Remove DataBase

To remove a DataBase from your application, click on the `delete` button.
If some APIs or models are linked with the DataBase you want to remove,
Strapi will offer you the choice to link this API with one of the
other DataBases linked with your application.

Warning: Strapi doesn't delete your data, it just breaks the link between
your DataBase and your application.

## Install new DataBase

To install a new DataBase, you've to fill out the required fields. Strapi
pre-configures some fields to respect guidelines and allowed ports for DataBases,
but you can override those fields.

### How to fill out the fields?

#### Adapter

@@ Kind of DataBase. Strapi offers the opportunity to connect your application to
a lot of DataBase Management Systems.

This is your kind of DataBase. Strapi offers the opportunity to connect your
application to a lot of DataBase Management Systems. 

This feature is available thanks to a powerful ORM called Waterline.

#### Connection identifier

@@ Unique name of your connection, not the name of your DataBase (ex: myMongoServer).

This identifier is the unique name of your connection, not the name of your DataBase.

#### Host

@@ IP address of your DataBase.

This is the IP address of your DataBase.

#### Port

@@ DataBase's port allowed to accept connection.

This is the DataBase's port allowed to accept connection.
