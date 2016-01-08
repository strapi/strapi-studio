# Template definition

## What do I see?

You are seeing the template page of the API Builder.
You can add, edit or remove fields from this template of data.

## What is a template?

A template is such as a schema of data. Let's take an example: an `article` has a
`title`, a `subtitle` and a `content`. But sometimes, you need to have another
field for a specific kind of article such as a cover picture.

Instead of create a global schema that encapsulates each need of data,
Strapi allows you to create another template of data. Your first template will
have `title`, `subtitle` and `content` fields only. However, your second template
called `article-cover` will have `title`, `subtitle`, `content` plus `cover`
fields. Both templates are still an article and can be access with the same API uri.

For developers: A template can be called a "sub API". You can access your data
and create an new entry with the same routes but according of the template the
result or the required data will not be the same.

## How to fill out the fields?

### Template name

@@ Enter the name of your template. See the documentation to get more information
about a template.

This field is the name of your template. For example, if you are creating a new
template for your API `Article`, with a specific field cover you can called
it `Cover`.

### Attributes

@@ This field's list is the schema of data of your template.

This field's list is the schema of data of your template. There are no limit number.

Warning: Sometimes, you have some common fields between your templates.
If you change the type of a field, this changes will be repercuted to the
other templates too.

### Validations

@@ The validations are rules which have to be respected to create a new entry in the database

For a specific field, you can add some validations (also called rules).

*More validations will come soon...*

#### Default Display Attribute

@@ The default display attribute is the attribute displayed in the administration of
your application. See the documentation to get more information about the default display attribute.

In order to enjoy our powerful admin dashboard, it needs indicators to
work well. The "default display attribute" is one of them. This option will
display this field value in priority in our admin. For example, if you
checked the `title` field for your API `article`, the admin dashboard
will display the `title` in the list of articles.

If there are no "default display attribute" checked, we choose the primary as
default attribute to display.
