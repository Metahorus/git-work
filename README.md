# git-work — Repositorio colaborativo Git

Descripción: repositorio de práctica del flujo colaborativo (fork, issue, rama, PR, conflicto, etiqueta y release).

## Índice

- [Entorno e instalación](#entorno-e-instalacion)
- [Configuración](#configuracion)
- [Comprobación](#comprobacion)
- [Problemas encontrados y solución](#problemas-encontrados-y-solucion)
- [Repositorio remoto](#repositorio-remoto)

## Entorno e instalación
Herramientas usadas y pasos para clonar y abrir la página (index.html).

## Configuración
Qué ficheros se han tocado y por qué (líneas 10 y 11 de css/cover.css).

## Comprobación
Comandos ejecutados y su salida (git log, git remote -v, git tag...).

## Problemas encontrados y solución
Tabla problema | causa | solución (incluye el conflicto de fusión).
---------------|-------|------------------------------------------
En el workflow no se detecta el index.html | Para MkDocs, todo el contenido procesable está dentro de la carpeta docs/ | Se usa una ruta absoluta para ver si encuentra el archivo.
Error al en commit de user2 personalizado, se copia el commit de la documentacion y el commit se realiza sin problema | Se estaba añadiendo un espacio luego de la barra '\' que separaba los mensajes, lo que hacía que se no se entendieran como dos mensajes. | Se hizo otro commit a posteriori prestando atención a no dejar espacio luego de la barra. 


## Repositorio remoto
Enlace público: https://github.com/Oscar-PF/git-work
Pull request principal: https://github.com/TU_USUARIO/git-work/pull/1