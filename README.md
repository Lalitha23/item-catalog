# Item-catalog-Project
**RestaurantMenuapp** for Item catalog project This is a python module that creates a website and JSON API for a list of restaurants. Each restaurant displays their menus and also provides user authentication using Google. Registered users will have ability to edit and delete their own items. This application uses Flask,SQL Alchemy, JQuery,CSS, Javascript, and OAuth2 to create Item catalog website.

#### Installation 1.virtualBox 2.Vagrant 3.python 2.7

#### Instructions to Run the project

Setting up OAuth 2.0 1. You will need to signup for a google account and set up a client id and secret. 2. Visit http://console.developers.google.com for google setup.

#### Setting up the Environment

* clone or download the repo into vagrant environment.
* Type command vagrant up,vagrant ssh.
* In VM, cd /vagrant/catalog
* Run python database_setup.py to create the database.
* Run Python lotsofmenus.py to add the menu items
* Run python 'project.py'
* open your webbrowser and visit http://localhost:8000/

#### To Do
* Use Javascript and style restaurant pages
* Include more pictures 
* Asyncronous loading / applying knockout bindings to look aesthetic
