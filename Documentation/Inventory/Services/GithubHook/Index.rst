
.. include:: ../../../Includes.txt

==================================================
Github Hook Processing
==================================================

Rendered: |today|

**Jump up and down on this page:**

.. contents::
   :local:

.. _github-hook:

Github Hook
===========

::

   Installed at:
      BASE=/home/mbless/public_html/services

   which is a symlink to:
      /home/mbless/HTDOCS/github.com/marble/typo3-docs-typo3-org-resources.git/webroot/services

   Cannot be viewed via the following line because of an .htaccess file:
      http://docs.typo3.org/~mbless/HTDOCS/github.com/marble/typo3-docs-typo3-org-resources.git/webroot/services/

   Script
      SCRIPT=$BASE/handle_github_post_receive_hook.php

   The script reads:
      $BASE/known-github-manuals.txt

   The script logs to:
      $BASE/temp.txt

   A former logfile 'temp.txt' was renamed to and archived as:
      $BASE/log-of-notifications.archive.001.txt

..
View:

- `$BASE/known-github-manuals.txt <http://docs.typo3.org/services/known-github-manuals.txt>`__
- `$BASE/temp.txt <http://docs.typo3.org/services/temp.txt>`__
- `$BASE/log-of-notifications.archive.001.txt <http://docs.typo3.org/services/log-of-notifications.archive.001.txt>`__

Not needed any more: Stuff in ``$BASE/ter/``. That folder can be deleted.

