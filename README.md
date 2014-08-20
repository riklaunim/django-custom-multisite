django-custom-multisite
=======================

Django==1.4.8 with modified Session and User models

For django apps compatibility during tests it's good to remove migrations folder from auth and sessions and add only non-initial migrations to project application that manages multisite integration.
