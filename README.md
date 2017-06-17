# Чеклист для новых npm-модулей

Этот чеклист подготовлен для CSS (Less) модулей и может не подходить для JS-библиотек частично или полностью.
Скопируйте его исходный код в wiki своего проекта и отмечайте чекбоксы по мере прохождения.

## Подготовка к первой публикации

- [ ] добавить в корень проекта `.editorconfig` [http://editorconfig.org/](http://editorconfig.org/) и убедиться, что код отформатирован по этим правилам. [Пример моего конфига](https://github.com/paulradzkov/flxgrid.css/blob/master/.editorconfig).
- [ ] создать или отредактировать `package.json`
- [ ] создать или отредактировать `bower.json`
- [ ] проверить `.gitignore`
- [ ] создать или отредактировать `.npmignore`
- [ ] создать `.min` версию для релизных `css` и `js` файлов
- [ ] добавить в начало каждого релизного файла комментарий с версией проекта и ссылкой на репозиторий проекта
- [ ] создать или обновить `README.md`
- [ ] добавить бэджи в `README.md` — [https://badge.fury.io](https://badge.fury.io)
- [ ] добавить в `README.md` ссылки на подключаемые из CDN релизные файлы — [https://unpkg.com/](https://unpkg.com/) 
- [ ] создать **git-tag**
- [ ] опубликовать в **npm** командой `npm publish`
- [ ] зарегистировать в **bower** командой `bower register <my-package-name> <git-endpoint>`

## После первой публикации

- [ ] проверить рейтинг и рекомендации в [https://npms.io](https://npms.io)
- [ ] создать демки на codepen

## Создание нового релиза

- [ ] обновить версию проекта в титульных комментариях загружаемых файлов
- [ ] обновить ссылки на скомпилированные файлы в документации и README.md
- [ ] убедиться, что скомпилированные файлы обновлены
- [ ] обновить `package.json` командой `npm version 1.0.X`
- [ ] создать новый **git-tag** и обновить **changelog**
- [ ] обновить пакет командой `npm publish`
- [ ] обновить код демки на codepen

## Продвижение

- [ ] написать заметку об обновлении
- [ ] опубликовать в твиттере
- [ ] опубликовать в фейсбуке
- [ ] опубликовать в гугл плюс
- [ ] опубликовать статью на сайте
