# TaskFlow

![CI](https://github.com/camsset-dev/taskflow/actions/workflows/ci.yml/badge.svg)

Gestor de tareas en Python · Proyecto integrador del curso **DevOps & Project Management**.

Sitio: https://camsset-dev.github.io/taskflow/

## Equipo
- Camila Saenz — [@camsset-dev](https://github.com/camsset-dev)

## ¿Qué hace?
TaskFlow permite agregar tareas con prioridad (baja, media, alta), completarlas, eliminarlas y listar las pendientes.

## Cómo ejecutarlo
```bash
python -m venv .venv
source .venv/bin/activate        # Windows (Git Bash): source .venv/Scripts/activate
pip install -r requirements.txt
python -m taskflow
python -m pytest -v
```

## Flujo de trabajo
- Estrategia: GitHub Flow · merge: squash · `main` protegida con el ruleset `proteger-main`
- Convenciones: ramas `tipo/descripcion`, Conventional Commits, PRs con plantilla

## CI/CD
- `ci.yml`: pruebas en Python 3.11, 3.12 y 3.13 en cada pull request
- `deploy.yml`: pruebas + publicación en GitHub Pages en cada merge a `main`

## Avance del proyecto
- [x] Hito 1 — Repositorio, código base y pruebas locales
- [x] Hito 2 — GitHub Flow, CI/CD y GitHub Pages
- [ ] Hito 3 — Jira, sprint e integración con GitHub

## Evidencias
### Hito 2
- [PR #1 · Plantilla de pull request](https://github.com/camsset-dev/taskflow/pull/1)
- [PR #2 · Pipeline de CI](https://github.com/camsset-dev/taskflow/pull/2)
- [PR #3 · Eliminar tareas](https://github.com/camsset-dev/taskflow/pull/3)
- [PR #4 · Sitio en GitHub Pages](https://github.com/camsset-dev/taskflow/pull/4)
- [Sitio publicado](https://camsset-dev.github.io/taskflow/)
