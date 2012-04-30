DJ-Database-URL
~~~~~~~~~~~~~~

This simple Django utility allows you to utilize the
`12factor <http://www.12factor.net/backing-services>`_ inspired
``DATABASE_URL`` environment variable in your Django application.

Usage
-----

Configure your database in ``settings.py``:

    DATABASES = dj_database_url.config(DATABASES)

Nice and simple.

Installation
------------

Installation is simple::

    $ pip install dj-database-url