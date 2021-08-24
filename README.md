[![GitHub Actions](https://github.com/flask-extensions/Flask-SimpleLogin/workflows/Tests/badge.svg)](https://github.com/flask-extensions/Flask-SimpleLogin/actions/workflows/tests.yml)
[![PyPI](https://img.shields.io/pypi/v/flask_simplelogin.svg?style=flat-square)](https://pypi.org/project/flask_simplelogin/)
[![PyPI versions](https://img.shields.io/pypi/pyversions/flask_simplelogin.svg?style=flat-square)](https://pypi.org/project/flask_simplelogin/)
[![PyPI formats](https://img.shields.io/pypi/format/flask_simplelogin.svg?style=flat-square)](https://pypi.org/project/flask_simplelogin/)
[![Flask](https://img.shields.io/badge/Flask-Extension-blue.svg?style=flat-square)](https://github.com/pallets/flask)
[![Documentation](https://readthedocs.org/projects/flask-simple-login/badge/?version=latest)](https://flask-simple-login.readthedocs.io/en/latest/?badge=latest)

# Login Extension for Flask

The simplest way to add login to flask!

## How it works

First install it from [PyPI](https://pypi.org/project/flask_simplelogin/).

> `pip install flask_simplelogin`

```python
from flask import Flask
from flask_simplelogin import SimpleLogin

app = Flask(__name__)
SimpleLogin(app)
```

## **That's it!**

Now you have `/login` and `/logout` routes in your application.

The username defaults to `admin` and the password defaults to `secret` (yeah that's not clever, let's see how to change it)

![Login Screen](/login_screen.png)

Check the [documentation](https://flask-simple-login.readthedocs.io/en/latest/?badge=latest) for more details!
