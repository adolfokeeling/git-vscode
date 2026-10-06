# Cómo trabajar en este repositorio

1. Desde `main`, ejecutá `git pull --ff-only` con el árbol de trabajo limpio.
2. Creá una rama descriptiva: `git switch -c practica/nombre-del-ejercicio`.
3. Editá y revisá `git status` y `git diff`.
4. Agregá archivos específicos con `git add ruta/del/archivo`.
5. Revisá `git diff --staged` y creá un commit que explique el cambio.
6. Publicá con `git push -u origin practica/nombre-del-ejercicio`.
7. Abrí un pull request hacia `main` y describí cómo comprobaste el resultado.
8. Después de fusionarlo en GitHub: `git switch main` y `git pull --ff-only`.

Los ejercicios de merge local y recuperación son excepciones didácticas: seguí sus instrucciones. Evitá force push y comandos que descarten cambios que todavía necesitás.
