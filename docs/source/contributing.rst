Contributing
============

Prerequisites
-------------

If you are not already familiar with Poetry_, this is a poetry project, so you'll need this!

Getting Setup
-------------
Note, while the project itself provisionally runs on Python 3.8, test dependencies
including pytest-mock-resources, coverage, and black, have minimum python versions of 3.9.
So local development of pytest-alembic itself requires. Additionally this means
we dont test 3.8 support, so supporting it is best effort until it becomes inconvenient.

See the :code:`Makefile` for common commands, but for some basic setup:

.. code-block:: bash

    # Installs the package with all the extras
    make install

And you'll want to make sure you can run the tests and linters successfully:

.. code-block:: bash

    # Runs CI-level tests, with coverage reports
    make test lint


Need help
---------

Submit an issue!

.. _Poetry: https://poetry.eustace.io/
