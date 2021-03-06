========================
Tornado project skeleton
========================

This is my boilerplate to build a simple, fast and rock solid website. There
are quite many Tornado template projects out there, but I wanted to
start something from scratch, that fits my needs and evolves out of years of
experiences (positive and negative) with other Python based webframeworks like
Turbogears and Django.

Of course this template is not designed for larger data structures. The main
focus is on scalability, fast data access and small library dependencies.

Installation
============

Check out the sources and install the requirements::

 $ git clone git@github.com:hkage/tornado-project-skeleton.git
 $ pip install -e .

Configuration
=============

Start the server
================

To start the final application, just run the following fabric command::

 $ fab devserver

This will tell Tornado to start the applicaton with the default port 8888. If
you want to use another port, just type::

 $ fab devserver:port=8000

In addition to that, see the fabfile.py Script for other parameters and comands.

Using vagrant
=============

To run the server within a Vagrant VM, you need to install Vagrant 1.7.x and
start the development server with the following command::

 $ fab vagrant devserver

__ http://www.turbogears.com
__ http://www.djangoproject.com
__ http://www.tornadoweb.org
__ http://www.mongodb.org
__ http://code.google.com/closure
