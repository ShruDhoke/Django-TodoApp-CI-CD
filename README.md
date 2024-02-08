<h1 align="center">Django-todo</h1>

A straightforward application for keeping track of tasks, developed using the Django web framework.

<h1 align="center">SetUp</h1>

To get this repository, run the following command inside your git-enabled terminal

$ git clone https://github.com/ShruDhoke/Django-TodoApp-CI-CD.git

You will need Django to be installed on your computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded Django, go to the cloned repo directory and run the following command


$ python manage.py makemigrations

This will create all the migrations files (database migrations) required to run this App.

Now, to apply these migrations run the following command

$ python manage.py migrate


One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user

$ python manage.py createsuperuser

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command


$ python manage.py runserver

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

<h1 align="center">OutPut</h1>
<img align="right" alt="Coding" height="500" width="4000" src="https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png">


Cheers, and Happy Coding :)
