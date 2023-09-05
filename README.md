this is a python project 
i have used django framework
you need to create a virtual environment before starting the project

How to setup the project

1.clone the repo with the command
git clone https://github.com/GuruRshetty/DP.git 
cd shopping

2.Create a virtualenv and install the required libraries from requirements.txt file
pip install -r requirements.txt

3.Run migrate command to create the db.sqlite3
python manage.py migrate

4.Create a superuser to access the database admin page
python manage.py createsuperuser

5.Make migrations for the product and order modules
python manage.py makemigrations
python manage.py migrate

6.password - Guru@2000

username-Guru
