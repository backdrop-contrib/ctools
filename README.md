Ctools
======

Most tools in the Chaos Tools Suite have nearly equivalent features that have
been included in Backdrop core since version 1.0.0.

There is no reason to install this module, hooray!

Mapping of ctools to Backdrop core features:

* Plugins -- tools to make it easy for modules to let other modules implement
  plugins from .inc files. **Backdrop uses info hooks and callback functions (or
  callback classes) instead of plugins.** See [wiki for more help in converting CTools plugin](https://github.com/backdrop-contrib/ctools/wiki/Converting-CTools-plugins).

* Exportables -- tools to make it easier for modules to have objects that live
  in database or live in code, such as 'default views'. **All configuration is
  exportable in Backdrop thanks to Configuration Management** To build a listing
  of your exportables, you might consider using [Preset API.](https://github.com/backdrop-contrib/preset).

* AJAX responder -- tools to make it easier for the server to handle AJAX
  requests and tell the client what to do with them. **Improvements to the core
  AJAX system make these tools less necessary**

* Form tools -- tools to make it easier for forms to deal with AJAX.
  **Improvements to the core AJAX system make these tools less necessary**

* Object caching -- tool to make it easier to edit an object across multiple
  page requests and cache the editing work. **Object caching has been added to
  core in Backdrop CMS**

* Contexts -- the notion of wrapping objects in a unified wrapper and providing
  an API to create and accept these contexts as input. **Contexts have been
  added to core in Backdrop CMS**

* Modal dialog -- tool to make it simple to put a form in a modal dialog.
  **Improvements to the core modal dialog system make these tools less
  necessary**

* Dependent -- a simple form widget to make form items appear and disappear
  based upon the selections in another item. **Improvements to the core states
  system make these tools less necessary**

* Content -- pluggable content types used as panes in Panels and other modules
  like Dashboard. **Improvements to the core block system make these tools less
  necessary**

* Form wizard -- an API to make multi-step forms much easier. **This now exists as the backdrop-contrib/form_wizard for Backdrop.**

* CSS tools -- tools to cache and sanitize CSS easily to make user-input CSS
  safe. **todo, if necessary**


Credits
-------

- Written & maintained for Drupal by Earl Miles (https://github.com/merlinofchaos).
- Maintained for Drupal by Daniel Wehner (https://www.drupal.org/u/dawehner).
- Maintained for Drupal by James Gilliland (https://www.drupal.org/u/neclimdul).
- Maintained for Drupal by Jakob Perry (https://www.drupal.org/u/japerry).
- Maintained for Drupal by Tim Plunkett (https://www.drupal.org/u/tim.plunkett).
- Maintained for Drupal by Kris Vanderwater (https://www.drupal.org/u/eclipsegc).
- Ported to Backdrop CMS by Nathan Haug (https://github.com/quicksketch).
