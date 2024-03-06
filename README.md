<img src="https://github.com/sassify/type-of/blob/main/.github/images/sassify_logo_round.png?raw=true" width="96" height="96" align="right" alt="Логотип проекта Sassify">Sassify Colors
===

🎨 Набор различных цветовых палитр, предоставляемых в виде Sass-переменных (Variables) и карт (Maps).

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

```bash
npm i @sassify/colors
```

## Начало работы
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
У проекта Sassify нет какого-либо сервера в Discord, но есть канал в Telegram &mdash; [@sassify](https://t.me/sassify).

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
Проект распространяется по свободной лицензии MIT, однако в проекте используются труды иных людей, чьё авторство я также обозначил в местах, где используется их код.

```
MIT License

Copyright (c) 2024 Haba Kudzaev <therteenten@inbox.ru>
```

> Если Вы нашли нарушение чьей-либо лицензии в моем проекте, то просьба написать мне:
> - [Telegram](https://t.me/therteenten)
> - [Электронная почта](mailto:therteenten@gmail.com?subject=Sassify)
> - [VK](https://vk.com/therteenten)
