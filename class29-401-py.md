# Django Custom User Model
> always use a custom user model for all new Django projects.

## Setup
1. we create a project with app 
> Note that we did not run migrate to configure our database. It's important to wait until after we've created our new custom user model before doing so.
2. in settings.py we update **AUTH_USER_MODEL** with our 'appname.CustomUser' 
3. create a class CustomUser in the model
4. create forms.py in the app directory
5. add subclasses in forms.py 
6. update the admin
7. now we create the superuser
8. add the templates


## AbstractUser vs AbstractBaseUser
> **AbstractBaseUser** requires much, much more work.

