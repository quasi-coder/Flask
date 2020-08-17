#Create a virtual environment property  
python3 -m venv .venv

#Activate the environment so that whatever module install will be installed local not globally 
source .venv/bin/activate

Link of site
http://127.0.0.1:5000/

pip3 freeze > requirements.txt
pip3 install -r requirements.txt

A general utility script for Flask applications.

  Provides commands from Flask, extensions, and the application. Loads the
  application defined in the FLASK_APP environment variable, or from a
  wsgi.py file. Setting the FLASK_ENV environment variable to 'development'
  will enable debug mode.

    $ export FLASK_APP=hello.py
    $ export FLASK_ENV=development
    $ flask run

Options:
  --version  Show the flask version
  --help     Show this message and exit.

Commands:
  routes  Show the routes for the app.
  run     Run a development server.
  shell   Run a shell in the app context.


  Mongo Import from the file:
  mongoimport --jsonArray --db UTA_Enrollment --collection user --file "/Users/users.json"



  