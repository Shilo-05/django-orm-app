# Django ORM Web Application

## NAME: Oswald Shilo.A
## REFERENCE NUMBER: 2300 6556

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram


## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create 10 Football players

## PROGRAM
**
admin.py
from django.contrib import admin from .models import Employee,EmployeeAdmin admin.site.register(Employee,EmployeeAdmin)

modles.py

from django.db import models from django.contrib import admin class Employee (models.Model): eid=models.CharField(max_length=20,help_text="Employee") name=models.CharField(max_length=100) salary=models.IntegerField() age=models.IntegerField() email=models.EmailField()

class EmployeeAdmin(admin.ModelAdmin): list_display=('eid','name','salary','age','email') 
**

## OUTPUT
![293314117-766388e3-60ce-4d46-aaba-ccc280f16dcd](https://github.com/Shilo-05/django-orm-app/assets/139841664/75c4e9df-4d00-4773-9674-a7d40906c73c)


## RESULT
Thus the program for creating a database using ORM has been executed successfully with some users been created..

