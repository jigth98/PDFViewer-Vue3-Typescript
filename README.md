# vue3-pdfjs-typescript

After trying quite a lot of options to get a PDF Viewer working with **Vue3** and Typescript, here's an starter example for doing just that. It should work out of the box without any modifications.

* This projects allows to render a PDF file with VueJS 3 and Typescript.

* It uses a relatively new library for VueJS **vue3-pdfjs**. Available at [https://github.com/randolphtellis/vue3-pdfjs](https://github.com/randolphtellis/vue3-pdfjs)

## Has been adapted to work for Typescript (Type definition for module)

It should work correctly out of the box, for Vue3 and has been slightly adapted to work with Typescript by using the following strategy.

* **The following file have been added**
./src/vue3-pdfjs.d.ts

* In ./tsconfig.json the following attribute have been created:
```
  "files": [
      "./src/vue3-pdfjs.d.ts"
  ]

```


## Installation

### Project setup
```
pnpm install
```

#### Compiles and hot-reloads for development
```
pnpm run serve
```

#### Compiles and minifies for production
```
pnpm run build
```

#### Lints and fixes files
```
pnpm run lint
```

#### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
