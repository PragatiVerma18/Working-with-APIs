# Working-with-APIs
This repository contains my experiments with different APIs, working both as a frontend and a backend developer.

## Quick Start

To get this project up and running locally on your computer:
1. Set up the Python Virtual environment.
   
   ```
   virtualenv env
   .\\env\\Scripts\\activate
   ```
2. Clone the repository
   
   ```
   git clone https://github.com/PragatiVerma18/Working-with-APIs/
   ```
3. Assuming you have Python setup, run the following commands (if you're on Windows you may use `py` or `py -3` instead of `python` to start Python):
   
   ```
   pip install django
   pip install djangorestframework
   python manage.py makemigrations
   python manage.py migrate
   python manage.py collectstatic
   python manage.py createsuperuser # Create a superuser
   python manage.py runserver
   ```
4. Open a browser to `http://127.0.0.1:8000/admin/` to open the admin site
5. Open tab to `http://127.0.0.1:8000` to see the main site, signup and then login to move to the create page or move to
   
   ```
   http://127.0.0.1:8000/create
   ``

## Resources Used:
1. <a href="https://django-rest-auth.readthedocs.io/en/latest/installation.html">django-rest-auth</a>
2. <a href="https://www.django-rest-framework.org/">django-rest-framework</a>
3. <a href="https://www.youtube.com/watch?v=RPsDhoWY_kc&list=PLLRM7ROnmA9HzbIXYN6D3wOZ0wUrqNs_d">Build an API with Django - JustDjango</a>

## API Overview:
After cloning the repository on your local machine, visit http://127.0.0.1:8000/ on your web browser. Append the following to see the utilisation of this API.

1. <pre> admin/ </pre> 
To access the admin page, provided by the Django web framework.

2. <pre> api-auth/ </pre>
To authenticate the users.

3. <pre> api/token/ </pre>
To obtain an API token.

3. <pre> create/ </pre>
To create a post.
