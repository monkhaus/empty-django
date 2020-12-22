# empty-django
Comes with the following apps pre-installed
- djangorestframework
- debug_toolbar

This is an empty Django project that comes with djangorestframework and debug_toolbar by default. 
The settings.py file already includes the apps and the middleware so that doesn't need updating except for any additional apps you decide to add or settings you decide to change. 


1. git clone https://github.com/monkhaus/empty-django.git
2. cd empty-django
3. python3 -m venv ve
4. source ve/bin/activate
5. python -m pip install pip-tools
6. pip-sync
7. cd project
8. python manage.py runserver
