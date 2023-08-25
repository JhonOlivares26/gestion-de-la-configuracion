# Gestion de la configuracion
## Proyecto gestor de notas
Aquí tienes el paso a paso que debes seguir para clonar el repositorio de GitHub, instalar las dependencias y construir el build. Adicionalmente tendrás el paso a paso para ejecutar y probar el proyecto en un servidor web.

### Verificación del sistema operativo

Lo primero que debes tener es contar con una version de windows 11 instalada en tu dispositivo.

### Verificacion y/o instalación de nodeJS
Ahora vamos a verificar si el paquete Node.js está instalado en nuestro sistema.

- En tu PC o Laptop presiona las siguientes teclas: La tecla Windows + R, al presionar esas teclas te aparecerá una ventana en la parte inferior izquierda de tu pantalla, ahí escribe el comando `cmd` y presiona enter, te aparecerá la terminal.

- Ya en la terminal ejecuta el comando `node -v`, esto imprimirá la versión de Node.js instalada en tu computadora, si está instalado. Por ejemplo, verás algo como por ejemplo "v18.16.0" que es la versión de Node.js.

> Si obtuviste una respuesta con la versión de Node.js, ¡ya está instalado! Si obtuviste un mensaje de error o no se imprimió nada, es probable que Node.js no esté instalado en tu sistema.

En caso de que no lo tengas instalado, puedes descargar Node.js desde el sitio oficial: https://nodejs.org/ . Deberás descargar la versión LTS y continuar la instalación. Después de descargarlo e instalarlo, repite los pasos anteriores para verificar que la instalación se haya realizado correctamente.

- Ahora instalaremos el gestor de paquetes de NodeJS llamado npm con el comando `npm install -g npm`

### Verificacion y/o instalación de git

Vamos a verificar si Git se encuentra instalado en tú máquina al igual que Node.js.

- En tu PC o Laptop presiona las siguientes teclas: La tecla Windows + R, al presionar esas teclas te aparecerá una ventana en la parte inferior izquierda de tu pantalla, ahí escribe el comando `cmd` y presiona enter, te aparecerá la terminal.

- Ya en la terminal ejecuta el comando `git --version`, esto imprimirá la versión de Git instalada en tu computadora, si está instalado. Por ejemplo, verás algo como por ejemplo "2.40.1.windows.1" que es la versión de Git.

> Si obtuviste una respuesta con la versión de Git, ¡ya está instalado! Si obtuviste un mensaje de error o no se imprimió nada, es probable que Git no esté instalado en tu sistema.

- Si no tienes Git instalado, puedes descargarlo desde el sitio oficial: https://git-scm.com/download/win , debes elegir la versión para windows.

> Después de descargarlo e instalarlo, repite los pasos anteriores para verificar que la instalación se haya realizado correctamente.

### Clonación del repositorio

- Lo primero que debes hacer es crear la carpeta en la cual vas a clonar el código fuente de la aplicación, esta la puedes crear en cualquier parte, pero lo más recomendable es hacerlo en el escritorio, la carpeta puede tener cualquier nombre.

- Dentro de la carpeta haz click derecho, luego le das en "Mostrar más opciones" y por último click en "Abrir en terminal".

- Ya dentro de la terminal, ejecuta el siguiente comando:
`git clone https://github.com/JhonOlivares26/gestion-de-la-configuracion.git`

> Una vez que el comando se complete, habrás clonado exitosamente el repositorio de GitHub en tu computadora.

### Moverse de rama
Ahora lo que debemos hacer es movernos de la rama por defecto "main" a la rama donde está el codigo de la aplicación.

-Ya en la terminal nos movemos a la carpeta donde está el codigo fuente con el comando `cd gestion-de-la-configuracion`

- En la misma terminal ejecutamos el comando `git checkout Jhon_Leyson_Olivares_Graciano`, 
de esta forma ya estaremos en rama que necesitamos. 

> Para verificarlo puedes ejecutar el comando `git branch` y te deberá aparecer   
"* Jhon_Leyson_Olivares_Graciano"

### Instalar dependencias 
Lo que haremos ahora será instalar las dependencias de nuestro proyecto para que este funcione bien.

- Dentro de la misma terminal ejecutamos el comando `npm i` o `npm install`, para que se descargen las dependencias necesarias automaticamente.

### Crear el build
ahora lo que haremos será crear nuestro artefacto, para esto utilizaremos el framework generador de aplicaciones para NodeJS llamado "express".

- En la misma terminal ejecutamos `npm install -g express-generator`, el cual nos instalará globalmente el paquete de express.

> En caso de que express no descargue lo que haremos será ejecutar `npm cache clean --force` con el fin de limpiar de nuestra chaché para cubrir el caso no infrecuente en el que una entrada de caché esté dañada o es inconsistente y npm falla solo porque intenta ser mas eficiente. Ahora ejecutamos `npm doctor` el cual verificará los paquetes almacenados en caché e identificará los corruptos. Además para asegurarnos que tenemos la ultima versión de npm ejecutaremos `npm install -g npm` , cuando haya terminado la instalación de npm, volvemos a ejecutar el comando para instalar express y ya debería funcionar.

- Ahora ejecutamos `express build --view pug` el cual nos creará una carpeta build con el artefacto.

> Para poder asegurarnos de que la carpeta se creó correctamente podemos listar los elementos de la carpeta, ejecutando el comando `dir`, este lo que hará es listar todo lo que tengamos en esa carpeta. Ahí podremos ver que efectivamente tendremos una carpeta llamada "build" con la fecha y hora de su creación.

FIN.
