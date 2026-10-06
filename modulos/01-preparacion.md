# 01 · Preparar el entorno
**Objetivo:** abrir una copia local en VS Code.

Instalá Git y VS Code desde los enlaces de [recursos](../recursos/documentacion.md). En Windows podés usar Git Bash. En VS Code abrí Terminal → New Terminal.

```bash
git --version
git config --global user.name "Adolfo Keeling"
git config --global user.email "TU_CORREO_VERIFICADO_O_NOREPLY"
git clone https://github.com/adolfokeeling/git-vscode.git
cd git-vscode
code .
git status
git remote -v
```

Reemplazá el correo antes de ejecutar: aparecerá en tus commits. Podés usar el correo noreply de GitHub → Settings → Emails. Si `code .` no funciona, abrí la carpeta desde File → Open Folder.

Clonar ya crea `origin` y el directorio `.git`; no ejecutés `git init` dentro de esta copia. Para publicar, seguí la autenticación oficial de GitHub enlazada en recursos; no uses tu contraseña de cuenta como contraseña de Git.

**Práctica:** [Explorar](../ejercicios/01-explorar.md).
