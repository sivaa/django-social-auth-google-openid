django-social-auth-google-openid
================================

Google OpenID integration for Django Admin Interface using django-social-auth

Installation
------------

- $ virtualenv django-social-auth-google-openid
- activate the virtual environment (Source/activate.bat (or) ./activate.sh) 
- $ pip install -r requirements.txt (uncomment the MySQL-python if you are using mysql)


Configuration
------------

The new users can be given the super user permissions using

SOCIAL_AUTH_CREATE_USERS_AS_SUPER_ADMIN = True