# Лисюша ловит котят — GitHub Pages

Готовый статический сайт/PWA для GitHub Pages.

## Что загрузить
Загрузите **все файлы из этой папки в корень репозитория**.
`index.html` должен находиться в корне, рядом с `manifest.json` и `sw.js`.

## GitHub Pages
В репозитории:
1. Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: **main**
4. Folder: **/(root)**
5. Save

После публикации сайт будет доступен по адресу вида:

`https://ВАШ_ЛОГИН.github.io/ИМЯ_РЕПОЗИТОРИЯ/`

На iPhone:
Safari → Поделиться → **На экран «Домой»**.

## Состав
- index.html — игра
- manifest.json — PWA
- sw.js — офлайн-кэш
- apple-touch-icon.png — иконка iPhone
- icon-192.png / icon-512.png / icon-maskable-512.png — PWA-иконки
- PNG-файлы персонажей, котят и замков
- .nojekyll — отключает обработку Jekyll
