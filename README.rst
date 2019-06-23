hr
========

CLI for hr project

Preparing for Development
-------------------------

1. Ensure ``pip`` and ``pipenv`` are installed.
2. Clone repository: ``git clone git@github.com:example/pgbackup``
3. ``cd`` into the repository.
4. Fetch development dependencies ``make install``
5. Activate virtualenv: ``pipenv shell``

Usage
-----

Running Tests
-------------

Run tests locally using ``make`` if virtualenv is activate:

::

    $ make

If virtualenv isn't activate then use:

::

    $ pipenv run make
