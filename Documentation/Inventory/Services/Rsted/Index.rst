
.. include:: ../../../Includes.txt

==================================================
ReST Online Editor
==================================================


.. _rst-ninjs-org:

ReST Online Editor by Andrey Rublev
===================================

The original online version
---------------------------

:title:  `Online ReStructuredText Editor <http://rst.ninjs.org/>`__
:type:   service
:path:   /home/mbless/rst-ninjs-org/rsted
:repo:   https://github.com/anru/rsted
:who:    `Andrey Rublev, Novosibirsk, Russia <https://github.com/anru>`__


As a service on docs.typo3.org
------------------------------

The service has to be started manually after a server reboot or in case
the process crashes.

1. Start the service::

      $ ### start the service on docs.typo3.org

	  $ # make sure you are user 'mbless'
	  $ sudo su mbless

      $ # go to the startfolder
      $ cd /home/mbless/rst-ninjs-org/rsted

      $ # start the application as a service
      $ python application.py &

2. In a browser launch `docs.typo3.org:5000 <http://docs.typo3.org:5000/>`__ and see
   if it works.

3. Select 'Theme: Nature' to get a TYPO3 like theme.

4. Reload the page if it seems to hang due to error messages.

.. note::

   Every now and then the service may really crash. In this case the
   application needs to be restarted on the server.