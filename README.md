#Django reddit
Reddit clone written in python using django web framework and twitter's bootstrap.

#Getting up and running

[Uploading redit-test-demo.webm…]()


The project is using python 3.10.

The steps below will get you up and running with a local development environment. We assume you have the following installed:

    install pipenv
    
First make sure to create and activate a virtualenv, then open a terminal at the project root and install the requirements for local development:

    $ pipenv install
    $ python manage.py migrate
    $ python manage.py runserver
    
For the time being there is no separate production specific settings because the project is not yet production ready.
