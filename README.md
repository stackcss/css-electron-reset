# css-electron-reset [![stability][0]][1]
[![npm version][2]][3] [![build status][4]][5]
[![downloads][8]][9] [![js-standard-style][10]][11]

Reset Electron stylesheets so it behaves like a native application

## CSS
```css
html {
  -webkit-user-select: none;
  -webkit-user-drag: none;
  cursor: default;
}

input, textarea, select, button, img {
  -webkit-user-drag: none;
}

.draggable {
  -webkit-app-region: drag;
}

.selectable {
  -webkit-user-select: auto;
  cursor: auto;
}
```

## License
[MIT](https://tldrlegal.com/license/mit-license)

[0]: https://img.shields.io/badge/stability-experimental-orange.svg?style=flat-square
[1]: https://nodejs.org/api/documentation.html#documentation_stability_index
[2]: https://img.shields.io/npm/v/css-electron-reset.svg?style=flat-square
[3]: https://npmjs.org/package/css-electron-reset
[4]: https://img.shields.io/travis/stackcss/css-electron-reset/master.svg?style=flat-square
[5]: https://travis-ci.org/stackcss/css-electron-reset
[6]: https://img.shields.io/codecov/c/github/stackcss/css-electron-reset/master.svg?style=flat-square
[7]: https://codecov.io/github/stackcss/css-electron-reset
[8]: http://img.shields.io/npm/dm/css-electron-reset.svg?style=flat-square
[9]: https://npmjs.org/package/css-electron-reset
[10]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[11]: https://github.com/feross/standard
