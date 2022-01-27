# User-authentication-using-django
User creation and login using django and postgresql


This Project is done using Django as backend and 
database used is postgres. 

This project runs in the localhost. 

change the database part in setting.py according to your system.
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'database name',
        'USER': 'user name',
        'PASSWORD': 'your password for postgres',
        'HOST': 'localhost',
    }
}

steps to run:
Run these steps in the project folder
1) Run it in your virtual environment
2) Run the command "python manage.py migrate" to create the default database.
3) Change the settings.py (feyre/settings.py) as given above
4) Run the command "python manage.py runserver"


feyre-the main app having all the main urls
home-the home page and everything regarding that
accounts-has the views and urls regarding the user signup and signin
static-has the images required
templates-all the html pages
