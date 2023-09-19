# Steps to Running a Django Project
## A. Setting up a new 
	- projectCreating a new project
1. create a container folder -
    mkdir <name of dir>
	open the VS Code
    code . 
    [git init]
3. install djngo inside the folder 
    (pipenv install django)
	- should be able to see the Pipfile and Pipfile.lock
4. Activate the virtual environment -
    (pipenv shell)
5. Insode thje VS code
    press ctrl +p
	
 type the >pthon interpreter
 select the name of your folder
 
 6. type django-admin startproject <BlogProject>
 *** move into this folder
    cd <>
 7. Make the migrations- 
 		first command (python manage.py makemigrations) - responsible for checklist
		second command (python manage .py migrate) - responsible for ....establishing
8. Creating the superuser account - so we are able to access the admin console (manage.py createsuperuser)

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
 
