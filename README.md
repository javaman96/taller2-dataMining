# taller2-dataMining
## Pasos para crear un ambiente de proyecto desde cero

+ Paso 1: $ virtualenv amb (nombre del ambiente)
+ Paso 2: $ virtualenv -p /usr/bin/python3 amb
+ Paso 3: $ source amb/bin/activate
+ Paso 4: $ pip3 install <package> (repetir para instalar varios <packages>)
+ Paso 5: $ pip3 freeze > requirements.txt


## Pasos para correr el proyecto existente en un repositorio (debe existir el archivo con el ambiente amb)

+ Paso 1: $ source amb/bin/activate
+ Paso 2: $ pip3 install -r requirements.txt


## Pasos para instalar paquetes nuevos

+ Paso 1: $ pip3 install <package> (repetir para instalar varios <packages>)
+ Paso 2: $ pip3 freeze < requirements.txt
