# Integrantes

David Barbosa Gómez

Juan José Díaz


# Respuestas

### Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”

El comando git add se utiliza para agregar los archivos modificados al área de preparación (staging area) de Git.

Modo de uso:

Para agregar uno o varios archivos
git add <Nombre de archivo> 

Para agregar todos los archivos
git add .


### ¿Que sucedió?

se genero un error de conflictos por los cambios realizados simultaneamente.


### ¿Hay una mejor forma de trabajar con git para no tener conflictos?

Las siguientes prácticas pueden ayudar a evitar conflictos en git.

* El uso correcto de git flow es una de las mejores prácticas para evitar conflictos.
* Realiza git pull frecuentemente para integrar cambios del repositorio remoto antes de trabajar.
* Coordinar con otros desarrolladores para evitar trabajar en las mismas partes del código.
* Hacer commits que incluyan solo los cambios relacionados con un único objetivo.
* Usar git rebase para aplicar los commits sobre la rama principal y mantener un historial más limpio.

### ¿Qué es y como funciona el Pull Request?

Un Pull Request es una solicitud para que los cambios en una rama sean revisados y fusionados en otra.
El proceso es el siguiente:

* Abrir un pull request en la interfaz web del repositorio.
* Revisar el código preferiblemente ayudandose de otros miembros del equipo para revisar el código, dejar comentarios y solicitanr ajustes si es necesario.
* Resolución de comentarios y conflictos.
* Fusión (merge), una vez aprobado, el pull request se fusiona en la rama base.
  
  ## Cambios en rama de David 
