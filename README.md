# team-devops-handbook

Командний довідник з Git: гілки, коміти, pull request, рецензування, конфлікти та правила репозиторію.

## Склад команди

| Учасник | Роль | Розділи довідника |
|---|---|---|
| [@Rektosik](https://github.com/Rektosik) | власник репозиторію | `branching.md`, `editor-config.md`, `conflict.md` |
| [@IvanKhatser](https://github.com/IvanKhatser) | учасник | `readme-template.md`, `code-review.md` |

## Призначення довідника

Спільний довідник, у якому описано процес командної роботи з Git.

## Зміст

- [Гілки та коміти](docs/branching.md)
- [Налаштування редактора та .gitignore](docs/editor-config.md)
- [Шаблон README](docs/readme-template.md)
- [Рецензування pull request](docs/code_review.md)
- [Розбір конфлікту злиття](docs/conflict.md)
- 
## Правила роботи з репозиторієм

1. Прямі коміти в `main` заборонені.
2. Кожна зміна робиться в окремій гілці й потрапляє в `main` через pull request.
3. PR потребує схвалення іншого учасника.
4. Зливаємо лише через Squash and merge.
