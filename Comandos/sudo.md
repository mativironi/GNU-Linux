# SUDO
* **Nombre:** _sudo - Super User Do_
* **Sintaxis:** sudo  _[opciones]_
* **Descripcion:** _Ejecuta un comando como otro usuario._

||Opciones mas importantes| 
| --------- | --------- |
| -u|Indica el usuario con el que se ejecuta el comando, por defecto root| 
| -g|Indica el grupo con el que se ejecuta el comando| 
| -k|Invalida la sesion de sudo, los 15 min se cancelaran y se cerrara sesion|
| -v|Extiende la sesion 5 min mas.|
| -i|Indica los permisos que tiene el usuario actual con sudo, se puede usar con -u| 
| --help|Ayuda.|

* **Ejemplos**

```sudo``` Pregunta por la contraseña del usuario que ejecuta el comando y listo.

```sudo -u [usuario]``` Ejecutar comandos de otros usuarios del sistema.

>Por defecto la sesion de sudo dura 15min.
