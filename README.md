# for-demo_purpose# User REST API :
This is the user authentication application by which we can be performed many API operations like user registration, login ,logout , change password, reset password and update user profile in Django Rest Framework.
# Technology Stack :
I have used in my application,

```
1. Python 3
2. Django REST Framework
3. sqlite3 Database
4. Google Chrome v.83.0.4103.61    
5. Google Chrome driver v.83.0.4103.61
```
# Project Structure :
```
.
├── accounts
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   ├── models.py
│   ├── __pycache__
│   ├── requirements.txt
│   ├── tests.py
│   └── views.py
├── db.sqlite3
├── manage.py
└── projct
    ├── __init__.py
    ├── __pycache__
    ├── settings.py
    ├── urls.py
    └── wsgi.py

```
# Running Locally
First, clone the repository to your local machine:

```
git clone https://github.com/Praful-Rathore-222/restapi.git

cd restapi
```

Install the requirements:

```
pip install -r requirements/dev.txt
```
Apply the database migrations:

```
python manage.py migrate
```

Load the initial data:
``
Create administrator/super user:
```
python manage.py createsuperuser 

```

Finally, run the development server:

```
python manage.py runserver
```

` The site will be available at 127.0.0.1:8000. `

Now, open a new terminal window, Run Celery with in your project root where manage.py lives: