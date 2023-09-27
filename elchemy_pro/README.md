# Elchemy
# This code is used for Elchemy backend api for Website / Mobile / Admin 

cd Elchemy
# Create a virtual environment to isolate our package dependencies locally
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install Django and Django REST framework into the virtual environment
pip install django
pip install djangorestframework

# Cmd for new app
cd elchemy_pro
django-admin startapp "APPNAME"

# Cmd for run project
python manage.py runserver

