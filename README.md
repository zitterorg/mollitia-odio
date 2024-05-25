# @zitterorg/mollitia-odio

[![Deploy](https://github.com/zitterorg/mollitia-odio/workflows/build/badge.svg)](https://github.com/zitterorg/mollitia-odio/actions)
[![Coverage Status](https://coveralls.io/repos/github/glebbash/@zitterorg/mollitia-odio/badge.svg?branch=master)](https://coveralls.io/github/glebbash/@zitterorg/mollitia-odio?branch=master)

Cli to create public typescript libraries hosted on GitHub and published to NPM.

Usage:

```sh
npx @zitterorg/mollitia-odio
```

What's included:

- CI/CD:
  - github-actions: build test and publish to npm
  - husky(git-hooks): commit message linting, running tests
  - coverage: coveralls
- Formatting:
  - ESLint and Prettier
  - Editorconfig
- Testing:
  - Jest

This project is [MIT Licensed](LICENSE).
