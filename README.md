# Guía OpenCode — Uso óptimo

Página estática (HTML + CSS + JS en un solo fichero, sin dependencias) con una guía en español
para usar **OpenCode** de la mejor manera: ahorro de tokens, sesiones, subagentes, ficheros de memoria y atajos.

## Qué contiene

1. Cómo funciona OpenCode (cliente + servidor, sesiones, agentes)
2. Atajos esenciales de teclado
3. Sesiones: memoria persistente y `@`/`!`/`/`
4. Ficheros que guardan lo que haces o tienes pendiente (`AGENTS.md`, comandos, skills, snapshots…)
5. `AGENTS.md`: tus reglas permanentes
6. Estrategias para usar menos tokens
7. Compacción y contexto
8. Dividir tareas en subagentes
9. Worktrees y paralelismo
10. Comandos slash y skills
11. Undo, redo y snapshots
12. Flujo recomendado paso a paso
13. Permisos y seguridad

## Cómo verla localmente

Doble clic en `index.html` o:

```sh
npx serve .
```

## Cómo subirla a GitHub

```sh
git init
git add .
git commit -m "Guía OpenCode"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
```

Luego en el repo: **Settings → Pages → Deploy from a branch → `main` / root**.
Tu página quedará en `https://TU-USUARIO.github.io/TU-REPO/`.

## Fuentes

Todo el contenido está basado en la documentación oficial de OpenCode V2:
<https://opencode.ai/docs/>
