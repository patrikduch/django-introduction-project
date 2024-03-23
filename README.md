# django-introduction-project

## Development


Prepare virtualenv
```bash
python -m venv myvenv  
```

Go to virtualevn

On Windows:
```bash
myvenv\Scripts\activate
```

On macOS and Linux:
```bash
source myvenv/bin/activate
```


Install the dependencies
```bash
pip install -r requirements.txt
```

Command for Db preparation
```bash
python manage.py migrate
```

Startup of Webserver
```bash
python manage.py runserver
```