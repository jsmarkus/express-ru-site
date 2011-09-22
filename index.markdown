---
layout: default
title: фреймворк для Node.JS
original_url: http://expressjs.com
original_title: Express
---

# Express - высокопроизводительный, высококлассный веб-фреймворк для Node.JS

	var app = express.createServer();
	app.get('/', function(req, res) {
	    res.send('Hello World');
	});
	app.listen(3000);

## Возможности

 - Понятная маршрутизация
 - Помощники перенаправления (redirect helpers)
 - Динамические помощники представлений
 - Опции представлений уровня приложения
 - Взаимодействие с контентом
 - Монтирование приложений
 - Ориентированность на высокую производительность
 - Рендеринг шаблонов и поддержка фрагментных шаблонов (view partials)
 - Конфигурации, быстро переключаемые под разные задачи (`development`, `production`, и т.д.)
 - Хранимые в сессии всплывающие сообщения (flash messages)
 - Сделано на основе [Connect](http://github.com/senchalabs/connect)
 - Скрипт `express` для быстрой генерации каркаса приложения
 - Высокое покрытие тестами

## Участники проекта

Основной вклад в проект внесли следующие лица:

 - TJ Holowaychuk (visionmedia)
 - Ciaran Jessup (ciaranj)
 - Aaron Heckmann (aheckmann)
 - Guillermo Rauch (guille)

## Сторонние модули

Следующие модули работают с Express или построены на его основе:

 - [express-resource](http://github.com/visionmedia/express-resource) обеспечивает ресурсную маршрутизацию
 - [express-messages](http://github.com/visionmedia/express-messages) рендеринг всплывающих уведомлений
 - [express-configure](http://github.com/visionmedia/express-configuration) поддержка асинхронной конфигурации (загрузка данных из Redis, и т.д.)
 - [express-namespace](http://github.com/visionmedia/express-namespace) - пространства имен в маршрутах
 - [express-expose](http://github.com/visionmedia/express-expose) простая публикация JS-кода в клиентскую часть приложения
 - [express-params](https://github.com/visionmedia/express-params) - расширения `app.param()`
 - [express-mongoose](https://github.com/LearnBoost/express-mongoose) - плагин для простого рендеринга результатов запросов Mongoose (ORM для MongoDB)

## Прочая информация

 - `#express` на freenode
 - Следите за [tjholowaychuk](http://twitter.com/tjholowaychuk) в Твиттере
 - [Google Group](http://groups.google.com/group/express-js)
 - [Wiki](http://github.com/visionmedia/express/wiki)
 - [日本語ドキュメンテーション](http://hideyukisaito.com/doc/expressjs/) by [hideyukisaito](https://github.com/hideyukisaito)
 - [Русскоязычная документация](http://express-js.ru/)
