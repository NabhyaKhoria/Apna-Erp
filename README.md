# Apna ERP
Apna ERP is an online web tool to function as a college erp. The system’s structure and functionality is very efficient and simple without any heavy packages installed. The website is fast and responsive. The website is built on Python using Django and Django REST Framework.

## Installation

Python need to be installed.
Requirements.txt packages need to be installed

```bash
pip install -r requirements.txt
```

## Usage

Go to the Apna-ERP folder and run

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.  

Example usernames:  
student- 'nabhya_035'  
password- 'nabhya_2002'

faculty- 'adrijit_ma001'
password- 'adrijit_1978'

admin- 'chad'
password- '1234'

You can access the django admin page at **http://127.0.0.1:8000/admin** and login with admin credentials given above.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin portal and NOT admin dashboard. 

The admin dashboard is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.

**For more details regarding the system and features please refer the reports included.**


## Screenshots
Refer the submitted report.


