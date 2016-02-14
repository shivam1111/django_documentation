.. highlight:: rst

Installing Django
=================
-----------------

Install DB 
----------

- Get the latest version of postgres or any DB that Django supports

.. note::

	For Postgresql we need psycopg2 installed

Install easy_install script
---------------------------

- The easy_install script is in python-setuptools module. Hence install python-setuptools first ::

	sudo apt-get install python-setuptools

Installing Virtual Environment & Django
---------------------------------------

- Please find the documentation by clicking on this link :ref:`virtualenv-installation`.

.. note::

	For our installation purposes we will create virtual environment directory named `django`

::

	shivam@shivam:~$ virtualenv django
	shivam@shivam:~$ cd django
	shivam@shivam:~/django$ source bin/activate
	(django)shivam@shivam:~/django$ easy_install django

- Follwing is the screen shot of the above code

.. image:: django_easy_install.png
   :scale: 40
   :alt: Homepage



