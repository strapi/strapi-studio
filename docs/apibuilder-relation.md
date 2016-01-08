# API relations

## What do I see?

You are seeing the relations page of the API Builder. You can add, edit or
remove relations between your APIs.

## What is a relation?

A relation is such as a join/link between two APIs. For example, if
you have a `Article` API and a `Comment` API, your article can have many
comments. So, you need to link your API `Article` with your API `Comment`.
We called this a "relation".

## How to fill out the fields?

### Relations

@@ This is the list of your relations for your API.

This is the list of your relations for your API. For example, if you add a
`comments` key, this will create a new relation with the selected API in the
settings part.

For developers: The name of your relation will be a new key in your model's
API, and the relation key will be a new key in the other model's API.

### Settings

#### Type

@@ Please read the sentence beside

There are different kind of relations. Take time to read the sentence beside
this input..

#### API

@@ Select the API which must be linked with your current API

This input targets the API which must be linked.

#### Relation key

@@ This input value will be the name of the key created in the API selected above.

This input value will be the name of the key created in the API selected above.
