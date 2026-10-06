# Ejercicio 03 · Trabajar en una rama
**Requisito:** ejercicio 02, árbol limpio. **Tiempo:** 20 minutos.

1. `git switch -c practica/bitacora`.
2. Agregá a apuntes/bitacora.md tu explicación de qué es una rama.
3. Agregá ese archivo y creá un commit.
4. `git switch main`; revisá que la explicación aún no esté en main.
5. `git merge practica/bitacora`.
6. Revisá `git log --oneline --graph --all -10`.

**Éxito:** main contiene la explicación y `git status` está limpio.
Un merge fast-forward puede avanzar main sin crear un commit adicional de merge.
