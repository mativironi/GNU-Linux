# MKDIR
* **Nombre:** _mkdir - make directory_
* **Sintaxis:** mkdir  _[opciones] dir1 [dir2 dir3 ... dirn]_
* **Descripcion:** _Crea uno o mas directorios._

||Opciones mas importantes| 
| :---------: | --------- |
| -p|Permite crear una cadena de directorios completa.| 
| -m|Permite especificar los permisos del nuevo directorio. (Ver comando chown).|
| --help|Ayuda.| 

* **Ejemplos**

```mkdir direc1``` Crea un directorio direc1 en el directorio actual.

```mkdir direc1 direc2 direc3``` Crea tres directorios en el directorio actual.

```mkdir Documents/Direc1``` Crea un directorio Direc1 dentro de otro que ya existe (Ruta Relativa).

```mkdir /home/pi/Documents/Direc2``` Crea un directorio Direc2 dentro de otro que ya existe (Ruta Absoluta).

```mkdir -p FoTos/Camara``` Crea un directorio Camara y un directorio FoTos.

```mkdir -m 755 DirecPerm``` Crea un directorio DirecPerm con permisos 755.

>mkdir -m [Permisos en octal] [Nombre del nuevo directorio].
