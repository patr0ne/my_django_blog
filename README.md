# Django blog

## Install and start

#### 1. Set up the Python development environment. We recommend using a Python virtual environment.
      
#### 2. Install requirements

```pip install -r requirements.txt```

#### 3. Please create .env file in folder project(repo/blog/blog) with variables:
```
SECRET_KEY = 'Your Django secret key'
EMAIL_HOST_USER = 'Your email for receiving messages in the contacts.html form'
EMAIL_HOST_PASSWORD = 'Your secret key from the email (in my case, the google application key was used)'
```

#### 4. 

```
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py collectstatic
python3 manage.py createsuperuser  # Create a superuser
python3 manage.py runserver
```

#### 5.
Open a browser to http://127.0.0.1:8000 to see the main site and to http://127.0.0.1:8000/admin/ to open the admin site
