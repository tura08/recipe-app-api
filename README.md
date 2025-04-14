# recipe-app-api
Recipe API project

# to run linting tool
docker-compose run --rm app sh -c "flake8"

# to start a new django project inside docker
docker-compose run --rm app sh -c "django-admin startproject app ."

# to start the server
docker-compose up

# to run a test
docker-compose run --rm app sh -c "python manage.py test"