# Blog REST API

Realizar un entorno virtual y ejecutar requirements.txt: 

$ python -m venv env
$ source env/bin/activate
(env) $ pip install -r requirements.txt

Realizar lo siguiente para crear la base de datos y generar el modelo de tabla: 

(env) $ python
>>> from main import db
>>> db.create_all()
>>> exit()
