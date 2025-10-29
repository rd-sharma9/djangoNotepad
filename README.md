# All things I learn 

day 1:

first i made the venn using this command ` python -m venv venv `
secondly i made the folder using django command "django-admin startproject backend"
thirdly i again made the folder using python command "python manage.py startapp api"

Afther this 

I install the dependenics by activation venv first "venv\Scripts\activate"
then i install all dependencies using " pip install -r requirements.txt "


Now I create the serializer.py file in api i wrote a some code
similarly write some code to view.py present inside api of backend



### Challlenge

from rest_framework_simplejwt.views is not detecting or suggesting its modules

-> solved by ctrl+shift+P then Python: Select Interpreter to use the venv we are working 
-> and adding the libarrary in setting.py of backend installed_apps

## Now

I write the code to both urls.py of api and backend inside backend

and run the commands -> python manage.py makemigrations 
                     -> python manage.py migrate


after this i write a code in model.py, url.py of both , serializer.py