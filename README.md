# Steps to Running a Django Project
## A. Setting up a new 
	- projectCreating a new project
1. create a container folder - mkdir
	open the VS Code code . 
	[git init]
2. install djngo inside the folder 
	(pipenv install django)
	- should be able to see the Pipfile and Pipfile.lock
3. Activate the virtual environment - (pipenv shell)
4. Insode thje VS code press ctrl +p
	
 type the >pthon interpreter
 select the name of your folder
 
 *** type django-admin startproject BlogProject
 *** move into this folder
 5. Make the migrations- 
 		first command (python manage.py makemigrations) - responsible for checklist
		second command (python manage .py migrate) - responsible for ....establishing
6. Creating the superuser account - so we are able to access the admin console (manage.py createsuperuser)

 ## B. Opening an existing project
 1.  go to the containing folder 
 2.  type the command to open vs code (code .)
 3.  once iside run the command (pipenv shell)
 4.  press control+p to select the interpreter
 	- choose the name of your folder
5. find the file named manage.py by running ls on the containing folder
6. Go into the containd project(cd <folder_name>) and type ls to find the manage.py file
7. run the command (python manage.py runserver)
8. open the browser and type localhost:8000
9. inside the browser run the command localhost:8000/admin
 
