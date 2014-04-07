
.. include:: ../../../Includes.txt

==================================================
Gerrit Hook Processing
==================================================

Rendered: |today|

**Jump up and down on this page:**

.. contents::
   :local:

.. _gerrit-hook:

Gerrit Hook
===========

Note: Each and every Gerrit-Change-Merge event ist signaled to the script.
If the documentation project is known a "wget request_rebuild.php" for the
corresponding project ist done.

::

   Web address:
      http://docs.typo3.org/php/php

   Installed at:
      BASE=/home/mbless/public_html/php/git-typo3-org-change-merged.php

   which is a symlink to:
      /home/mbless/HTDOCS/github.com/marble/typo3-docs-typo3-org-resources.git/webroot/php

   Cannot be viewed via the following line because of an .htaccess file:
      http://docs.typo3.org/~mbless/HTDOCS/github.com/marble/typo3-docs-typo3-org-resources.git/webroot/php/

   Script
      SCRIPT=$BASE/git-typo3-org-change-merged.php

   The script itself contains an array which lists known projects (bad, I know!)
      The script needs to be modified for a new documentation project.

   The script logs to:
      $BASE/zzzlog-1.txt
      $BASE/zzzlog-2.txt
      $BASE/zzzlog-3.txt

..
View:

- `BASE/zzzlog-1.txt <http://docs.typo3.org/php/zzzlog-1.txt>`__
- `BASE/zzzlog-2.txt <http://docs.typo3.org/php/zzzlog-2.txt>`__
- `BASE/zzzlog-3.txt <http://docs.typo3.org/php/zzzlog-3.txt>`__


