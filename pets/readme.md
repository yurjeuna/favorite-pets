#favourite pets
##run this commands to start project
###create env
> python3 -m venv env
> sorce env/bin/activate
### install requirements.txt
> pip install -r requirements.txt
### create postgres database
> psql -U postgres
> create database dbname;
> create user dbuser;
> grant all on database dbname to dbuser;
> \password dbuser
### fill .env file based ion .env.template  
### migrate
> python manage.py 
### create new user
### run
