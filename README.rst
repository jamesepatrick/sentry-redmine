sentry-redmine
==================

An extension for Sentry which integrates with Redmine. Specifically, it allows you to easily create
Redmine issues from events within Sentry.


Install
-------

Install the package via ``pip``::

    pip install git+https://github.com/jamesepatrick/sentry-redmine


More realistically you will want to be installing this in a docker instance, so rather than running ``pip``
you can add ``git+https://github.com/jamesepatrick/sentry-redmine`` to your ``requirements.txt``.


Configuration
-------------

Create a user within your Redmine install (a system agent). This user will
be creating tickets on your behalf via Sentry.

Go to your project's configuration page (Projects -> [Project]) and select the
Redmine tab. Enter the required credentials and click save changes.

You'll now see a new action on groups which allows quick creation of issues.
