## Rubén Dario Ceballos A00054636
# so-workshop1

### Desarrollo

1. Explique la función de los directorios en la raíz de sistema operativo Linux-CentOS.
Proporcione ejemplos de los archivos que se encuentran en cada directorio (explique al menos un
archivo por directorio).

| Directorio   | Archivo ejemplo | Descripción del contenido del directorio  |
|------|------|------|
| bin | pwd; permite saber la dirección actual del puntero | Directorio que contiene los archivos ejecutables del sistema, tanto de administrador como de usuarios |
| dev | mouse; driver el mouse | Directorio de dispositivos a los que linux puedea acceder |
| home | usuario; archivo con las configuraciones básicas para iniciar con usuario | Residen todas las cuentas de usuarios |
| lib64 | an example file | Librerias que trabajan a x64 bits |
| mnt | cdrom; archivo necesario para lectura de cd | Punto de montaje para sistemas de archivos montados temporalmente |
| tmp | yum.log; contiene el historial del comando yum | Contiene los archivos temporales del sistema |
| var | log; historial de comandos de los usuarios | Archivos que cambian con el tiempo, sea por reescritura o modificaciones del sistema |
| boot | initramfs-3.10.0-514.e18.x86_64.img; imagen usada temporalmente mientras se inicia el sistema | Contiene los elementos necesarios para el arranque del sistema |
| etc | passwd; contraseñas del sistema | Archivos de configuración de los demonios |
| lib | sendmail; biblioteca con los archivos y protocolos necesarios para email básico | Directorio residen todas las bibliotecas compartidas requeridas por los comandos en el sistema raíz |
| root | anaconda-ks.cfg; modelo usado por redhat para las actualizaciones | Directorio que contiene todos los archivos del administrador |
| sbin | lvm; ejecutable que administra volúmenes lógicos | Archivos ejecutables usados por el administrador |
| sys | an example file | an awesome description |
| usr | bin; ejecutables de uso común para los usuarios | Contiene todos los ejectuables, archivos y librerias para el uso común de los usuarios |

2. En una tabla como se muestra a continuación escriba 10 comandos de Linux no visto en clase. Puede incluir comandos que funcionan una vez han sido instalados con yum

| Comando   | Usuario | Descripción |
|------|------|------|
| $ df -h | who call it | mostrar una lista de las particiones montadas |
| $ recode ..HTML < page.txt > page.html | who call it | convertir un fichero de texto en html |
| $ free -m | who call it | muestra el estado de la RAM en megabytes |
| $ last reboot | who call it | mostrar historial de reinicio |
| $ pkill -u operativos | who call it | Matar todos los procesos del usuario operativos |
| $ top | who call it | mostrar las tareas de linux usando la mayoría cpu |
| $ fsck /dev/hda1 | who call it | reparar / chequear la integridad del fichero del sistema Linux en el disco hda1 |
| $ tac file1 | who call it | ver los contenidos de un fichero comenzando desde la última línea |
| $ apt-get clean | who call it | limpiar cache desde los paquetes descargados |
| $ yum clean all | who call it | eliminar desde los paquetes caché y ficheros de encabezado |

## REFERENCIAS 
* https://github.com/ICESI/so-commands/tree/master/centos7
* https://www.comoinstalarlinux.com/comandos-ubuntu-mas-450-comandos-linux-deberias-conocer/#Espacio_de_Disco
* https://linuxreflejo.wordpress.com/2008/07/18/estructura-de-directorios/
