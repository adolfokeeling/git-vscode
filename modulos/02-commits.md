# 02 · Guardar versiones
**Objetivo:** distinguir edición, staging y commit.

Un archivo editado vive en el directorio de trabajo. `git add` selecciona su contenido actual para el próximo commit. El commit guarda una versión local; todavía no la publica en GitHub.

```bash
git status
git diff
git add apuntes/bitacora.md
git diff --staged
git commit -m "docs: registrar mi primera práctica"
git log --oneline -5
```

Si editás después de `git add`, agregá de nuevo el archivo para incluir la edición nueva. En VS Code usá Source Control para ver cambios, el botón + para staging y el campo de mensaje para el commit. Revisá el diff antes de confirmar.

**Práctica:** [Primer commit](../ejercicios/02-primer-commit.md).
