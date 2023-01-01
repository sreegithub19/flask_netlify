# flask_netlify

Reference: https://testdriven.io/blog/static-site-flask-and-netlify/

Steps:

- python3 -m venv venv
- source venv/bin/activate
- pip install Frozen-Flask
- pip freeze > requirements.txt
- pip install -r requirements.txt
- export FLASK_APP=app.py
- flask run
- python freeze.py
- git add . && git commit -m "c" && git push origin main
- deactivate
