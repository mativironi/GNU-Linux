# LS
* **Nombre:** _ls - list_
* **Sintaxis:** ls _[-opciones]_ _[directorio|archivo]_
* **Descripcion:** _Muestra el contenido de un directorio_

||Opciones mas importantes| 
| --------- | --------- |
| -l|Información completa de los archivos| 
| -a|Muestra toda la información, incluyendo las ocultas|
| -x|Lista en columnas, ordenamiento horizontal|
| -C|Lista en columnas, ordenamiento vertical|
| -R|Lista directorios en forma recursiva|
| -r|Ordena listados en forma inversa|
| -t|Ordena el listado por fecha de última modificacion|
| -u|Ordena el listado por fecha de último acceso|
| -c|Ordena el listado por fecha de último cambio de estado.|
| -i|Ordena listados en forma inversa|
| -S|Ordenar por tamaño de archivo, el más grande primero (SORT)|
| -h|Legible por humanos|
| --help|Ayuda.| 

* **Ejemplos**

```ls``` o ```ls .```Muestra el contenido del directorio actual.

```ls Documents``` Muestra el contenido del directorio Documents (Ruta relativa).

```ls /home/``` Muestra el contenido del directorio home (Ruta Absoluta).

```ls /home/ -l``` Muestra el contenido del directorio home y le agrega mas información.

```ls -lh ``` o ```ls -l -h``` Muestra todo el contenido del directorio actual por orden alfabetico y de forma legible para humanos.

```ls -lhS``` o ```ls -l -h -S``` Lista y ordena los archivos de mayor a menor tamaño.

```ls -lhSr``` o ```ls -l -h -S -r``` _Lista y ordena los archivos de menor a mayor tamaño.

>Los espacios, los utiliza el interprete para separar las partes de los comandos

>Ruta Absoluta: se basa en la raíz del árbol de Linux. Toda ruta absoluta empieza, por /.

>Ruta Relativa: dependen del directorio actual en el que se encuentra el usuario.
