PlainStore
==========

> Dead simple store for digital goods


## Local setup

1. Install NodeJS and Python Poetry first

2. Install dependencies

```sh
poetry install
poetry run src/manage.py tailwind install
poetry run src/manage.py migrate
poetry run src/manage.py createsuperuser
```

3. Start server

```sh
poetry run honcho start
```

Enjoy!
