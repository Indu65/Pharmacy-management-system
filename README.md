requirements.txt
Django==5.2.7
Pillow==10.1.0
sqlparse==1.0.6

2️⃣ README.md
# Pharmacy Django Mini Project

## Project Overview
This is a Django-based web application for managing a pharmacy. The project allows users to manage medicines, products, and related inventory efficiently. It demonstrates CRUD operations, image uploads, and basic web functionalities using Django.

---

## Features
- Add, update, and delete medicines and product items.  
- Upload images for medicines and products.  
- Display lists of medicines and products on the homepage.  
- Basic web interface with templates for displaying data.  
- Built using Django 5.x and Python 3.9/3.10.

---

Installation

1. **Clone the repository**:
bashgit clone <your-repo-link>
cd Pharmacy-Django-Mini-Project-master


Create a virtual environment:

python -m venv venv


Activate the virtual environment:

Windows PowerShell:

.\venv\Scripts\Activate


Windows CMD:

venv\Scripts\activate.bat


Install dependencies:

pip install -r requirements.txt


Apply migrations:

python manage.py migrate


Run the development server:

python pharmacyproject/manage.py runserver


Open your browser at http://127.0.0.1:8000

Project Structure
Pharmacy-Django-Mini-Project/
│
├── pharmacyproject/       # Main Django project
│   ├── app/               # Application for managing medicines/products
│   ├── settings.py        # Project settings
│   └── urls.py            # Project URLs
│
├── templates/             # HTML templates
│   └── Home.html
│
├── media/                 # Uploaded images
├── manage.py
└── requirements.txt       # Project dependencies

Dependencies

Django==5.2.7

Pillow==10.1.0

sqlparse==1.0.6


License

This project is licensed under the MIT License.




