# Django Development
## Set the VIRTUAL_ENV path
```
$ source ./bin/activate
```

## Check Django is installed correctly
```
$ python -m django --version
```

## Make a new app
```
cd src
django-admin startproject <appname>
```

## Serve the app
```
python src/<appname>/manage.py runserver 8000
```
Port is optional. The server starts on port 8000 by default.

## Check your app
Navigate to [http://localhost:8000]() to see you app up and running.
