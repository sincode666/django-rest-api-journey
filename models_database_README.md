# Step 04: Models and Database

## Overview
Models define the structure of database tables using Django ORM.

## Example

##python
class Student(models.Model):
    name = models.CharField(max_length=100)
    age = models.IntegerField()


Migrations to make the structure as sql db_structure

Commands:
python manage.py makemigrations
python manage.py migrate


Models act as a bridge between Python code and the database.
Real-World Use:
Used to store user data, products, orders, etc.