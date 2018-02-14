# Dockerfile with [webpack](https://webpack.github.io), [stylelint](https://stylelint.io/) and [ESLint](https://eslint.org/)


## Docker Image includes:
- Node 8.9
- Webpack 3.10
- ESLint 4.17
- Stylelint 8.4

## Install
> Make sure you have [Docker](https://docker.com/) installed

__Pull image from:__
```bash
$ docker pull leocaseiro/webpack-eslint-stylelint
```

__Re-build image:__
```bash
$ docker build -t leocaseiro/webpack-eslint-stylelint
```


## Setup Dockerfile
```
FROM leocaseiro/webpack-eslint-stylelint
```

---
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
