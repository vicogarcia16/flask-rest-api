# Blog REST API

Realizar un entorno virtual y ejecutar requirements.txt: 

- $ python3 -m virtualenv env
- $ env Scripts/activate.bat
- (env) $ pip install -r requirements.txt

Realizar lo siguiente para crear la base de datos y generar el modelo de tabla: 

- (env) $ python
- from main import db
- db.create_all()
- exit()
