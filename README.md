# Django CRM
A simple django CRM

<!-- ![django CRM App](/media/screenshot.png) -->
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/emperorKez/django-CRM.git
```

$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

create an admin user 
```bash
$ python manage.py createsuperuser
```

start the server 

```bash
$ python manage.py runserver
```

head over to http://127.0.0.1:8000/ for the App.

Cheers
