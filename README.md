# Flask-Project->
## What is Web Framework?
Web Application Framework or simply Web Framework represents a collection of libraries and modules that enables a web application developer to write applications without having to bother about low-level details such as protocols, thread management etc.

## What is Flask?
Flask is a web application framework written in Python. It is developed by Armin Ronacher.Flask is based on the Werkzeug WSGI toolkit and Jinja2 template engine.

## WSGI
Web Server Gateway Interface (WSGI) has been adopted as a standard for Python web application development. WSGI is a specification for a universal interface between the web server and the web applications.

## Werkzeug
It is a WSGI toolkit, which implements requests, response objects, and other utility functions. This enables building a web framework on top of it. The Flask framework uses Werkzeug as one of its bases.


## Jinja2
Jinja2 is a popular templating engine for Python. A web templating system combines a template with a certain data source to render dynamic web pages.
Flask is often referred to as a micro framework. It aims to keep the core of an application simple yet extensible. Flask does not have built-in abstraction layer for database handling, nor does it have form a validation support. Instead, Flask supports the extensions to add such functionality to the application.

## Prerequisite
Python 2.6 or higher is usually required for installation of Flask. Although Flask and its dependencies work well with Python 3 (Python 3.3 onwards), many Flask extensions do not support it properly. Hence, it is recommended that Flask should be installed on Python 2.7.

Install virtualenv for development environment
virtualenv is a virtual Python environment builder. It helps a user to create multiple Python environments side-by-side. Thereby, it can avoid compatibility issues between the different versions of the libraries.

## The following command installs virtualenv

pip install virtualenv
This command needs administrator privileges. Add sudo before pip on Linux/Mac OS. If you are on Windows, log in as Administrator. On Ubuntu virtualenv may be installed using its package manager.

Sudo apt-get install virtualenv
Once installed, new virtual environment is created in a folder.

mkdir newproj
cd newproj
virtualenv venv
To activate corresponding environment, on Linux/OS X, use the following −

venv/bin/activate
On Windows, following can be used

venv\scripts\activate
We are now ready to install Flask in this environment.

pip install Flask
The above command can be run directly, without virtual environment for system-wide installation.
It will shows like ---> Installing collected packages: MarkupSafe, itsdangerous, colorama, Werkzeug, Jinja2, click, Flask


