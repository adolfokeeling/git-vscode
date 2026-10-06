# Comandos de consulta rápida
Ejecutalos desde la carpeta del repositorio.

| Comando | Uso |
| --- | --- |
| `git status` | Estado del trabajo y staging. |
| `git diff` | Cambios aún no staged. |
| `git diff --staged` | Contenido del próximo commit. |
| `git add ruta` | Preparar un archivo. |
| `git commit -m "mensaje"` | Guardar una versión local. |
| `git log --oneline --graph --all` | Ver historial y ramas. |
| `git switch -c nombre` | Crear una rama y cambiar a ella. |
| `git switch main` | Volver a main. |
| `git merge nombre` | Integrar nombre en la rama actual. |
| `git remote -v` | Mostrar remotos. |
| `git fetch origin` | Obtener referencias remotas. |
| `git pull --ff-only` | Sincronizar sin crear un merge; falla si hay divergencia. |
| `git push -u origin nombre` | Publicar y establecer seguimiento. |
| `git restore --staged ruta` | Quitar de staging sin borrar la edición. |
| `git revert SHA` | Deshacer un commit mediante un nuevo commit. |

Antes de recuperar cambios, consultá el módulo 05. No copies comandos sin entender qué archivos o ramas afectan.
