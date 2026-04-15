## Gitflow: Metodología que utiliza varias ramas.
##	Estructura:
## main: Producción
## develop: desarrollo
## feature: nuevas funcionalidades
## release: preparación de versión
## hotfix: arreglos urgentes
## Ventajas:
## Muy ordenado
## Ideal para proyectos grandes
## versión clara
##		Desventajas
## complejo
## lento
# muchas ramas generan conflicto

## Trunk Based Development: Todos trabajan sobre una sola rama.
##	Ventajas:
## Mucho más rápido
## menos conflicto
## facilita integración
## Desventajas
## Requiere disciplina
## el código se debe mantener estable

## ¿Qué es GIT?
## Es una herramienta que guarda el historial de cambios de un proyecto. Cambia varios cambios de un archivo. 

## Repositorio: Carpeta del proyecto.
## Commit: Guardar cambio, más un comentario
## Branch: Copia del proyecto para trabajar sin afectar el original.
## Merge: Unir cambios de distintas ramas.


## Comandos básicos

## git init: Iniciar git dentro del proyecto.
## git add . : Es el paso previo a guardar, antes de un commit tenemos que ejecutar esto.
## git  commit -m “mensaje” : Es para documentar en el proyecto.
## git status: Para ver el estado del proyecto.
## git  log: Cuantos commit hemos hecho en el proyecto.
## git  log - - oneline: Hace lo mismo que el Log más ordenado.
## git branch –m main: Creamos la rama principal del proyecto.
## git remote add origin <URL del repositorio creado>:  Agregamos el repositorio hecho.
## git push -u origin main: Enviamos el proyecto a nuestro nuevo repositorio.
## git branch <NombreNuevaRama>: Creación de una nueva rama
## git checkout <NombreRama>: Nos cambiamos a la nueva rama
## git add <Nombre-de-Archivos>: Agregamos un archivo para el commit.
## pull request: Botón de Github


