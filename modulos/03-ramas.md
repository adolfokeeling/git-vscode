# 03 · Ramas y merge
**Objetivo:** desarrollar un cambio sin modificar directamente main.

Una rama es una referencia a una secuencia de commits; no es una carpeta duplicada.

```bash
git switch main
git switch -c practica/bitacora
# Editar, agregar y guardar el cambio con un commit.
git switch main
git merge practica/bitacora
git log --oneline --graph --all -10
```

Cambiar de rama requiere cuidar los cambios sin guardar en commits. Si Git bloquea la operación, revisá `git status`; no descartés archivos solo para continuar.

Este merge es local. En el siguiente módulo practicarás la revisión mediante GitHub.

**Práctica:** [Rama y merge](../ejercicios/03-rama-y-merge.md).
