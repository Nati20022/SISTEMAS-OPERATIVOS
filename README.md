# Bitacora de comandos de Sistemas Operativos
Este es un repositorio de comandos de Linux del curso de Sistemas operativos
| **COMANDO** | **DESCRIPCION** | **EJEMPLO DE USO** |
| --------| ----------- | -------------- |
| ps-aux | Muestra los procesos que pertenecen a un usuario  |-Muestra los procesos asociados a un usuario, mostrar los procesos asociados a un grupo de usuarios, procesos relacionados a la terminal actual o los procesos en ejecuccion |
| top  | Permite ver las tareas del sistema en tiempo real|-Procesos preparados para ejecutarse, el proceso no se esta ejecutando, mostrar procesos en ejecuccion detenida. |
| htop  |  Visor de procesos, es similar al top pero visual|-Ver el primer proceso ejecutandose o el ultimo, rastreo de llamadas al sistema, ordenar procesos por consumo de memoria, ordenar por consumo de procesador, ordenar procesos por tiempo, marcar un proceso y seguirlo, matar un proceso ocultar los procesos. |
| pstree | Muestra de manera de arbol los procesos en ejecucion| -Para ver la lista de argumentos, mostrar el PID para cada proceso, visualizar el propietario de cada proceso, ordenar las salidas por PID.|
| man | Paginas de manual, es una herramienta para ver la documentacion sobre comandos, archivos,etc|-Obtener breve descripcion de un comando (mand -f find), buscar manual por clave, localizar ficheros |
| sudo su | Permite ejecutar programas con privilegios de otro usuario de manera temporal (generalmente root)|-Instalacion de paquetes priviligeado, correr codigod de python3 |
| whoami | Imprime el nombre de usuario actual| -Saber que usuario esta logeado despues de usar el comando su|
| more | Permite ver pero no editar el condenido de un archivo o comando| -Cambiar el mensaje, comprimir lineas, especificar tamaño de la pantalla, mostrar cierta linea de texto|
| tail-n| Para visualizar las ultima 10 lineas de un fichero|-Se puede cambiar el numero para ver mas lineas tail -20 |
| head -n | Para visualizar las primeras 10 lineas de un fichero| -Se puede cambiar el numero para ver mas lineas head -20|
| cp | Permite copiar un archivo o carpeta|-Copiar archivos o carpetas de gran tamaño o de manera mas rapida |
| alias | Indica que reemplace una cadena por otra|-Para eliminar un alias, personalizar el terminal |
| mv| Mover/renombrar archivos o directorios del sistema de archivos| |
| rm | Elimina archivos y directorios|-Ejemplo al eliminar un archivo que este corrupto de manera segura |
| useradd| Creacion de usuarios| -Crear cuenta de usuario, asignar contraseña, crear cuenta de usuario en otro directorio, incluir cuenta en grupos, crear cuenta de usuario sin carpeta personal|
| passwd | Cambia la contraseña del usuario|-Cambiar la contraseña de un usuario que se desconoce la contraseña actual |
| less| Muestra el texto en la pantalla|-Mostrar cambios realizados, directorios, leer un archivo |
| history | Buscar los ultimos comandos que se han ejecutado|-Cambiar un comando, limpiar el historial, ver numero determinado de linea |
| sudo apt install| Instalar paquetes|-Instalar paquetes especificos |
| dir/mkdir | Copiar directorios| -Crear una carpeta dentro del nivel de la terminal, crear directorio en una ruta|
| ip addr |Muestra la direccion IP y la informacion de las interfaces de red|-Ver informacion ethernet, activar o desactivar una interfaz de red, asignar una ip, eliminar una ip, agregar alias, comprobar la puerta de enlace, agregar ruta estatica o eliminarla |
| df -hT |Cual sistema de archivos tiene el sistema operativo|
