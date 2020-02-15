# React Typescript Webpack Minimal Starter Kit

This is a bare minimum starter kit to get you going with your [React](https://reactjs.org/), [TypeScript](https://www.typescriptlang.org/) and [webpack](https://webpack.js.org/) experiments.

## Motivations

This repo is ready for your experiments, it keeps webpack config file clean so you can easily modify it and add more functionality.

## It Does
* Production build
* Can serve build folder with ([HTTP-Server](https://github.com/http-party/http-server))
* Development build (with `webpack-dev-server`)
* Create index.html with `html-webpack-plugin`

## It does not contain
* Tests
* Babel
* Lint
* Multiple webpack configurations
* Hot reload and Live reload

## Great if you want to
* Check how adding of some library influence your bundle size
* Play with some webpack property to better understand it
* Start development from scratch 

## Prerequisites

All you need to get started is [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/get-npm).

## Install

Just download the source or clone this repository 

```
git clone https://github.com/vict-shevchenko/react-typescript-webpack-minimal-starter-kit.git
```

(you may want to delete the `.git` directory to remove the association with this repo)

Then install dependencies:
```
npm install
```

## Run

### development server

```
npm start
```

### production build

```
npm run build
```


### server production build

```
npm run serve
```

## Edit

Edit  `src/index.tsx` and add other TypeScript files the way you see fit. Edit `src/assets/template.html` to change the HTML used by webpack.

## License

This package is released under [Unlicense](http://unlicense.org) meaning you can do pretty much anything you want with it.

## Contribute

Configurations with features will leave in its own branches, you may want to check them.
