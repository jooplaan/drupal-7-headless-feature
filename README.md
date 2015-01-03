Headless Drupal feature
==================

Feature to use with the AngularJS-d7client. See:

https://github.com/jooplaan/AngularJS-d7client

Installation
============

Drupal 7:

Use [Drush](https://github.com/drush-ops/drush) to install Drupal and the required modules.

Open Terminal, cd to the directory where you want to host the Drupal instance.

```
$ drush dl drupal
$ cd drupal-7.X
```

Setup your hosting environment for the Drupal to point the preferred webserver document root to the drupal directory. Then run the Drupal installer using your browser. After the installation enable
this feature with Drush:

```
$ cd sites/all/modules
$ git clone git@github.com:jooplaan/drupal-7-headless-feature.git headless_drupal
$ drush en headless_drupal --y
```

Next create some content in the Drupal install:

* a few banner images
* a few articles (used for blog posts)
* a few projects (used for portfolio)
* a 'standard page' for the Contact page


