# Django Development
## Set the VIRTUAL_ENV path
```
$ source ./bin/activate
```

## Install Django (and other requirements)
```
$ pip install -r requirements.txt
```

## Check Django is installed correctly
```
$ python -m django --version
```

## Create a new project, if necessary
A new project has already been created in `src/`
```
$ django-admin startproject <src>
```
This automatically creates a default app `src/app/`
```
$ django-admin startapp <app>
```

## Create a new app

## Serve the app
```
$ python <src>/manage.py runserver 8000
```
Port is optional. The server starts on port 8000 by default.

## Check your app
Navigate to [http://localhost:8000]() to see you app up and running.
