# trydjango401

### Commands
- Create GitHUb repository:
  - On your local drive: git init
  - On your local drive: git add -A
  - On your local drive: git commit -m "First commit"
  - On your local drive: git branch -M main
  - On new created GitHub repository:  git remote add origin https://github.com/AgileDataScientist/trydjango401.git
  - On your local drive: git push -u origin main / git push origin master --force
- Create the Virtual Environment: virutalenv -p python310 .
- Activate the Virtual Environment. Use ".." or "." depending on directory: .\Scripts\activate
- Install django latest version: pip install django==4.0.1
- Create a new directory "src": 
  - mkdir src 
  - cd src
- Create django project: django-admin startproject muypicky .
- Create a new folder and two files within the folder before renaming the settings.py file to "old_settings" and copying content to base.py: 
  - mkdir settings
  - __init_.py
  - base.py
- Make sure in top level directory before installing these additonal applications:
  - pip install psycopg2
  - pip install gunicorn dj-database-url
  - pip install django-crispy-forms
  - pip install pillow
- Create a requirements.txt file: pip freeze > requirements.txt
- Run within the src-folder the manage.py file and migrate to setup the SQLite database: python manage.py migrate
  - Create a superuser and enter the credentials: python manage.py createsuperuser
- Run the server: python manage.py runserver ####
  - Enter a port number for the 4-hash marks
  
### Resturants Application
- Create a new application: python manage.py startapp restaurants 



