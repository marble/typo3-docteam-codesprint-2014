
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

Description
-----------

::

   Web address:
      http://docs.typo3.org/services/handle_github_post_receive_hook.php

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


- `BASE/handle_github_post_receive_hook.php <http://docs.typo3.org/services/handle_github_post_receive_hook.php>`__
- `BASE/known-github-manuals.txt <http://docs.typo3.org/services/known-github-manuals.txt>`__
- `BASE/temp.txt <http://docs.typo3.org/services/temp.txt>`__
- `BASE/log-of-notifications.archive.001.txt <http://docs.typo3.org/services/log-of-notifications.archive.001.txt>`__

The stuff at ``BASE/ter/`` isn't needed any more and can be deleted.

How to activate hook processing
-------------------------------

Please read this `QuickStart Howto <http://docs.typo3.org/typo3cms/drafts/github/marble/DocumentationStarter/Quickstart/>`__.

