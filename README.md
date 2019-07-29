# BootstrapFlaskBase

Este repo es una versión básica de una app básica Flask, a partir de un ejemplo de bootstrap. Con esto se puede iniciar nuevas aplicaciones.

[Link al ejemplo boostrap](https://getbootstrap.com/docs/4.0/examples/dashboard/)

Características:

 - Uso de flask para crear una app escuchando
 - Uso de templates 
 - Uso de elementos estáticos
 - Renderización de templates
 - Inclusión de templates
 - Uso de librería Python para generar charts en html
 - Uso bajo el marco de entornos virtuales

Para crear el entorno virtual se debe ingresar a la carpeta raíz y si no tienes instalado el módulo de entornos virtuales

     pip install virtualenv 

Luego hacer el entorno

     python -m venv nombre_del_entorno_que_uno_quiera

Dentro del entorno ingresar a la carpeta Scripts. Dentro de acá instalar las librerías mediante el ejecutable pip dentro del entorno.

Para generar generar la lista de las librerías y generar el archivo "requeriments.txt" 

    .\pip freeze > ../../src/requeriments.txt

