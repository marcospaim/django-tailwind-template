# django-tailwind-template
This is a simple starter template for you to quickly set up a Django project with Tailwind.

## ✨ Features
- Python 3.12 and Django 5.2
- Tailwind CSS integration with [Django-Tailwind] (https://django-tailwind.readthedocs.io/en/latest/)
- Debugging with [django-debug-toolbar](https://django-debug-toolbar.readthedocs.io/en/latest/)

## Requirements

Python 3.10 or newer and Node.js

## Installation
Set up a new virtual environment to isolate dependencies and then install all dependencies listed in `requirements.txt`. Run `migrate` to set up the database schema and `createsuperuser` to create a new superuser account for accessing the admin. Execute the `runserver` command to start the local server.

```
(.venv) $ pip install -r requirements.txt
(.venv) $ python manage.py migrate
(.venv) $ python manage.py createsuperuser
(.venv) $ python manage.py runserver
```
In a new terminal, activate the Python virtual environment and run the following commands to install Tailwind CSS dependencies and start Django Tailwind in development mode:
```
(.venv) $ python manage.py tailwind install
(.venv) $ python manage.py tailwind start

```
## License

[The MIT License](LICENSE)