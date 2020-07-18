# SU
* **Nombre:** _su -  Switch User_
* **Sintaxis:** su  _[opciones] [ - ] [ usuario [ argumento...]]_
* **Descripcion:** _ejecuta un comando con un ID de usuario y grupo sustituto._

||Opciones mas importantes| 
| --------- | --------- |
| -c|Pasar el _comando_ al shell con la opción **-c**| 
| -l|Inicie el shell como un shell de inicio de sesión con un entorno similar a un inicio de sesión real.|
| -s|Ejecuta el shell especificado en lugar del predeterminado.| 
| --help|Ayuda.|

* **Ejemplos**

```su toto```  Se encuentra bajo el usuario "**toto**", sigue en la misma carpeta de trabajo que antes y beneficia de la conflagración del usuario de antes (shell, permisiones diversas...)

```su - toto``` El "**-**" fuerza el inicio de un nuevo shell de conexión, con las preferencias por defecto del usuario **toto**.

```su - ``` Es aconsejable de conectarse como "Super User" "**root**", usando este comando.

> Cuando se ejecuta, _su_ pide la contraseña de la cuenta a la se quiere acceder, y si es aceptada, da acceso a dicha cuenta. Al no poner un usuario, se accede como administrador. Sin embargo, también es posible pasar como parámetro otro nombre de usuario.
> Una vez introducida la contraseña, podemos ejecutar los comandos como si fuésemos el otro usuario. Al escribir **exit**, volvemos a nuestro usuario.

>Una variante muy utilizada es usar _su_ seguido de un guión. Así, para loguearte como root, tenés que ingresar _su –_ y para loguearte como otro usuario _su – otrousuario_.

>El **su** (Switch User) sirve para cambiar el usuario corriente o invocar el superusuario. El comando **sudo** no tiene la función de cambiar de usuario. Su trabajo es permitir que un usuario común pueda ejecutar algún comando con permisos elevados, sin la necesidad de cambiar de identidad.  
