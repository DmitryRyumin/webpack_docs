# Webpack

![GitHub top language](https://img.shields.io/github/languages/top/DmitryRyumin/webpack_docs)
![GitHub repo size](https://img.shields.io/github/repo-size/DmitryRyumin/webpack_docs)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/DmitryRyumin/webpack_docs)
![GitHub last commit](https://img.shields.io/github/last-commit/DmitryRyumin/webpack_docs)

## Необходимо установить/обновить

- [NodeJS](https://nodejs.org/ru/)
- [Webpack](https://webpack.js.org/guides/getting-started/)

## Получение версий

```cmd
node --version
npm --version
```

## Создание файла `package.json` для списка зависимостей

```cmd
npm init
```

## Установка списка зависимостей из файла `package.json`

```cmd
npm install
```

## Установка Webpack

> `webpack` - основной функционал
>
> `webpack-cli` - использование webpack в командной строке
>
> `--save-dev` - зависимости только для разработки (`devDependencies`)

```cmd
npm install --save-dev webpack webpack-cli
```

## `webpack.config.js` - конфигурационный файл

## Сборка проекта

> `dev` - режим разработки
>
> `build` - режим продакшн
>
> `start` - режим запуска сервера в режиме разработки
>
> `stats` - статистика

```cmd
npm run dev
npm run build
npm run start
npm run stats
```

## [Паттерны](https://webpack.js.org/configuration/output/#outputfilename) для `filename`

## [Плагины](https://webpack.js.org/plugins/)

- `npm install --save-dev html-webpack-plugin` - взаимодействие с HTML ([параметры](https://github.com/jantimon/html-webpack-plugin#options))
- `npm install --save-dev copy-webpack-plugin` - копирование отдельных файлов или директорий, которые уже существуют, в каталог сборки ([параметры](https://webpack.js.org/plugins/copy-webpack-plugin/#options))
- `npm install --save-dev mini-css-extract-plugin` - извлечение CSS в отдельные файлы ([параметры](https://webpack.js.org/plugins/mini-css-extract-plugin/#plugin-options))
- `npm install --save-dev css-minimizer-webpack-plugin` - оптимизации/минимизации CSS файлов
- `npm install --save-dev eslint babel-eslint eslint-webpack-plugin` - статический анализ кода

## [Загрузчики](https://webpack.js.org/loaders/) - работа с другими типами данных отличными от `JS`

- `npm install --save-dev style-loader` - добавление стилей в секцию `HEAD` файла `HTML`
- `npm install --save-dev css-loader` - импорт стилей в `JS` файл
- `npm install --save-dev xml-loader` - загрузка `XML` файлов
- `npm install --save-dev csv-loader` - загрузка `CSV` файлов
- `npm install --save-dev less-loader` - компиляция `Less` в `CSS`
- `npm install --save-dev sass-loader` - компиляция `Sass` в `CSS`

## Другие библиотеки

- `npm install --save-dev webpack-dev-server` - перезагрузка проекта в реальном времени (выход `control+c`)
- `npm install normalize.css` - нормализация стилей
- `npm install jquery` - jQuery
- `npm install --save-dev cross-env` - кроссплатформенная установка переменных сред
- `npm install --save-dev less` - `Less`
- `npm install --save-dev sass` - `Sass`
- `npm install --save-dev babel-loader @babel/core @babel/preset-env @babel/plugin-transform-runtime @babel/plugin-proposal-class-properties` - `Babel` с пресетами и плагинами
- `npm install --save core-js` - стандартная библиотека `JS` включающая полифилы
- `npm install --save-dev webpack-bundle-analyzer` - визуализатор размеров выходных файлов `webpack`
- `npm install --save-dev eslint eslint-config-google` - общая конфигурация `ESLint` для руководства по стилю `Google JavaScript` (ES2015+)
- `npm install material-design-icons` - иконки в стиле минимализма
