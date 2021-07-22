# ESLint Configs


Inspired by [eslint-config-react-app](https://github.com/facebook/create-react-app/tree/main/packages/eslint-config-react-app).

Supports React and Typescript.

## Usage

First, install this package, ESLint and the necessary plugins. Note that when using npm 7 (or greater) this step is not required, as npm will automatically install peer dependencies.

```sh
npm install --save-dev @llc1123/eslint-config @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks prettier
```

Then create a file named `.eslintrc.js` with following contents in the root folder of your project:

```javascript
module.exports = {
  extends: ['@llc1123'],
}
```

That's it! You can override the settings from `@llc1123/eslint-config` by editing the `.eslintrc.js` file. Learn more about [configuring ESLint](https://eslint.org/docs/user-guide/configuring) on the ESLint website.