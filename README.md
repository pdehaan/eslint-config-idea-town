# eslint-config-idea-town

Shared ESLint config for idea-town repos.

## Installation:

Unfortunately, it doesn't look like you can obscure the nested dependencies into the external
config. So for now you need to install the `eslint-config-idea-town` config, the [`eslint-config-airbnb`](https://www.npmjs.com/package/eslint-config-airbnb) config, and the [`babel-eslint`](https://www.npmjs.com/package/babel-eslint) parser:

```sh
$ npm i --D eslint-config-idea-town eslint-config-airbnb babel-eslint
```

## Usage:

Simply create an .eslintrc file and extend the fancy "idea-town" config:

```yaml
extends: idea-town
```
