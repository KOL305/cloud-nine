# Cloud Nine
Description:
- Web-based sleep cycle tracker and sleep helper created for the TeenTechSF 2022 Hackathon (Finalist)

Pre-requisites:
- MongoDB Account
- Git Installed
- Pip Installed


How to import app:
- Open up terminal
- Go to the chosen directory where you want the project located
- Enter in terminal: git clone https://github.com/KOL305/Cloud_Nine
- Open up your project in a code editor


How to set up virtural environment (in code editor):
- Enter in terminal: (Windows) python -m venv venv, (Mac) python3 -m venv venv
- Enter in terminal: (Windows) venv/Scripts/activate, (Mac). venv/bin/activate
- Make sure that your code editor has selected the venv python interpreter


How to set up .env (in code editor):
- create a file called .env
- Copy and paste the following into .env:

DEBUG = True
TESTING = False
CSRF_ENABLED = True
SESSION_COOKIE_SECURE = True
SESSION_COOKIE_HTTPONLY = True
SESSION_COOKIE_SAMESITE = 'None'
SESSION_TYPE='mongodb'
SESSION_TIME=30
PERMANENT_SESSION_LIFETIME = timedelta(minutes=30)
MONGO_URI=<<Add your mongodb url here>>
ENV = "development"
DOMAIN='http://127.0.0.1:5000'
SECRET_KEY=<<Add your secret key  here>>
SECURITY_PASSWORD_SALT=<<Add your password salt here>>


How to install requirements:
- Enter in terminal: pip install -r requirements.txt


To run app:
- Enter in terminal: (Windows) python app.py, (Mac) python3 app.py
