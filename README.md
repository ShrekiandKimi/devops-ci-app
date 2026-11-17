# devops-ci-app

Учебное Flask-приложение. CI: Pylint → pytest → Docker build → smoke-test → GHCR.

Публикация выполняется только при push в main.

- Проверка: `/health`.
- Образ: `ghcr.io/shrekiandkimi/devops-ci-app`.
