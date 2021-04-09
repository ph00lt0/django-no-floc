---
title: django-no-floc
---

[![image](https://badge.fury.io/py/django-no-floc.svg)](https://badge.fury.io/py/django-no-floc)

[![image](https://travis-ci.org/ph00lt0/django-no-floc.svg?branch=master)](https://travis-ci.org/ph00lt0/django-no-floc)

[![image](https://codecov.io/gh/ph00lt0/django-no-floc/branch/master/graph/badge.svg)](https://codecov.io/gh/ph00lt0/django-no-floc)

Middleware to opt out of Google\'s FLoC cohort tracking.

# Documentation

The full documentation is at <https://django-no-floc.readthedocs.io>.

# Quickstart

Install django-no-floc:

    pip install django-no-floc

Add it to your \`INSTALLED_APPS\`:

``` {.python}
MIDDLEWARE = (
    ...
    'no_floc.middleware.NoFLoCMiddleware',
    ...
)
```

# Running Tests

Does the code actually work?

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

# Development commands

    pip install -r requirements_dev.txt
    invoke -l

# Credits

Tools used in rendering this package:

-   [Cookiecutter](https://github.com/audreyr/cookiecutter)
-   [cookiecutter-djangopackage](https://github.com/pydanny/cookiecutter-djangopackage)
