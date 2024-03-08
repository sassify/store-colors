# 🎨 Sassify Colors
Набор различных цветовых палитр, предоставляемых в виде Sass-переменных (Variables) и карт (Maps).

![Весрия пакета на npm](https://img.shields.io/npm/v/@sassify/colors?label=%40sassify%2Fcolors)
![Список языков](https://img.shields.io/github/languages/count/sassify/colors?color=%23ff0056)
![Топ язык в репо](https://img.shields.io/github/languages/top/sassify/colors?color=%23ff0056)
![Кол-во открытых ишью](https://img.shields.io/github/issues-raw/sassify/colors)
![Кол-во открытых PR](https://img.shields.io/github/issues-pr-raw/sassify/colors)
![Лицензия](https://img.shields.io/github/license/sassify/colors)
![Версия зависимости `sass`](https://img.shields.io/github/package-json/dependency-version/sassify/colors/sass/main?color=%23d94390)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/sassify/colors)
![GitHub contributors](https://img.shields.io/github/contributors/sassify/colors)
![GitHub last commit](https://img.shields.io/github/last-commit/sassify/colors)

## Начало работы
Для начала необходимо установить npm-пакет `@sassify/colors`:

```sh
npm install --save-dev @sassify/colors
```

После установки зависимости в свой проект, импортируйте модуль Sassify Colors:

```scss
@use 'node_modules/@sassify/colors' as colors;
```

Теперь вся палитра из Sassify Colors доступна через пространство `colors`:

```scss
// _styles.scss
.text-warning {
	color: colors.$md-red--500;
}

.card {
	background-color: colors.$md-grey--200;
	color: colors.$md-grey--900;
}
```

```css
/* styles.css */
.text-warning {
	color: #f44336;
}

.card {
	background-color: #eeeeee;
	color: #212121;
}
```

> Вся цветовая палитра из Sassify Colors задокументирована с помощью комментариев SassDoc. Документация доступна по [этой](https://sassify.github.io/colors/) ссылке.

## Сообщество
У проекта Sassify нет какого-либо сервера в Discord, но есть Telegram &mdash; [@sassify](https://t.me/sassify).

## Версии
Для обеспечения прозрачности цикла выпуска и стремления поддерживать обратную совместимость Sassify поддерживается в соответствии с рекомендациями [Semantic Versioning](https://semver.org/). Иногда я ошибаюсь, но я придерживаюсь этих правил, когда это возможно.

## Благодарности
Несмотря на то, что я умудрился как-то гармонично (надеюсь) уложить все эти функции, я не могу не выразить огромную благодарность след. персонажам:
- [Kitty Giraudel](https://github.com/KittyGiraudel) - за большое количество кода и статей по Sass,
- [takamoso](https://github.com/takamoso) - за полезный код,
- [Sindre Sorhus](https://github.com/sindresorhus) - за полезный код,
- разработчикам CSS-препроцессора [Sass](https://sass-lang.com/) - за непосредственно Sass,
- всем тем у кого я учился (хоть я и не помню ваши имена).

## Лицензия
Проект распространяется по свободной лицензии [MIT](./LICENSE), однако в проекте используются труды иных людей, чьё авторство я также обозначил в местах, где используется их код.

```
MIT License

Copyright (c) 2024 Haba Kudzaev (therteenten)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
