.. image:: https://img.shields.io/badge/status-deprecated-red
   :alt: Status

.. warning::

   **This Repository is Deprecated**

   This repository is no longer maintained.

   The SQL Grader XBlock has been moved to:
   https://github.com/openedx/xblocks-extra

   Please use the new repository for all future work.


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
