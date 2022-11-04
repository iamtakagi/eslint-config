# @iamtakagi/eslint-config

```sh
yarn add -D @iamtakagi/eslint-config @iamtakagi/prettier-config eslint prettier
```

```js
// at package.json
{
    "eslint": {
        "extends": ["@iamtakagi"], // or "@iamtakagi/eslint-config/without-ts"
        "parserOptions": {
            "project": ["./tsconfig.json"]
        }
    },
    "prettier": "@iamtakagi/prettier-config",
}
```