# React Django CRUD Project
- creating virtual environment
```
python -m venv env
```
- activate the virtual environment
```
.\env\Scripts\activate.bat
```
- Install Django & show details
```
pip install django
pip show django
```
- Install everything in requirements.txt file
```
pip install -r requirements.txt
```
- then start project backend
```
python -m django startproject backend 
cd .\backend\
python manage.py startapp api
```
- to run the project
```
python manage.py runserver
```

```
manage.py -> settings.py -> urls.py
```

