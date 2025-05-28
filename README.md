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
```

# Screenshots
![image](https://github.com/user-attachments/assets/9c0eb27a-06b0-402a-a46a-924033378c8c)
![image](https://github.com/user-attachments/assets/3c53be1d-445c-4ca3-831b-dae930055458)
![image](https://github.com/user-attachments/assets/c75f210c-946a-44bf-b47b-92728a1a0608)
![image](https://github.com/user-attachments/assets/ab3cd036-5172-45cb-a309-9451d931dfaf)











