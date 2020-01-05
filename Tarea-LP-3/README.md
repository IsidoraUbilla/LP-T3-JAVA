﻿
# Tarea 3 LP - StarterPack

##Integrantes:
* Daniel Pumarino, 201873608-2
* Isidora Ubilla Zavala , 201804581-0

### Contenido:

* **Clases**: Están creadas la mínima cantidad de clases necesarias para resolver el problema, estas deben ser editadas desde la carpeta **/src/Tarea3**.

* **makefile**: Archivo makefile listo para compilar con el comando **make**, los resultados de compilación se guardan en la carpeta del proyecto con el nombre Juego.jar

* **manifest.mf**: Archivo necesario para indicar la clase principal del proyecto.

### Instrucciones de Compilación y Ejecución:

1. Compilar con el comando **make**.
2. Ejecutar con el comando **java -jar Main.jar**

### Consideraciones del MAKEFILE:

* En caso de querer cambiar la carpeta del código, modificar la línea **9** del makefile, (javac -sourcepath **src/** -d build/classes **src/Tarea3/\***.java)

* El makefile trae también la instrucción **clean** para limpiar el las clases compiladas del proyecto que una vez obtenido el programa .jar, ya no sirven (en otras palabras, el comando **make clean** borra la carpeta **/build**).

* En la clase **Main** está declarado el método **main** del programa, el cual se ejecutará al momento de ejecutar el jar.

* Por defecto, el nombre del paquete es **tarea3**, para modificarlo hay que editarlo en todos los archivos **.java** y en el **manifest.mf** (línea 2, Main-Class: **tarea3**/Juego)

### Consideraciónes del código:

* En la clase Grafo se solicitaba el método **n addNode: recibe el identificador de un nuevo nodo.** Por la implementación de matriz utilizada este método no era necesario ni útil.




