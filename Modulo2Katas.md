Amy Malavar

# Ejercicio - Crear un paquete

En este ejercicio, aprenderás a utilizar entornos virtuales como una forma para no afectar a los paquetes instalados globalmente u otros programas que se ejecutan en tu máquina.

*Para este ejercicio es necesario que lo ejecutes desde la terminal, línea de comandos, cmd, consola, cli, etc. de tu computadora, sé que es desafíante, pero no te preocupes ¡¡Sé que puedes lograrlo!!*

## Crear un entorno virtual

Crea un entorno virtual mediante ``venv``

* Entro en mi terminal para crear mi entorno virtual y ejecuto:

       python3 -m venv env 

* Para activar mi entorno virtual

    source env/bin/activate


* Veo las bibliotecas que puedo instalar en mi entorno:

    pip freeze

* Con 'pip install...' instalo una bilbioteca en mi entorno virtual:
   
   pip install python-dateutil

* Al terminar su instalacion, me notifica con un mensaje de exito.

* Con 'pip freeze' veo mi lista de bibliotecas.

* Con deactivate' desactivo mi entorno virtual