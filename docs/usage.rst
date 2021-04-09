=====
Usage
=====

To use django-no-floc in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'no_floc.apps.NoFlocConfig',
        ...
    )

Add django-no-floc's URL patterns:

.. code-block:: python

    from no_floc import urls as no_floc_urls


    urlpatterns = [
        ...
        url(r'^', include(no_floc_urls)),
        ...
    ]
