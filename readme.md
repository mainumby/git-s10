# Git Desarrollo Colaborativo

Esto es una guía creado con la finalidad de facilitar el entenfimineto y aplicación de la herramineta conocida como GIT,
que se utiliza para el control de versiones de nuestros proyectos. Aquí veremos como configurar la misma, así como también cada una de sus opciones.

## Configuración Inicial

Cuando inicializamos un repositorio por primera vez, podemos establecer el nombre de usuario y correo aelectronico, para
identificarnos dentro dle historial de cambios. 

Cuando queremos definir una configuración de manera general, debemos utilizar el parámetro *--global* para indicar que dicha configuración debe almacenarse en la carpeta del usuario y no en la carpeta *.git/* del repositorio.

* **git init**: Inicializa un repositorio de git.
* **git config --global user. name** `username`:Define el nombre de usuario para el control de cambios. 
* **git config --global user.email** `email`: Establece el correo electrónico para las confirmaciones.

## Gestión del proyecto

Para sincronizar los cambios realizados en el proyecto, debemos tener en cuenta que si creamos en nuestra computadora el mismo utilizando el comando *git init*, vamos a tener que crearlo también en nuestro servidor remoto, como por ejemplo [GitHub](https://github.com).

En caso de que ya exista un repositorio remoto, simplemente debemos descargar el historial de cambios del mismo, pero indistintamente de como hayamos empezado, lo principal es estar pendiente de los cambios realizados en el servidor de GIT.