# Modules

## What do I see?

You're seeing the APIs list contained by your selected application.
Each API can have multiple templates or not.

## What's an API?

An API is such as a content type (ex: `article`, `category`, `comment`).
You can link APIs together with some relations
(ex: an article can have many comments). An API allows you to create, read,
update or delete an entry (ex: an article).

For developers: An API is composed by its own routes, controllers, model,
templates and policies. When you are using the API Builder, it will create a RESTful CRUD API.

## What's a template?

A template is such as a schema of data. Let's take a look at an example: an article has a
`title`, a `subtitle` and a `content`. But sometimes, you need to have another field
for a specific kind of article such as a cover picture.
Instead of creating a global schema that encapsulates every specific kind of schema, Strapi
allows you to create another template of data. Your first template will have
`title`, `subtitle` and `content` fields only. Whereas your second template called
`article-cover` will have `title`, `subtitle`, `content` plus `cover` fields. However,
those templates are still an article content-type and can be accessed with the same API uri.

For developers: A template can be called "a sub API". You can access your data
and create a new entry with the same routes but according to the template the
result or the required data will not be the same.

## Default template notion

The default template notion is very easy to understand. When you create an entry,
you don't have to specify the template parameter. Strapi will choose the default
template automatically. If you only have one template, it's the `default` one.
