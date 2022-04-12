# base

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run build
npm run test:e2e # or `npm run test:e2e:ci` for headless testing
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## Setup VScode

Enable ESLint and Prettier Extensions

### Add as Prettier as ESLint [Plugin](<https://dev.to/s2engineers/how-to-make-eslint-work-with-prettier-avoiding-conflicts-and-problems-57pi>)

plugins: ['prettier'],

Additional steps only necessary if prettier and eslint not installed

### Format with [Prettier](<https://vueschool.io/articles/vuejs-tutorials/eslint-and-prettier-with-vite-and-vue-js-3/>)

### Installing Prettier

```sh
npm install --save-dev --save-exact prettier
```

### Create .prettierrc.json

```sh
echo {}> .prettierrc.json
```

### Installing ESLint

Maybe alread done

```sh
npm install --save-dev eslint eslint-plugin-vue
```

```sh
npm install eslint-config-prettier --save-dev
```
