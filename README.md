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
![image](https://github.com/user-attachments/assets/5e139c83-5962-4733-bfee-d0e2533260e8)
![image](https://github.com/user-attachments/assets/7c45412a-9af8-4dd6-b6f0-45e2e69cd6bd)
![image](https://github.com/user-attachments/assets/1870f479-9153-452f-8461-d5c445f363cf)
![image](https://github.com/user-attachments/assets/a12f90f7-cfeb-486e-b47b-27a55f43068f)
![image](https://github.com/user-attachments/assets/80fe09d9-dab8-4ce1-9aae-434dfbf17a2f)
![image](https://github.com/user-attachments/assets/3149fe5f-ce7c-483e-8427-ad2f04894e68)










