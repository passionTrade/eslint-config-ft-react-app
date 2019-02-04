# eslint-config-ft-react-app

This package includes the shareable ESLint configuration used by fashionTrade react apps.

## Usage in Create React App Projects

The easiest way to use this configuration is with [Create React fT App](https://github.com/FashionTrade/create-ft-react-app), which includes it by default.

**You don’t need to install it separately in Create React App projects.**

## Usage Outside of Create React App

If you want to use this ESLint configuration in a project not built with Create React App, you can install it with the following steps.

First, install this package, ESLint and the necessary plugins.

```sh
yarn add --dev @fashiontrade/eslint-config-ft-react-app babel-eslint@9.x eslint@5.x eslint-plugin-flowtype@2.x eslint-plugin-import@2.x eslint-plugin-jsx-a11y@6.x eslint-plugin-react@7.x eslint-config-airbnb@17.0.0 eslint-config-prettier@3.0.1 eslint-plugin-jest@21.x eslint-plugin-mocha@5.x eslint-plugin-prettier@2.x
```

Then create a file named `.eslintrc.js` with following contents in the root folder of your project:

```
module.export = {
  extends: '@fashiontrade/eslint-config-ft-react-app',
}
```

That's it! You can override the settings from `eslint-ft-config-react-app` by editing the `.eslintrc.js` file.
