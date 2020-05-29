# RM
* **Nombre:** _rm - remove_
* **Sintaxis:** rm  _[opciones]  [ficheros o directorios]_
* **Descripcion:** _Borra archivos o directorios_

||Opciones mas importantes| 
| --------- | --------- |
| -r|Borra en forma recursiva todo el directorio indicado y los subdirectorios. ¡Tener cuidado!| 
| -d|Borra directorios vacios.|
| -i|Pregunta antes de cada borrado.|
| -I|Pregunta una vez antes de borrar más de tres ficheros,o cuando se borra recursivamente. i(mayuscula)|
| --help|Ayuda.|
 
* **Ejemplos**

```rm fichero1.txt``` Borra el fichero1.txt

```rm fichero1.txt fichero2.txt``` Borra 2 ficheros.

```rm -r directorio1``` Borra en forma recursiva todo el directorio1.

```rm -d directorio2``` Borra el directorio, si esta vacio.

```rm -i fichero2.txt``` Pregunta si queres borrar el archivo. s/n

```rm -d /home/pi/Desktop/directorio1/``` Borra directorio1 (Ruta Absoluta)
>Para eliminar directorios es necesario usar las opciones, de lo contrario no se pueden eliminar los mismos.

>Se pueden eliminar multiples ficheros y directorios.

>Realiza mas funciones que **rmdir**, por lo que es mas util.
