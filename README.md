# Yumroad

Yumroad is a scaffold for starting new Flask applications. It takes care of the boilerplate code (like User Registration, OAuth, Teams, and Billing), allowing you to focus on building your application. Yumroad is built upon best practices for modern Flask applications.

## Setup

Usage of Python 3 is required. It can be installed [on Python.org](https://www.python.org/downloads/)

```
# Optional but recommended:
python3 -m venv env; source env/bin/activate

pip install -r requirements.txt
./manage.py server # or `FLASK_APP=manage FLASK_ENV=development flask run`
```

## Development

```
# Development
# If using a virtual env: source env/bin/activate
./manage.py resetdb # to seed data
FLASK_APP=manage FLASK_ENV=development flask run

# Go to localhost:5000 in a browser and click on Login
# Login with the following credentials "user@example.com", "test

# Production documentation in the repository.
```

## Testing

Github Actions is configured to run tests and produce code coverage metrics.

To run tests locally, try this command:

```
APPNAME_ENV=test ./manage.py test --coverage


# Screenshots
![image](https://github.com/user-attachments/assets/adaacea0-c946-4b2a-a7bb-5a88cfebb9af)
![image](https://github.com/user-attachments/assets/1cd0ac08-db69-4459-92b8-88cb6539560b)
![image](https://github.com/user-attachments/assets/2484ea50-6520-481f-9ca6-ab5d9262df54)
![image](https://github.com/user-attachments/assets/f0a03e7b-c60a-454e-9ff9-f5321b36c680)
![image](https://github.com/user-attachments/assets/27f4eb58-f634-48d1-84da-57fe0b1bbe43)
![image](https://github.com/user-attachments/assets/83a74343-9bbb-4790-89ab-33509d591989)









