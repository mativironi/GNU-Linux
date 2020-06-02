# RMDIR
* **Nombre:** _rmdir - remove directory._
* **Sintaxis:** rmdir  _[opciones] dir1 [dir2 dir3 ... dirN]_
* **Descripcion:** _Borra uno o más directorios vacios._

||Opciones mas importantes| 
| :---------: | --------- |
| -p|Permite borrar una cadena de directorios completa, siempre que los directorios estén vacíos.| 
| --help|Ayuda.|
 

* **Ejemplos**

```rmdir direc1``` Elimina el directorio direc1 que se encuentra vacio dentro del directorio actual.

```rmdir direc1 direc2``` Elimina 2 directorios que se encuentran vacios en el directorio actual.

```rmdir Documents/Direc1``` Elimina el directorio Direc1 dentro de otro que ya existe (Ruta Relativa).

```rmdir /home/pi/Documents/Direc2``` Elimina el directorio Direc2 dentro de otro que ya existe (Ruta Absoluta).

```rmdir -p Nuevo/Nuevo1/Nuevo2``` Elimina el directorio Nuevo2 y sus antepasados (Nuevo y Nuevo1) mientras todos se encuentren vacios.

>Recordar que rmdir borra directorios/carpetas, siempre y cuando esten vacias.
