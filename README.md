# item-catalog-udacity-nanodegree

This is the fourth project of Full Stack Web Develper Nanodegree by Udacity.

Users can sign in with google or facebook. After sign in, they can create, edit, delete category or course.

## Project Description
>This is a project assigned by Udacity in part of the Udacity Full Stack Nanodegree program. In This project, we're provided a sql file to generate a `sqllite` database and a `Vagrantfile` settings to run a VM server to run the database.
>Your task is to create a reporting tool that prints out reports (in plain text) based on the data in the database. This reporting tool is a Python program using the psycopg2 module to connect to the database.

## Setting up the VM using VirtualBox and Vagrant
1. Download and install VM using [VirtualBox](https://www.virtualbox.org/wiki/Downloads)  
2. Download and install [Vagrant](https://www.vagrantup.com/downloads.html) for the VM settings 
3. Download Vagrantfile in the working folder and Run command `vagrant up` to load box and settings the VM
4. Run `vagrant ssh` to log into the VM



## Getting started

To get started with the app, you need to install [Virtualenv][1].
Then make a virtual environment.

    $ git clone https://github.com/wleandrooliveira/item-catalog-udacity-nanodegree.git
    $ cd item-catalog
    $ virtualenv --python=/usr/bin/python env --always-copy
    $ source env/bin/activate
    $ export CATALOG_ENV='dev'
    $ pip install -r requirements.txt
    $ python db_start.py dropdb
    $ python db_start.py createdb
    $ python db_start.py initdb

Run Application

    $ python db_start.py runserver

Access Application

    $ http://localhost:5000


## Social login

To use social login, you need to get client id from google and facebook and set environment variables.

    $ export GOOGLE_CLIENT_ID='YOUR_GOOGLE_CLIENT_ID'
    $ export GOOGLE_CLIENT_SECRET='YOUR_GOOGLE_CLIENT_SECRET'
    $ export FB_CLIENT_ID='YOUR_FACEBOOK_CLIENT_ID'
    $ export FB_CLIENT_SECRET='YOUR_FACEBOOK_CLIENT_SECRET'


[1]: https://virtualenv.pypa.io/en/stable/installation/


## Used skills

### Languages

 - HTML / CSS
 - JavaScript
 - Python

### Frameworks
 - [Flask][2]
 - [Bootstrap][3]
 - [Simple Blog Template][5]
 - [Jinja2][6]

[2]: http://flask.pocoo.org/
[3]: http://getbootstrap.com/
[6]: http://jinja.pocoo.org/docs/dev/
