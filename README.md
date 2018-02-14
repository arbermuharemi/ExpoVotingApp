# ExpoVotingApp
A web application that allows expo visitors to vote on their favorite Junior Design project.

## Installing packages
Be sure you have the proper packages to run the app.  These include flask and flask-mysql

 	$pip install flask

 	$pip install flask-mysql
 	
## Running the Flask Application

To run the flask app, open the command promt and navigate to the folder that holds the full application. Ensure that you have virtualenv installed on your computer using [these instructions](http://flask.pocoo.org/docs/0.11/installation/#installation).

If you don't have a venv/ folder in the project directory, run the following command:

    $ virtualenv venv

In the command line, enter the following code to activate the virtual environment:

__**Mac/Linux:**__

    $ . venv/bin/activate
   
__**Windows:**__

    $ venv\scripts\activate

Now, enter the following code to run the flask app:

**__change main.py to the file name of the file where the program starts__**

__**Mac/Linux:**__
   
    $ export FLASK_APP=main.py
    $ flask run
        * Running on http://127.0.0.1:5000/
        
__**Windows:**__

    $ set FLASK_APP=main.py
    $ flask run
        * Running on http://127.0.0.1:5000/

Now, just head over to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to view the running application.

## Databases

Database Information

PythonAnywhere Info:
* arbermuharemi@gmail.com
* expovoting123

Development Database Info (Management: [https://www.freemysqlhosting.net](https://www.freemysqlhosting.net)):
* Website: [http://www.phpmyadmin.co/](http://www.phpmyadmin.co/)
* Server/Host: sql9.freemysqlhosting.net
* Name: sql9219692
* Username: sql9219692
* Password: 5M2YS1HZdZ
* Port Number: 3306
