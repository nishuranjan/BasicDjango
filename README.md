# BasicDjango
Setup of django application

Create a virtual environment
-------------------------------------
python -m venv env

Enable the policy to run the powershell
--------------------------------------------
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process

Activate the virtual environment
------------------------------------------
.\env\Scripts\activate     

Install the django 
-------------------------------------------
python -m pip install django

Create first django project
---------------------------------------------
django-admin startproject djangoproj .

Run the django server
----------------------------------------------
python manage.py runserver
