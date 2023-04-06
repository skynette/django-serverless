
# Django on Vercel

A Simple Starter Template which helps to Deploy a **Django Project on Vercel** as a **Serverless Function** .

This App is Configured with Postgres as the Choice of Database.

- [x] Configured with Static Files in Production.

- [x] Compatable with Postgres/MySQL DB.

  

## Get & Running on your Local Machine


- Clone the **Repo**

```sh

cd  ~/Dev/

mkdir django_vercel

cd  django_vercel

git clone  https://github.com/skynette/django-serverless.git  .

```

- Create a **Virtual Environment** for **Python**


```python

virtualenv --python=python3.9 .

source bin/activate

pip install -r requirements.txt

```

- Run Locally

```python

cd ~/Dev/django_vercel

python manage.py runserver
