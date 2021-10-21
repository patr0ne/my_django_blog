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


## Screenshots
### Main page
![image](https://user-images.githubusercontent.com/62960493/138349259-899a025e-9acb-42c3-abfb-038a5b1bb394.png)
### Post detail
![image](https://user-images.githubusercontent.com/62960493/138349497-9e3370b1-0d5b-480d-8baf-592b1f001fb3.png)
### Search page
![image](https://user-images.githubusercontent.com/62960493/138349660-96f243f8-1617-44e7-be7d-e35a88878d77.png)
### Tags page
![image](https://user-images.githubusercontent.com/62960493/138349736-3d53f763-b5cb-4821-a5ff-450cad5f9daf.png)
### Contact us page
![image](https://user-images.githubusercontent.com/62960493/138349807-ecc09f93-b216-4b0b-8f8a-bd560c34726b.png)

