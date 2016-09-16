<p align="center">
  <img src="./media/logo.png" width="100" /><br><br>
  <a href="https://npmjs.com/package/hack"><img src="https://img.shields.io/npm/v/hack.svg?style=flat-square" alt="npm version"></a> <a href="https://npmjs.com/package/hack"><img src="https://img.shields.io/npm/dm/hack.svg?style=flat-square" alt="npm downloads"></a> <a href="https://gitter.im/egoist/hack"><img src="https://img.shields.io/gitter/room/egoist/hack.svg?style=flat-square" alt="Gitter"></a>
</p>

## Install

```bash
$ npm install --save hack
```

Option #1: Use any pre-processor

```js
import 'hack'
```

Option #2: hot-link the css files:

```html
<link rel="stylesheet" href="/path/to/hack.css">

<!-- markdown theme -->
<body class="hack"></body>

<!-- standard theme -->
<link rel="stylesheet" href="/path/to/standard.css">
<body class="standard"></body>

<!-- dark theme -->
<link rel="stylesheet" href="/path/to/dark.css">
<body class="hack dark"></body>

<!-- dark-grey theme -->
<link rel="stylesheet" href="/path/to/dark-grey.css">
<body class="hack dark-grey"></body>

<!-- solarized-dark theme -->
<link rel="stylesheet" href="/path/to/solarized-dark.css">
<body class="hack solarized-dark"></body>
```

It's also available on [CDNJS](https://cdnjs.com/libraries/hack) and NPMCDN:

> https://unpkg.com/hack/dist/hack.css<br>
> https://unpkg.com/hack/dist/standard.css<br>
> https://unpkg.com/hack/dist/dark.css<br>
> https://unpkg.com/hack/dist/dark-grey.css<br>
> https://unpkg.com/hack/dist/solarized-dark.css<br>

For more usages and style guideline head to [hackcss.com](http://hackcss.com/) 🎉

## Development

```bash
$ npm run dev

$ npm run build
```

## License

MIT &copy; [EGOIST](https://github.com/egoist)

Logo was generated with [slogan](https://github.com/egoist/slogan).
