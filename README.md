# pollswebapp
this is polls webapp created in django using official django documentation

<br>
<b> I prefer Django Official documentation and some youtube videos as a django begginer to do this basics project Django docs Polls app</b>

# Following are steps for how i setup project and all things you need to know if you ae begginer to Django 
# And this project go according to the django documentation and here is no erros so you can use for yourself

Steps

Step 1 First make your own Directory in windows Command prompt or in Powershell using command ```mkdir mydjango``` for example -mydjango i used here

Then simply change that directory using command ```cd Mydjango```

Step 2 Then lets make your own virtual environment in that directory for that particular project using command ```python -m venv myenv```

venv is virtual environment -m is for make i guess

After that you to activate your virtual environment using command

command :- ```myenv\Scripts\activate```

Then you to install django in that particular directory using command

Command :- ```pip install django```

Note:- in your system before doing this python is installed this is must for working of django commands and pip also

and after that for creating django project command is

Command :- ```django-admin.exe startproject mysite .```

. for the directory structure if donot used then you can experience that i experience that :))

And after that you can run your project using

Command ```python manage.py runserver```

```127.0.0.1:8000``` on your local system ok

and for creating app in django in your particular directory ```python manage.py startapp myapp```

and for migrations of databases make sure add your app in settings.py file in installed app section ok

And for creating superuser for admin interface use command

Command :- ```python manage.py createsuperuser```

and then migrate that particular file using

Command using ```python manage.py migrate```

and check your browser for django project working

See using this command ```localhost:8000 ```port
<br>
# You can check it out my blog for setuping django on windows machine on Medium 
<a href="https://medium.com/@krishnakakade77" target="_blank"><b>krishnakakade</b></a>
<br>
<b>View of my project polls app</b>

