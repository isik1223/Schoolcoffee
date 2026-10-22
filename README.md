# ARDINGLY COFFEE — сенсорное меню

Меню в стиле кофейного автомата: категории слева (горячие, холодные, еда), плитки позиций, выбор молока, сахара и добавок, корзина и экран «Заказ готовится».
Один файл `index.html`, без сборки и зависимостей.

## Запуск на GitHub Pages
1. Создайте репозиторий на github.com (например, `ardingly-coffee`).
2. **Add file → Upload files**: загрузите `index.html` и `README.md` (старые файлы заменятся).
3. **Settings → Pages → Build and deployment**: **Deploy from a branch**, ветка `main`, папка `/ (root)`, **Save**.
4. Через 1–2 минуты сайт откроется по адресу `https://ВАШ_ЛОГИН.github.io/ardingly-coffee/`.

## Как изменить меню
В начале блока `<script>` в `index.html`: `CONFIG` (валюта и цены добавок), `MILKS`, `CATS`, `GROUPS` и список `MENU` (название, цена, иконка).
