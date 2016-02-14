.. highlight:: rst

.. _virtualenv-installation:

Virtual Environment
===================
-------------------

Installing Virtual Environment 
------------------------------

::

	sudo easy_install virtualenv


Create Virtual Environment Directory
------------------------------------

To create a virtual environment directory ::

	virtualenv <directory name>

Activate the Virtual Environment
--------------------------------

- Go into the created Virtual Environment Directory and type ::

	source bin/activate

- The activation of virtual environment tells the current shell to change the context of the current environment so that root of package installation will be re-routed to this folder


Deactivate the activated virtual environment 
--------------------------------------------

Go into the activated virtual environment directory and type ::

	deactivate
