## docker-django-base

This repo can be used to setup a Django project locally on your machine.

You can clone this repo, and if you have docker installed you just need to run

```
docker-compose run web django-admin.py startproject composeexample .

```

This will create the DJango project for you.

Running `docker-compose up` after this will start the project.

You can connect to your docker instance by looking up the container id using `docker ps` and then `docker exec -it <ID> sh`

This will allow you to run migrations eg. `python3 manage.py migrate`

