python3 -m venv menv               ##Set virtual envirolment 
source menv/bin/activate           ##activate virtual environment For linux  
pip install django                 ##install django
django-admin startproject movie    ##install django start projetc
cd movie
python3 manage.py startapp movieapp_list
python3 manage.py runserver
python3 manage.py migrate
python3 manage.py createsuperuser
enter user name and password
python3 manage.py runserver
127.0.0.0:8000/admin
 
   
