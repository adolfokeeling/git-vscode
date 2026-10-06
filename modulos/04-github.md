# 04 · Publicar y revisar
**Objetivo:** completar un pull request (PR).

`origin` es el nombre del remoto creado al clonar. `push` publica commits; `fetch` trae referencias remotas sin integrar cambios; `pull` trae e integra.

Con los ejercicios locales anteriores terminados y el árbol limpio, publicá los commits de main:
```bash
git switch main
git push origin main
git pull --ff-only
git switch -c practica/glosario
# Editar apuntes/glosario.md y crear un commit.
git push -u origin practica/glosario
```

En GitHub abrí un PR desde esa rama hacia main. Revisá Files changed, describí el resultado y fusioná cuando estés conforme. Si la interfaz ofrece un método, podés usar Merge o Squash.

```bash
git switch main
git pull --ff-only
```

Si el push es rechazado, no uses force. Revisá el historial y sincronizá. Si `pull --ff-only` falla por divergencia, detenete y compará las ramas antes de elegir un merge.

**Práctica:** [Pull request](../ejercicios/04-pull-request.md).
