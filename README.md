# ARQUITECTURA FLASK CON IMPLEMENTACION DE BLUEPRINT
Proyecto base de Python

#CREAR ENTORNO VIRTUAL
python3 -m venv venv
. venv/bin/activate

#INSTALAR PROYECTO
pip install -e .

#CORRER EL PROYECTO

export FLASK_APP=flaskr
export FLASK_ENV=development
flask run


#INSTALAR PAQUETE PARA TEST
pip install pytest coverage

pytest
coverage run -m pytest
coverage html

