# Developing

* Create a virtual env

```
python3 -m venv venv
```

* Activate it

```
. venv/bin/activate
```

* pip now avaiable from venv:

```
$ which pip
/home/curtis/working/app-accelerator-flask-python/venv/bin/pip
```

* Install flask

```
pip install flask
```

* flask CLI now avilable from venv

```
$ which flask
/home/curtis/working/app-accelerator-flask-python/venv/bin/flask
```

* Run:

```
export FLASK_APP=hello
flask run
```