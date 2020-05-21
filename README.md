# PCHS

Platform Cooperative for House Services

Technology: Django 3.0.6

Use python3 previously intalled in my system

Install pip
python3 -m pip install --upgrade pip

Install virtualenv
pip3 install virtualenv

Create virtualenv environment
virtualenv -p python3 venv

created virtual environment CPython3.6.8.final.0-64 in 426ms
  creator CPython3Posix(dest=/home/caracol/Dev/PCHS/venv, clear=False, global=False)
  seeder FromAppData(download=False, pip=latest, setuptools=latest, wheel=latest, via=copy, app_data_dir=/home/caracol/.local/share/virtualenv/seed-app-data/v1.0.1)
  activators BashActivator,CShellActivator,FishActivator,PowerShellActivator,PythonActivator,XonshActivator

Activate virtulenv
source venv/bin/activate

Deactivate virtualenv
deactivate

Install Django
python -m pip install Django

Successfully installed Django-3.0.6 asgiref-3.2.7 pytz-2020.1 sqlparse-0.3.1

Create proyect
django-admin startproject mysite .

Update Python for use Postgresql
sudo apt install python3-dev python3-psycopg2

Install postgresql libraries
pip3 install psycopg2