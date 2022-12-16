# idor-lab-django
This is a simple Django app to demonstrate a Insecure direct object reference (IDOR)

### Generate secret key
Run `python -c "import secrets; print(secrets.token_urlsafe())"`

Create a .env in the root directory and then paste like `SECRET_KEY = your_key`
