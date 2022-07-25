# Cinema

REST API for managing cinema service.


## Installing

Python3 and Docker must be already installed


```shell
git clone https://github.com/RomaTsybulia/Cinema.git
cd Cinema
python -m venv venv
source venv/Scripts/activate 
pip install -r requirements.txt
python manage.py runserver
set DB_HOST=<your_db_host>
set DB_NAME=<your_db_name>
set DB_USER=<your_user_name>
set DB_PASSWORD=<your_db_password>
python manage.py migrate
python manage.py runserver
```


## Docker
```shell
docker-compose build
docker-compose up
```
