###########################################################
## this is a guide for the first basic setting for django platform
###########################################################

1.  install python

2.  Need nodejs 6.X.
    update cache by:
    curl --silent --location https://deb.nodesource.com/setup_6.x | sudo bash -
    install nodejs 

3.  bootstrap 
    - Tried but dropped Semantic UI Front-end (lightweight)Framework (because lack of documentation and many bugs that are not fixed..)
    - pip install django-bootstrap3

4.  virtualenv
    sandbox - for personal python system which it can carry its own packages.
    - Reference: https://tuwlab.com/26167

    To create:
        - install: sudo apt-get install python-virtualenv
        - create: virtualenv python -m myvenv <virtual env name>
        - activate: source myvenv/bin/activate
        - deactivate: deactivate

   4.1 pip command
       - pip install <package name>
       - pip freeze -check what packages it is installed
       - pip install -r requirements.txt - install from requirements.txt

5.  install django
    - pip install django
    -

6.  django-admin startproject <project-name>

7.  install packages
    - write in the requirement file (requirements.txt)
        djangorestframework
    
    pip install -r requirements.txt

    Migrate, Test run
    - python manage.py migrate
    - python manage.py runserver (default is 0.0.0.0:8000 <- only it can access locally)
    - python manage.py runserver <ip address:#port>

8. Basic setup for above framework,
   Refer to: https://semantic-ui.com/introduction/getting-started.html

Reference
[1] Tutorial: https://docs.djangoproject.com/en/1.11/intro/tutorial01/

