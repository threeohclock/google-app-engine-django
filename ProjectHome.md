## Project Deprecated ##
As of Nov 2010, this helper is no longer the recommended way to run Django projects on Google App Engine.

Please see the note at the top of http://code.google.com/appengine/articles/appengine_helper_for_django.html for links to the recommended solutions.

The project continues in maintenance mode only (bugfixes and patch merging only).



---

## Google App Engine Helper for Django ##

This project provides a helper that eases the process of creating a Django project to run on the Google App Engine.

The helper currently provides:
  * The ability to use most manage.py commands
  * A BaseModel class that appears the same as the standard Django Model class.
  * The ability to serialize and deserialize model instances to JSON, YAML and XML.
  * Access to Django's test framework with a test datastore and support for fixtures.
  * The ability to send email via the App Engine mail API using the standard Django mail functions.
  * An App Engine compatible implementation of the Django authentication framework. Only users are supported at this time. Group and Permission support is not implemented.
  * Support for the Django memcache cache backend module.
  * Support for the db and cache session backed modules.

This is an initial release of the helper and we look forward to working with the community to extend the functionality it provides.

For more details and to get started please refer to the
[introductory article](http://code.google.com/appengine/articles/appengine_helper_for_django.html) or the [README](http://code.google.com/p/google-app-engine-django/source/browse/trunk/README).

If you are upgrading from an earlier version of the Google App Engine Helper for Django you may be interested in the list of recent [CHANGES](http://code.google.com/p/google-app-engine-django/source/browse/trunk/CHANGES).


## To Submit Your Patch to the helper ##

To submit a patch to the helper

  1. Locate or Create a bug for the issue you wish to patch
  1. Post the code for the patch in the issue
  1. If the patch is accepted, we'll mark it as such (set the status as Patch-Accepted)
  1. When the version of the helper with your accepted patch is released, we'll mark the issue as Fixed-Patch


## To Submit a Feature or Issue ##

To submit a feature:

  * Check if the feature already exists in the issue tracker
    * If it does, star the issue
      * If you have additional clarification, add that to the comments
    * If the feature does not exist, file a new feature including a description of the desired functionality

To submit a potential issue:

  * Check to see if the issue exists
    * If it does, star the issue
      * If you have additional information on the issue, add that to the bug
    * If the issue does not exist
      * File the issue. Please include as much specific detail as possible when reporting the bug. Include any stack trace that you see, and if appropriate screenshots of the observed behavior