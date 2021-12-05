# Models in Django
independent of the underlying database — you can choose one of several as part of your project settings. (the structure of stored data, including the field types and possibly also their maximum size, etc..)

## Model primer
1. in the app models.py
2. create a class with the model name

**Fields**: the data we want to store in the database and can have restrictions and manipulations.

**Methods**: __str__() to return a human-readable string for each object. 

## Model management
1. save(): to store modifications.
2. filter(): searching for matches.

# Admin in Django
The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records.

1. from django.contrib import admin  
> import
2. admin.site.register  
> to register the admin
3. we can create a super user
> has full access to the site and all needed permissions using manage.py.

