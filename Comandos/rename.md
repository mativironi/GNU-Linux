# RENAME
* **Nombre:** _rename_
* **Sintaxis:**  rename  _[opciones] 's/old/new/' ficheros_
* **Descripcion:** _Cambiar el nombre del archivo_

||Opciones mas importantes| 
| :---------: | --------- |
| -v|Muestra los archivos que fueron renombrados, si los hay.| 
| -i|Pregunte antes de sobrescribir archivos existentes.|
| --help|Ayuda.|

* **Ejemplos**

```rename 's/tex/txt/' *.tex``` Cambia la extension de todos los archivos **.tex** a **.txt** del directorio actual.

```rename -v 's/tex/txt/' *.tex``` Realiza lo mismo que el anterior con la diferencia que muestra los archivos que fueron renombrados.

```rename 's/viejo/nuevo' *.txt```  Reemplaza todas las apariciones de **viejo** con **nuevo**. Mantiene la extencion **.txt**

![Imagenes rename](https://github.com/mativironi/GNU-Linux/blob/master/Imagenes/rename.PNG?raw=true)

```rename 's/nuevo//' *.txt``` Eliminar parte del nombre de archivo.

![Imagenes rename1](https://github.com/mativironi/GNU-Linux/blob/master/Imagenes/rename1.PNG?raw=true)
>Con **mv** podemos renombrar un archivo o fichero. Con **rename** podemos renombrar multiples ficheros.

> La principal ventaja de **rename** respecto de **mv**, es que nos permite renombrar multiples ficheros de una forma mas sencilla.
 
> Rename no forma parte de una distribución estándar de Linux, por lo que deberá instalarla. En las distribuciones de Ubuntu y Debian, **rename** se instala de la siguiente manera: **sudo apt-get install rename**
