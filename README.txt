This is a Chat server with Django + redis + JS

Firstly, run the redis server in backend in port '6379'
HINT-Installing redis is easier in windows through Docker

For running this django project use following commands inside src folder in cmd

F:\src> virtualenv chat_env
F:\src> cd chat_env/Scripts
F:\src> activate
F:\src> cd ../../
F:\src> pip install -r requirements.txt  (ERROR: install in administrator mode)

After this For running server
F:\src> python manage.py runserver
