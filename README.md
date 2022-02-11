# gliff.ai eslint-config

![Repo License](https://img.shields.io/github/license/gliff-ai/eslint-config?color=0078FF&style=flat-square) ![Repository Size](https://img.shields.io/github/repo-size/gliff-ai/eslint-config?style=flat-square&color=f2f2f2) ![Latest Tag](https://img.shields.io/github/v/tag/gliff-ai/eslint-config?&label=latest%20tag&style=flat-square&color=f2f2f2) ![Number of Open Issues](https://img.shields.io/github/issues/gliff-ai/eslint-config?style=flat-square&color=yellow) ![Number of Open Pull Requests](https://img.shields.io/github/issues-pr/gliff-ai/eslint-config?style=flat-square&color=yellow)

👋 **Welcome in!** 👋

This repository contains the ESLint configuration that is shared for [gliff.ai](https://gliff.ai)’s projects. 

This repository aims to clearly share our ESLint configuration used in [gliff.ai](https://gliff.ai) projects with contributors. This lint is designed to find and fix problems by analysing our JavaScript code to find problems like programming errors, bugs, stylistic errors and suspicious constructs and then can automatically fix many of the issues flagged.

❌ **This repository does not accept most contributions unfortunately! However, an issue can still be raised if you recognise a problem you wish to bring to the gliff.ai teams attention.** ❌

## Table of Contents

Looking for something specific? 🔍

- [Repository Introduction](#gliffai-eslint-config)
- [Table of Contents](#table-of-contents)
- [Access](#access)
- [Development](#development)
- [Linting and Formatting](#linting-and-formatting)
- [Testing](#testing)
- [Contribute](#contribute)
- [Contact](#contact)
- [License](#license)

## Access

[{{back to navigation}}](#table-of-contents)

Run `npm install @gliff-ai/annotate` in your command line to install the package from the npm registry.

To access our team's shared ESLint Config, run `npm i @gliff-ai/eslint-config --save-dev` and then within eslintrc.js run:

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

## Contribute

[{{back to navigation}}](#table-of-contents)

This repository **does not accept contributions** unfortunately as content has been developed with specific gliff.ai team practises and preferences in mind. _However_, an issue can still be raised if you recognise a problem you wish to bring to the gliff.ai teams attention.

We do have several repositories within the gliff.ai github space that  welcome all contributions and contributors on. These will be marked with the topic tag **contributions-welcome** meaning we welcome contributions on this repository! Search for them [here](https://github.com/search?q=topic%3Acontributors-welcome+org%3Agliff-ai&type=Repositories)!

Check out the [gliff.ai Contribution Guide](https://github.com/gliff-ai/.github/blob/main/CONTRIBUTING.md) 👋 to learn more!

## Contact

[{{back to navigation}}](#table-of-contents)

Need some help? 🤔 Have a question? 🧠 \
Reach out to the gliff.ai team at [community@gliff.ai](mailto:community@gliff.ai?subject=[GitHub]) or on our [GitHub discussions](https://github.com/gliff-ai/roadmap/discussions/landing).

## License

[{{back to navigation}}](#table-of-contents)

This code is licensed under a [GNU AGPLv3 license](https://github.com/gliff-ai/eslint-config/blob/main/LICENSE) 📝 \
Curious about our reasoning for this? Read about them [here](https://gliff.ai/articles/open-source-license-gnu-agplv3/)!
