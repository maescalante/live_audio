# live_audio

Se necesitan importar las siguientes librerias para el
funcionamiento del proyecto.

En caso de que se este trabajando con una raspberry pi
siga los siguientes pasos.

1.Asegurese de tener instalado python y cree un ambiente
 virtual desde el cual se va a ejecutar el proyecto:
````
sudo apt update
sudo apt upgrade
sudo apt install python3.7
````
Para asegurarse de que la instalación se realizara de 
manera correcta ejecute:

````
python3 --version
````

A continuación se debe crear el ambiente virtual en el que
se instalaran las librerias necesarias para la ejecución 
del proyecto

````
 python3 -m pip install --upgrade pip
sudo pip3 install virtualenv
virtualenv -p python3 venv_problema
````
Para acceder al ambiente virtual:
````
source venv_problema/bin/activate
````
Dentro del ambiente ejecute los siguientes comandos:
````
pip install numpy
pip install pyaudio
pip install librosa
````