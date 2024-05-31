1. Create folder for your project.

2. Create virtual environment: "python -m venv venv".

3. Activate virtual environment: ".\venv\Script\activate(using cmd or any other cli).

4. Install Django "pip install django".

5. "pip list" to see if packages have been installed.

6. make sure your python is in path of your system otherwise nothing will work and we are creating the virtual environment in case dependencies 
are only installed in the v-env not in the entire system itself.

7. "django-admin startproject crm" to create your backend.

8. Now above command will create a django app(manage.py file) in crm folder.

9. In our root directory CRM there is now two folders one id venv and other I made is crm and in that we have two files one is manage.py and when 
you run this file with command "python manage.py" remeber run in this command in the CRM/crm directory.

10. This command will make db.sqlite3 file.

11. "django-admin startapp webapp" to create webapp.

12. "python manage.py migrate" migrate to your environment.

13. "python manage.py createsuperuser" after than follow the instructions in terminal.p