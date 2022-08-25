# pollApp

## To migrate the database open terminal in project directory and type
- python manage.py makemigrations
- python manage.py migrate

## To use admin panel you need to create superuser using this command
- python manage.py createsuperuser

## To Create some dummy text data for your app follow the step below:
- pip install faker
- python manage.py shell 
- import seeder
- seeder.seed_all(30)

## To run the program in local server use the following command
- python manage.py runserver

- Then go to http://127.0.0.1:8000 in your browser
