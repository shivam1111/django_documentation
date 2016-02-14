.. highlight:: rst

Creating Django Project
-----------------------

- Goto the virtual environment folder and activate the environment

- Now goto `bin` folder and you will find file name `django-admin`

- Just type the name of the file and press enter to display the commands available to you

- Amongst them there will be command `startproject`. This will help you create a project

.. image:: working_project.png
   :scale: 40
   :alt: Homepage

Following is the text of the screenshot

::

	shivam@shivam:~$ cd django
	shivam@shivam:~/django$ source bin/activate
	(django)shivam@shivam:~/django$ cd bin
	(django)shivam@shivam:~/django/bin$ ls
	activate      activate.fish     django-admin     django_test   easy_install-2.7  pip2    python   python2.7
	activate.csh  activate_this.py  django-admin.py  easy_install  pip               pip2.7  python2  wheel
	(django)shivam@shivam:~/django/bin$ django-admin

	Type 'django-admin help <subcommand>' for help on a specific subcommand.

	Available subcommands:

	[django]
	    check
	    compilemessages
	    createcachetable
	    dbshell
	    diffsettings
	    dumpdata
	    flush
	    inspectdb
	    loaddata
	    makemessages
	    makemigrations
	    migrate
	    runserver
	    sendtestemail
	    shell
	    showmigrations
	    sqlflush
	    sqlmigrate
	    sqlsequencereset
	    squashmigrations
	    startapp
	    `startproject`
	    test
	    testserver

- To create the project type ::

	django-admin.py startproject `django_test`

.. note::
	No hyphins allowed in the name of the project name

Running Django Project
----------------------

- To run the project 
	* Activate the virtualenv
	* Goto the project folder where you will find the `manage.py` file
		* The project folder will be in the path where you have executed the `django-admin.py startproject <project_name>` script	

	* Type ::
			
			python manage.py runserver

.. image:: running_project.png
   :scale: 40
   :alt: Homepage

- Now goto chrome and type `localhost:8000`

.. image:: chrome_project.png
   :scale: 40
   :alt: Homepage

                                       
Changing Developement Server Port
---------------------------------

- By default, the runserver command starts the development server on port 8000, listening only for local connections. If you want to change the server’s port, pass it as a command-line argument ::
    
    python manage.py runserver 8080

- By specifying an IP address, you can tell the server to allow non-local connections. This is especially helpful if you’d like to share a development site with other members of your team. The IP address 0.0.0.0 tells the server to listen on any network interface ::
    
    python manage.py runserver 0.0.0.0:8000
    
When you’ve done this, other computers on your local network will be able to view your Django site by visiting your IP address in their Web browsers, e.g., http://192.168.1.103:8000/ . (Note that you’ll have to consult your network settings to determine your IP address on the local network. Unix users, try running “ifconfig” in a command prompt to get this information. Windows users, try “ipconfig”.)
        
    
Creating superuser for admin
----------------------------

Type the command in yout project directory and enter all the questions ::

    python manage.py createsuperuser
