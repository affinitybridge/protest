-- SUMMARY --
A Drupal module to display a modal blackout (ie: website protest).

A splash page will be presented to the visitors of your site with information
about the protest you have chosen to support.

-- REQUIREMENTS --

PHP 5.2

-- INSTALLATION --

* Install as usual, see http://drupal.org/node/70151 for further information.

-- CONFIGURATION --

* Configure user permissions in Administer >> User management >> Permissions
  >> protest module:

  - administer protest

    Users with the "administer protest" permission will have access to the
    protest administration page.

  - bypass protest blackout

    Users with the "bypass protest blackout" permission will not experience the
    modal blackout.

* Configure protest settings in Administer >> Site configuration >> Protest.

-- DEFAULTS --

The default configuration is set to promote the BlackoutSpeakout campaign
(http://www.blackoutspeakout.ca/)
