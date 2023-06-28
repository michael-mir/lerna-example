# Lerna example

## Start

- Install [yarn](https://yarnpkg.com/):

`npm install --global yarn`

- Check yarn version:

`yarn -v`

- Install [lerna](https://github.com/lerna/lerna) 🐉:

`yarn global add lerna`

## How to run package scripts?

`yarn workspace {package} {script}`

## What's inside?

This mobnorepo includes the following packages:

### Packages

- `@michael-mir/packages-components`: a stub React component library
- `@michael-mir/tools-eslint`: `eslint` configurations
- `@michael-mir/tools-prettier`: `prettier` configurations
- `@michael-mir/tools-tsconfig`: `tsconfig.json`s used throughout the monorepo

### Utilities

This monorepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [Prettier](https://prettier.io) for code formatting
- [ESLint](https://eslint.org/) for code linting

### Build

To build all apps and packages, run the following command:

`yarn build`

### Develop

To develop all apps and packages, run the following command:

`yarn dev`

### Versioning

`lerna version --no-private`

### Publishing (+ versioning)

`lerna publish from-package`

### Scripts

- `build` - build package code
- `format` - format by [prettier](https://prettier.io/docs/en/options.html)
- `lint` - lint by [eslint](https://eslint.org/docs/latest/user-guide/configuring/)
