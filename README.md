# My FLASK Training

I am learning flask using Miguel Grinberg's Mega Tutorial. This project is what I have built while going through the tutorial.

https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

## quick start (existing virtual environment)

1. to start virtual environment:

```bash
source venv/bin/activate
```

2. Start flask dev server:

```python
flask run
```

3. Access http://localhost:5000/ in the browser

## New venv setup

### create virtual environment

```bash
  $ python -m venv venv
```

### Use venv

- windows:

```bash
venv\Scripts\activate
```

- not windows:

```bash
source venv/bin/activate
```

## venv package installations with pip

Within the virtual environment, run the following command to install packages.

```python
  pip install < package name >
```

### required packages
flask, python-dotenv, flask-wtf, flask-sqlalchemy, flask-migrate, flask-login

```python
  pip install flask
  pip install python-dotenv
  pip install flask-wtf
  pip install flask-sqlalchemy
  pip install flask-migrate
  pip install flask-login
```
### Flask env variables

create file .flaskenv in project directory

add `FLASK_APP=microblog.py`