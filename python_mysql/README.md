# Desarrollo de API Rest PYTHON - MONGODB 



# Instalación Entorno Virtual

```bash
## Instalar biblioteca de entorno virtual
pip install virtualenv
## crear entorno virtual
virtualenv venv
## Activar entorno virtual
.\venv\Scripts\activate.bat
```

## Instalación de library
```bash
pip install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy pymysql

```

## Ejecución API

```bash
python src/app.py
```


## Ejecución MySQL 
```bash
# Abrir consola interactiva
mongo
# Mostrar DB
show dbs

use pythonmongodb

show collections
# Ver resultados
db.users.find().pretty() 
```