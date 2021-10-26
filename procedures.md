0 - Django Architecture:

<p align="center">
  <a href="https://www.github.com/CarlosViniMSouza">
    <img src="https://github.com/CarlosViniMSouza/ebook_Django_Academy"/>
  </a>
</p>

1 - write in terminal:

```shell
print(django.get_version()) 
#(Output: 3.2.8)
 ```

For check django version installed(and if is installed).

2 - If your installation is correct, this command has already been added to your PATH!

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