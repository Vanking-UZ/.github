# Vanking-UZ/.github

Служебный репозиторий организации.

| Путь | Что это |
|---|---|
| `profile/README.md` | Публичная страница организации на github.com/Vanking-UZ |
| `profile/assets/` | Баннеры (светлый и тёмный), аватар, social preview 1280×640 |
| `CONTRIBUTING.md`, `SECURITY.md` | Правила по умолчанию для всех репозиториев без своих файлов |
| `.github/PULL_REQUEST_TEMPLATE.md`, `.github/ISSUE_TEMPLATE/` | Шаблоны PR и задач по умолчанию |

Картинки собираются скриптом `tools/build_github_assets.py` в папке бренда (`~/Documents/wanking`):

```bash
merch/.venv/bin/python tools/build_github_assets.py <путь-к-этому-репо>/profile/assets
```
