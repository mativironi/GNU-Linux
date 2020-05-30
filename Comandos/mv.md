# MOVE
* **Nombre:** _mv - move_
* **Sintaxis:** 
	* mv  _[opciones] [fichero/directorio viejo] [fichero/directorio nuevo]_
	* mv _[opciones] [fichero/directorio origen] [fichero/directorio destino]_
* **Descripcion:** _Renombra archivos/directorios y mueve archivos/directorios de un lugar a otro._

||Opciones mas importantes| 
| --------- | --------- |
| -f|No pregunta nunca antes de sobreescribir.| 
| -i|Pide confirmación antes de sobreescribir.|
| -b|Crea una copia de seguridad antes de borrar.|
| --help|Ayuda.|

* **Ejemplos**

```mv fi-viejo.txt fi-nuevo.txt``` Renombra el fichero.

```mv olddirectory newdirectory``` Renombra el directorio.

```mv fi-nuevo.txt newdirectory/``` Mueve el fichero **fi-nuevo.txt** al directorio **newdirecory**

```mv fi-nuevo.txt ../``` Mueve el fichero **fi-nuevo.txt** al _directorio padre_ del directorio actual. (Ruta relativa)

```mv viejo.txt folder4/nuevo.txt``` Mueve el fichero **viejo.txt** al directorio **folder4** y renombra el fichero a **nuevo.txt** 

```mv folder4 folder1/``` Mueve el directorio **folder4** y lo pega dentro del directorio **folder1** 

> Mover es copiar y después borrar el original. Es como _Cortar y Pegar_

> **mv** no modifica el propietario ni el grupo.

> Se pueden utilizar rutas absolutas y relativas.
