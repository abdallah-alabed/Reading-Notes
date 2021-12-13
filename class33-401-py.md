# JSON Web Tokens
compact and self-contained way for securely transmitting information between parties as a JSON object. 

When should you use JSON Web Tokens?
- Authorization: allowing the user to access routes, services, and resources that are permitted with that token.
- Information Exchange: securely transmitting information between parties. 

How do JSON Web Tokens work?
1. In authentication, when the user successfully logs in using their credentials, a JSON Web Token will be returned.
2. Whenever the user wants to access a protected route or resource, the user agent should send the JWT, typically in the Authorization header using the Bearer schema.
3. The server's protected routes will check for a valid JWT in the Authorization header, and if it's present, the user will be allowed to access protected resources. 

How To Use it in Django Rest Framework?
1. pip install djangorestframework_simplejwt
2. in settings.py:
  - REST_FRAMEWORK = { \
    'DEFAULT_AUTHENTICATION_CLASSES': [ \
        'rest_framework_simplejwt.authentication.JWTAuthentication',
    ],
}
3. in urls.py:
  - urlpatterns = [ \
    path('api/token/', jwt_views.TokenObtainPairView.as_view(), name='token_obtain_pair'), \
    path('api/token/refresh/', jwt_views.TokenRefreshView.as_view(), name='token_refresh'), \
]

# Django Server 

why python manage.py runserver isnt used in production setting?
- It has not gone through security audits or performance tests.

> If you plan on running on Heroku, a web server is provided implicitly. 
> You don’t have to take care of it. You just need to specify a command to run your application server (again, Gunicorn is fine) in the Procfile.
