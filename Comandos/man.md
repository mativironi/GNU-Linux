# MAN
* **Nombre:** _man - manual_
* **Sintaxis:**  man  _[opciones] [comando]_
* **Descripcion:** _Interfaz  que ofrece ayuda sobre muchos comandos._

||Opciones mas importantes| 
| :---------: | --------- |
|-k|Busca las descripciones breves y los nombres de las páginas del manual con una palabra clave.| 
|-f|Nos enseña una descripción breve del comando indicado.|
|-w|Localiza el fichero del manual.|
|-a|Muestra todas las páginas del manual.|
|--help|Ayuda.|

* **Ejemplos**

```man ls``` Manual del comando **ls**

```man -f find ``` Muestra una descripción breve del comando **find**

```man -k list ``` Usamos una palabra clave como **list** para buscar nuestro comando, en este caso **ls**

```man -w free ``` Localiza la ubicacion del fichero de comando **free** y la imprime en pantalla.

```man -a ls``` Me muestra el manual completo.

```man 7 man``` Mauestra la seccion 7 del manual del comando **man**


> Brinda mas informacion que la opcion **--help** y ademas siguen un formato prácticamente estándar, lo que ayuda a navegar por estos con mucha simpleza.

> En ocasiones el mismo programa posee diversas secciones de manual.

> El manual construye su interfaz en bloques bien definidos y ordenados de forma prácticamente.
>1. **NOMBRE:** El nombre del comando y una frase de una línea que enuncie su propósito.
>2. **SINOPSIS:** Una lista de las opciones y argumentos que toma el comando y sus parámetros, o la función.
>3. **DESCRIPCIÓN:** Una descripción más detallada del propósito y mecanismos del comando o función.
>4. **OPCIONES:** Descripciones de cada una de las opciones que toma el comando y que hacen.
>5. **FICHEROS:** Directorios de ficheros relacionados con el comando o función (archivos de configuración, bases de datos, etc).
>6. **VÉASE TAMBIÉN:** Una lista de comandos o funciones relacionadas.
>7. **BUGS:** Problemas del comando o función que están pendientes de ser resueltos. También conocido como BUGS.
>8. **AUTOR:** Información sobre el programa, su pasado, sus términos de uso, y su/s creador/es.
