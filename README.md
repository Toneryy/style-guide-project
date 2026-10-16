# style-guide-project

Руководство по стилю документации музыкального сервиса Itmotify. Проект сделан по методологии Docs as Code: текст хранится в Markdown, изменения проходят через Pull Request, проверяются линтерами и автоматически публикуются.

Сайт руководства: <https://toneryy.github.io/style-guide-project/>

## Что внутри

| Путь | Назначение |
| --- | --- |
| `docs/` | Разделы руководства в Markdown |
| `mkdocs.yml` | Настройки сайта и навигации MkDocs |
| `.markdownlint-cli2.jsonc` | Правила разметки для markdownlint |
| `.vale.ini`, `styles/Itmotify/` | Правила языка и стиля для Vale |
| `.github/workflows/docs.yml` | Проверка, сборка и публикация на GitHub Pages |
| `CONTRIBUTING.md` | Как предложить изменение |

## Локальная сборка

```bash
python -m venv .venv
source .venv/bin/activate        # в Windows: .venv\Scripts\activate
pip install -r requirements.txt
mkdocs serve
```

Сайт откроется по адресу <http://127.0.0.1:8000>. Подробнее о проверках и процессе ревью – в [CONTRIBUTING.md](CONTRIBUTING.md).

## Авторы

Лабораторная работа № 3 по дисциплине «Проектная документация», Университет ИТМО, 2026.

- Мещеряков Д.П.
- Катков А.С.
