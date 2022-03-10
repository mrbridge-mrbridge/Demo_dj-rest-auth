### Demo Project to learn Dj-Rest-Auth
[![<iMerica>](https://circleci.com/gh/iMerica/dj-rest-auth.svg?style=svg)](https://app.circleci.com/pipelines/github/iMerica/dj-rest-auth)

This demo project shows how to use dj-rest-auth app. To run this locally, follow the following commands:
    
### Setup Steps 

* Get the copy locally, either by clone or fork
* cd dj-rest-auth/demo/
* OPTIONAL {You can run a virtual environment for this at this point}
* py -m pip install -r requirements.pip
* python manage.py migrate --settings=demo.settings --noinput
* python manage.py runserver --settings=demo.settings
* Now, go to http://127.0.0.1:8000/ in your browser


### Setup Steps for React (single page application) app
    
* cd react-spa/
* npm install
* npm start

### Documentation

View the full documentation here: https://dj-rest-auth.readthedocs.io/en/latest/index.html


### Acknowledgements

This project was originally by https://github.com/iMerica/
