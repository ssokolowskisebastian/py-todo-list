# py-todo-list
Python 3 must be already installed

1. Clone repository

```shell
git clone https://github.com/ssokolowskisebastian/py-todo-list
```

2. Create and activate .venv environment

```shell
python -m venv venv
```
on Windows
```shell
venv\Scripts\activate
```
on macOS
```shell
source .venv/bin/activate
```

3. Install requirements.txt 

```shell
pip install -r requirements.txt
```

4. Make migrations

```shell
python manage.py makemigrations
python manage.py migrate
```

5. Load fixtures (Optional, but recommended)

```shell
python manage.py loaddata data.json
```

6. Create superuser

```shell
python manage.py createsuperuser
```

7. Run server

```shell
python manage.py runserver # http://127.0.0.1:8000/
```


## Features

Tasks:
* Creating
* Updating
* Deleting

Tags:
* Creating
* Updating
* Deleting

## Built with

Technologies used in the project:

*   Backend: Django (Python)
*   Database: SQLite
*   Styles: Bootstrap 4
