.. image:: https://img.shields.io/badge/status-archived-red
   :alt: Status

⚠️ Repository Migration Notice ⚠️
***********************************

.. warning::

   This ``xblock-sql-grader`` repository is being archived. The SQL Grader XBlock
   is moving to the `xblocks-extra <https://github.com/openedx/xblocks-extra>`_ repository,
   which consolidates optional add-on XBlocks for the Open edX platform.

   The migration is being completed through:
   `openedx/xblocks-extra#18 — feat: add SQL Grader XBlock <https://github.com/openedx/xblocks-extra/pull/18>`_

   **Archival:** This repository will become read-only once the migration is complete.
   No further updates or changes will be accepted here.

   Please use `xblocks-extra <https://github.com/openedx/xblocks-extra>`_ for all future work.
   If you have any questions or concerns, please open an issue on the
   `xblocks-extra issue tracker <https://github.com/openedx/xblocks-extra/issues>`_.


SQL Grader XBlock
=================

XBlock to grade SQL statements
via a SQLite engine.

|badge-travis|
|badge-coveralls|

This package provides an XBlock for use with the Open EdX Platform.
Participants can be graded on SQL scripts, written in code editor
supporting:

- syntax highlighting
- autocomplete (with Ctrl+Space)



Installation
------------


System Administrator
~~~~~~~~~~~~~~~~~~~~

To install the XBlock on your platform,
add the following to your `requirements.txt` file:

    git+https://github.com/Stanford-Online/xblock-sql-grader.git@master#egg=sql_grader==0.0.1



Course Staff
~~~~~~~~~~~~

To install the XBlock in your course,
access your `Advanced Module List`:

    Settings -> Advanced Settings -> Advanced Module List

and add the following:

    sql_grader



.. |badge-coveralls| image:: https://coveralls.io/repos/github/Stanford-Online/xblock-sql-grader/badge.svg?branch=master
   :target: https://coveralls.io/github/Stanford-Online/xblock-sql-grader?branch=master
.. |badge-travis| image:: https://travis-ci.org/Stanford-Online/xblock-sql-grader.svg?branch=master
   :target: https://travis-ci.org/Stanford-Online/xblock-sql-grader
