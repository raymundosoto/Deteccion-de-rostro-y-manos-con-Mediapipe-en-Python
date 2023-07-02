# Detección de rostro y de manos con python Mediapipe y OpenCv en linux (Ubuntu 22.04)

## Instrucciones de instalación

Se creará un ambiente virtual que contenga la versión de Python 3.10 donde se instalará Mediapipe y todas las bibliotecas auxiliares

Se crea una carpeta que contenga el proyecto usando la terminal de Linux en la carpeta de Documentos usando los siguientes comandos y oprimiendo `Enter` después de terminar de editar cada documento

`cd Documentos`

`mkdir proyecto_facial`

Cambiamos a la carpeta del proyecto

`cd proyecto_facial`

Actualizamos los repositorios de software de Ubuntu usando

`sudo apt-get update`

Actualizamos la lista de bibliotecas pip3

`python3 -m pip install --upgrade pip`

Instalamos el creador de ambientes virtuales de python

`sudo apt install python3-virtualenv`

Crear el ambiente virtual con el nombre __proyecto_fc__ con una versión de Python 3.10

`virtualenv -p python3 project_fc`

Activar el ambiente virtual para instalar nuestras librerías

`cd proyecto_fc`

`source bin/activate`

Con lo anterior ya estará activado el ambiente virtual y procedemos a instalar Mediapipe que a su vez instalará también OpenCv

`pip install mediapipe`

En un editor de código abrir el script que se encuentra en el repositorio de Github, activar el ambiente virtual con las bibliotecas instaladas para que funcione sin problemas.












