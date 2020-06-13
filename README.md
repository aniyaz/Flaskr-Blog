# Flaskr-Blog

A complete Flask based Blog website. Learnt it from Official flask tutorial.

How to Install the app?

Clone/Download this repository and get into the folder
First you need to set the environment variable.

For Linux and Mac:

    $ export FLASK_APP=flaskr
    $ export FLASK_ENV=development



For Windows cmd, use set instead of export:

    > set FLASK_APP=flaskr
    > set FLASK_ENV=development



For Windows PowerShell, use $env: instead of export:

    > $env:FLASK_APP = "flaskr"
    > $env:FLASK_ENV = "development"


Secondly, initialize the PostgreSQL DB
    $ flask init-db

Now, your app is ready to run
    $flask run
