# Ejercicio 05 · Resolver un conflicto sin afectar el repositorio
**Requisito:** ejercicio 04. **Tiempo:** 35 minutos.

Creá una carpeta NUEVA fuera de git-vscode, abrila en la terminal y ejecutá:
```bash
git init -b main
```
1. Creá saludo.txt con una sola línea: `Hola`.
2. `git add saludo.txt` y `git commit -m "Agregar saludo base"`.
3. `git switch -c alternativa`. Reemplazá la línea por `Hola desde alternativa`, agregá y creá un commit.
4. `git switch main`. Reemplazá la misma línea por `Hola desde main`, agregá y creá un commit.
5. `git merge alternativa`: ahora debe aparecer un conflicto.
6. Abrí saludo.txt. Sustituí TODO el contenido por `Hola desde ambas ramas`, sin marcas de conflicto.
7. `git add saludo.txt` y `git commit -m "Resolver conflicto del saludo"`.
8. Agregá una segunda línea `Línea temporal`, agregá el archivo y creá un commit.
9. Ejecutá `git revert HEAD`; aceptá el mensaje y cerrá el editor si se abre.
10. Revisá el archivo, `git status` y `git log --oneline --graph --all`.

**Éxito:** desaparece la línea temporal, el saludo combinado permanece y el historial contiene el commit de revert.
**Pista:** si querés cancelar el merge antes del paso 7, usá `git merge --abort`.
No publiques este laboratorio; anotá lo aprendido en la bitácora del repositorio principal.
