# eslint-config
Shared ESLint Config

`npm i @gliff-ai/eslint-config --save-dev`

then in eslintrc.js

```js
module.exports = {
  extends: [
      "@gliff-ai"
  ],
  parserOptions: {
    tsconfigRootDir: __dirname,
    project: ["./tsconfig.json"],
  },
  overrides: [
      {
          files: ["*.ts", "*.tsx"],
          rules: {}        
      }]
};
```
