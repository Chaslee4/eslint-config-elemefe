# eslint-config-ylfe

Eslint rules for ylfe based on Elemefe's eslint rule.
Forked form project[https://github.com/ElemeFE/eslint-config-elemefe]

## Usage

### eslint-config-ylfe

Our default export contains all of our ESLint rules, including ECMAScript 6.

First, install this package
```sh
npm install --save-dev eslint-config-ylfe eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "ylfe"
}
```

### eslint-config-ylfe/legacy

For some legacy project using es5.

First, install this package
```sh
npm install --save-dev eslint-config-ylfe eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "ylfe/legacy"
}
```

### eslint-config-ylfe/react
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-ylfe eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
Then add following contents to your .eslintrc file
```
{
  "extends": "ylfe/react"
}
```

## License
MIT
