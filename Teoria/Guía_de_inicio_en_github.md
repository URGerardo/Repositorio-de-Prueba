# ¿Qué es GitHub?
Github se trata de un software el cual podemos utilizar para almacenar archivos de diversa índole, regularmente piezas de código o archivos de programa. Este entorno tiene como particularidad la capacidad de permitir a múltiples usuarios poder colaborar en un proyecto en común publicando archivos que pueden ser manipulados por todos aquellos miembros que formen parte de un proyecto.

# Comandos de utilidad

Estos son algunos comandos de suma utilidad:

* mkdir (nombreDeCarpeta): Nos permitirá crear carpetas dentro de nuestro repositorio, dentro de la rama en donde nos encontremos.

* echo "ContenidoEntreComillas" > NombreDelArchivo.extension : Nos permite crear un archivo con un contenido dentro de la carpeta o rama que seleccionemos.

* cd (nombreDelDirectorio) : Nos permite movernos entre carpetas.

* cd . . : Nos permite retroceder al directorio anterior respecto en donde nos encontremos posicionados.

## Comandos propios de GitHub
Dentro del repositorio tendremos diferentes comandos que nos permitirán interactuar de manera remota desde Visual Studio Code, siendo los más recurrentes los siguientes:

*   git branch (nombreDeRama): Nos permitirá crear una nueva rama dentro del repositorio.

* git rm -r NombreCarpeta: Nos permitirá eliminar una carpeta que se encuentre dentro de una rama, incluyendo todos los archivos que la misma pueda contener.

* git status : Nos permitirá saber en qué situación nos encontramos dentro del repositorio, informándonos sobre los cambios que hemos realizado.

* git commit -m "DescripciónEntreComillas" : Nos permitirá agregar un mensaje donde se explique brevemente los cambios realizados.

* git push origin (nombreDeLaRamaDestino) : Nos permite enviar los cambios realizados a nuestro repositorio Online, de manera que todo lo que hayamos borrado, modificado o anidado se subirá a nuestro repositorio.

* git pull : Nos permitirá actualizar nuestro repositorio local. Es necesario realizarlo luego de cada cambio para mantener actualizado nuestro repositorio clonado en nuestro equipo local.

* git add (nombreArchivo) : Nos permite añadir archivos o modificaciones que hayamos realizado. Este comando ha de ser utilizado antes de realizar un commit.

* git push origin --delete (nombreDeRama) : Nos permitirá borrar una rama de nuestro repositorio y al mismo tiempo publicar los cambios al repositorio Online

* git mv NombreArchivo(oCarpeta) NombreArchivo(oCarpeta): Permite modificar y renombrar un archivo o carpeta según nuestra necesidad. Es necesario realizar un commit luego de los cambios realizados, de manera que estos puedan verse en el repositorio Online.