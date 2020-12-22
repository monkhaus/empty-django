# empty-django
Comes with the following apps pre-installed
- djangorestframework
- debug_toolbar

This is an empty Django project that comes with djangorestframework and debug_toolbar by default. 
The settings.py file already includes the apps and the middleware so that doesn't need updating except for any additional apps you decide to add or settings you decide to change. 


1. clone git repo 
VIA HTTPS: git clone https://github.com/monkhaus/empty-django.git 
VIA SSH: git clone git@github.com:monkhaus/empty-django.git

2. cd empty-django
3. python3 -m venv ve
4. source ve/bin/activate
5. python -m pip install pip-tools
6. pip-sync
7. cd project
8. python manage.py runserver




clone git repo 
VIA HTTPS: 
- git clone https://github.com/monkhaus/empty-django.git 

VIA SSH: 
- git clone git@github.com:monkhaus/empty-django.git

THEN copy into terminal:
- cd empty-django && python3 -m venv ve && source ve/bin/activate && python -m pip install pip-tools && pip-sync && cd project && python manage.py runserver
