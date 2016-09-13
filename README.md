# Чеклист для новых npm-модулей

Этот чеклист подготовлен для CSS (Less) модулей и может не подходить для JS-библиотек частично или полностью.
Скопируйте его исходный код в wiki своего проекта и отмечайте чекбоксы по мере прохождения.

## Подготовка к первой публикации

- [ ] добавить в корень проекта `.editorconfig` [http://editorconfig.org/](editorconfig) и убедиться, что код отформатирован по этим правилам. [Пример моего конфига](editorconfig-example).
- [ ] создать или отредактировать `package.json`
- [ ] создать или отредактировать `bower.json`
- [ ] проверить `.gitignore`
- [ ] создать или отредактировать `.npmignore`
- [ ] создать `.min` версию для релизных `css` и `js` файлов
- [ ] добавить в начало каждого релизного файла комментарий с версией проекта и ссылкой на репозиторий проекта
- [ ] создать или обновить `README.md`
- [ ] создать **git-tag**
- [ ] опубликовать в **npm** командой `npm publish`
- [ ] зарегистировать в **bower** командой `bower register <my-package-name> <git-endpoint>`

## После первой публикации

- [ ] добавить бэджи в `README.md` — [https://badge.fury.io](badges)
- [ ] добавить в `README.md` ссылки на подключаемые из CDN релизные файлы — [https://unpkg.com/](unpkg) 

## Создание нового релиза

- [ ] обновить версию проекта в титульных комментариях загружаемых файлов
- [ ] обновить `package.json` командой `npm version 1.0.X`
- [ ] создать новый **git-tag** и обновить **changelog**
- [ ] обновить пакет командой `npm publish`

[editorconfig]: http://editorconfig.org/
[editorconfig-example]:https://github.com/paulradzkov/flxgrid.css/blob/master/.editorconfig
[badges]: https://badge.fury.io
[unpkg]: https://unpkg.com/
