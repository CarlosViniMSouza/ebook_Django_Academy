Image - Django Architecture:

<p align="center">
  <a href="https://www.github.com/CarlosViniMSouza">
    <img src="https://github.com/CarlosViniMSouza/ebook_Django_Academy/blob/master/images/django_architecture.png"/>
  </a>
</p>

1 - write in terminal:

```shell
print(django.get_version()) 
#(Output: 3.2.8)
 ```

For check django version installed(and if is installed).

2 - If your installation is correct, this command has already been added to your *PATH*!

By just typing django-admin, the list of available commands, similar to:

```
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
 startproject
 test
 testserver
```

3 - For now, we are interested in the startproject command that creates a new project with the right directory structure for we start to develop!

We run this command as follows:

```shell
django-admin startproject helloworld
```

4 - Creating the following directory structure:

```
/helloworld
 - __init__.py
 - settings.py
 - urls.py
 - wsgi.py
- manage.py
```

Explaining each file:

° *helloworld/settings.py*: Very important file with the settings of our project, such as database settings. data, installed applications, static files configuration and a lot more.

° *helloworld/urls.py*: Routes configuration file (or URLConf). It's where we configure who responds to which URL.

° *helloworld/wsgi.py*: Here we configure the interface between the application server and our Django application.

° *manage.py*: Django-generated file that exposes important commands for maintaining our application.

5 - To test, go to the project's root folder and run the command: 

```shell
python manage.py runserver
```

Then access your browser and write: `http://localhost:8080`

And so, this page will show for you:

<p align="center">
  <a href="https://www.github.com/CarlosViniMSouza">
    <img src="https://github.com/CarlosViniMSouza/ebook_Django_Academy/blob/master/images/djang_hello_world.png"/>
  </a>
</p>

These were the procedures needed to start the project.