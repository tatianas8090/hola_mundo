# Hola Mundo (FASTAPI)

Lo primero que se realizo fue crear el repositorio hola_mundo. 

Seguido de ello verificar que se tiene PIP instalado, PIP viene instalado con Python de forma predeterminada. 

Después se debe crear un entorno virtual y activarlo de la siguiente manera:

primero: python -m venv name(como desee llamar mi proyecto en mi caso fast)

segundo: source venv_name/Scripts/activate (GIT BASH - windows)

Para desactivar el entorno con el comando: deactivate.

despues de ello vamos  a instalar los paquetes de requisitos.txt con el comando: Requisitos de PIP Install -R.txt

Actualizamos el main.py creado inicialmente, luego con el comando py uvicorn main:app --reload este nos arroja el 
 
 http://127.0.0.1:8000

donde vamos a encontra hola mundo y la documentacion de las FastApi previamente importada.
