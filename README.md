# Web Standards Days
[![](https://github.com/web-standards-ru/wsd.events/workflows/Deploy/badge.svg)](https://github.com/web-standards-ru/wsd.events/actions?query=workflow%3ADeploy)

## Установка и запуск окружения

Необходима Node.js версии не ниже 4.1, зависимости ставятся командой `npm install`.

### Команды

1. Разработка: `npm start` — сборка в `dest` и локальный сервер из `dest` с вотчером.
2. Сборка: `npm run build:prod` — сборка версии для продакшена в `dest`.
3. Деплой: `npm run deploy` — синхронизация из `dest` на удалённый сервер, требуется доступ.

Деплой происходит автоматически после комита в `master`, вручную лучше не деплоить.

## Картинки

- Фото докладчика: цветной JPEG, 1024 × 1024 со сжатием 90%.
- Лого партнёра: SVG, в крайнем случае PNG, 460 × 460.

## Благодарности

- [Canonical](http://www.canonical.com/) за шрифт [Ubuntu](http://font.ubuntu.com/).
- [Злым марсианам](https://evilmartians.com/) за [Evil Icons](http://evil-icons.io/).
- Михаилу Баранову за настройку и поддержку сервера.
