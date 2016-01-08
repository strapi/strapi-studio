# Dashboard

Welcome on Strapi. Our ecosystem will help you to build powerful back-end
application with no effort.

Feel free to [contact us](http://strapi.io/support) for support.

## What do I see ?

You're seeing your apps list.

- Connected applications are represented by a green circle.
- Not connected applications are represented with grayscale filter.

## Getting started

Let's go!

Install Strapi and create your first application following those
[instructions](http://strapi.io/documentation/introduction).

Now, you need to generate a secret key to connect your application with the Studio.
Follow [those steps](http://dashboard.strapi.io/#!/settings/security) and
set your secret key in your application.

## Delete application

When you delete your application from the dashboard page,
this will not delete your local directory but only the link between your
application and the Studio.

To reconnect your application, you need to generate another secret key.

## Selected application

To select an application, please use the select input in the top bar.
This action will update the Studio with the selected application data.

## Synchronize your applications

To synchronize your application in realtime with the Studio, click on the `sync`
button. This action will pull necessary data only. Your data are fully encrypted
with 2048 bits RSA key. This key is (re-)generated every time you start your
application.

## Connected application

To be able to use the Studio, your application has to be started, else your data
can't be pull from your local directory.
