# 05 · Conflictos y recuperación
**Objetivo:** recuperar cambios de forma consciente.

- `git restore --staged archivo`: quita el archivo de staging y conserva su edición.
- `git restore archivo`: descarta cambios locales no staged del archivo. Usalo solo si no los necesitás.
- `git revert SHA`: crea un nuevo commit que deshace el commit indicado; conserva el historial.
- `git merge --abort`: cancela un merge en conflicto; comenzá merges con el árbol limpio.

Un conflicto ocurre cuando Git no puede combinar cambios automáticamente. Abrí el archivo, elegí el texto final, eliminá las marcas `<<<<<<<`, `=======` y `>>>>>>>`, agregá el archivo y terminá con `git commit`.

VS Code muestra controles para resolver conflictos o un editor de merge. Revisá siempre el resultado completo.

**Práctica:** [Laboratorio aislado](../ejercicios/05-conflictos.md).
