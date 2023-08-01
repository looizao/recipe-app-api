# recipe-app-api

## Docker Compose commands

#### Run tests
`docker compose run --rm app sh -c "python manage.py test"`

#### Run Linter
`docker compose run --rm app sh -c "flake8"`

#### Make Migrations
`docker compose run --rm app sh -c "python manage.py makemigration"`

#### Apply migrations
`docker compose run --rm app sh -c "python manage.py migrate"`