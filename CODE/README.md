# Flask & React Message Board

The application is an anonymous message board with one-page design.

We use the technique below:

* Python-Flask
* React
* AJAX
* webpack
* Bootstrap

Moreover, we split the frontend and backend.

* frontend: we use React to build the tools with webpack.
* backend: Using flask framework，shelve module to do the data storage.


## HIGHLIGHT

* Response Design!
* The frontend uses React to process the sheets, AJAX to do the data transportation. It is much easy to understand and use within 100 lines of codes.
* Use python built-in modules shelve store data and configure the database without installing other database clients.
* Download the entire project without having to download other dependencies and open the http server to see the effect in the browser immediately.


## Backend

Activate virtual environment, install engineering dependencies, turn on http server.

```shell
$ virtualenv venv
$ source venv/bin/activate
(venv)$ pip install -r requirements.txt
(venv)$ python manager.py runserver
``````

Exit the virtual environment.

```shell
(venv)$ deactivate
``````

## Frontend

* Install the dependencies： `cd app/static/js && npm install`
* Execute webpack：`npm start`
