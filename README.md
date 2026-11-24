# devops-docs

Учебный репозиторий практической работы № 9: Pylint, MkDocs, GitHub Actions и GitHub Pages.

- исходники документации: `docs/`;
- конфигурация MkDocs: `mkdocs.yml`;
- CI: `.github/workflows/quality.yml`;
- публикация: `.github/workflows/pages.yml`.

Каталог `site/` является результатом сборки и не хранится в Git.

Работу выполнил Горячев Владислав Павлович, ЭФБО-15-24.

Сайт: https://11l13n.github.io/devops-docs/

CI проверяет Pylint и строгую сборку документации до слияния. Публикация выполняется только из main.

Результаты экспериментов и исправления сохранены в Pull Request № 1–8. Маркер публикации: [build.txt](https://11l13n.github.io/devops-docs/build.txt).
