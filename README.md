# Gestion de la configuracion
----
# Proyecto calculadora
Aquí tienes el paso a paso que debes seguir para clonar el repositorio de GitHub, así podrás ejecutar y probar la calculadora en tu maquina.

1. Lo primero que debes tener es contar con una version de windows 11 instalada en tu dispositivo.

###Verificacion y/o instalación de nodeJS
Ahora vamos a verificar si el paquete Node.js está instalado en nuestro sistema.

En tu PC o Laptop presiona las siguientes teclas: La tecla Windows + R, al presionar esas teclas te aparecerá una ventana en la parte inferior izquierda de tu pantalla, ahí escribe el comando `cmd` y presiona enter, te aparecerá la terminal.

Ya en la terminal ejecuta el comando `node -v`, esto imprimirá la versión de Node.js instalada en tu computadora, si está instalado. Por ejemplo, verás algo como "v14.17.5" que es la versión de Node.js.

Si obtuviste una respuesta con la versión de Node.js, ¡ya está instalado! Si obtuviste un mensaje de error o no se imprimió nada, es probable que Node.js no esté instalado en tu sistema.

En caso de que no lo tengas instalado, puedes descargar Node.js desde el sitio oficial: https://nodejs.org/ . Después de descargarlo e instalarlo, repite los pasos anteriores para verificar que la instalación se haya realizado correctamente.

### Verificacion y/o instalación de git

Vamos a verificar si Git se encuentra instalado en tú máquina al igual que Node.js.

En tu PC o Laptop presiona las siguientes teclas: La tecla Windows + R, al presionar esas teclas te aparecerá una ventana en la parte inferior izquierda de tu pantalla, ahí escribe el comando `cmd` y presiona enter, te aparecerá la terminal.

Ya en la terminal ejecuta el comando `git --version`, esto imprimirá la versión de Git instalada en tu computadora, si está instalado. Por ejemplo, verás algo como "2.40.1.windows.1" que es la versión de Git.

Si obtuviste una respuesta con la versión de Git, ¡ya está instalado! Si obtuviste un mensaje de error o no se imprimió nada, es probable que Git no esté instalado en tu sistema.

Si no tienes Git instalado, puedes descargarlo desde el sitio oficial: https://git-scm.com/

Después de descargarlo e instalarlo, repite los pasos anteriores para verificar que la instalación se haya realizado correctamente.

###Clonación del repositorio

Lo primero que debes hacer es crear la carpeta en la cual vas a clonar el código fuente de la aplicación, esta la puedes crear en cualquier parte, pero lo más recomendable es hacerlo en el escritorio, la carpeta puede tener cualquier nombre.

Dentro de la carpeta haz click derecho, luego le das en "Mostrar más opciones" y por último click en "Abrir en terminal" o en "Git bash here".

Ya dentro de la terminal, ejecuta el siguiente comando:
`git clone https://github.com/JhonOlivares26/gestion-de-la-configuracion.git`

Una vez que el comando se complete, habrás clonado exitosamente el repositorio de GitHub en tu computadora.

###Moverse de rama
Ahora lo que debemos hacer es movernos de la rama por defecto "main" a la rama donde está el codigo de la aplicación. Para esto debemos entrar en la carpeta que se creó al clonar el repositorio, Dentro de la carpeta haz click derecho, luego le das en "Mostrar más opciones" y por último click en "Abrir en terminal" o en "Git bash here".

Ya en la terminal ejecutamos el comando `git checkout Jhon_Leyson_Olivares_Graciano`, 
de esta forma ya estaremos en rama que necesitamos. 

Para verificarlo puedes ejecutar el comando `git branch` y te deberá aparecer   
"* Jhon_Leyson_Olivares_Graciano"





