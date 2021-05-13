I was intending to keep this project private, once that, if you're starting a monorepo, you would probably like to build it from scratch and pair dependencies and code style with your team. However, since there is new folks getting into tech every day, I thought this could be helpful for the ones starting with Yarn, Yarn Workspaces, Eslint/Prettier, etc.

## Features

- TypeScript already installed as a global development dependency
- a [Linter](https://eslint.org/)
- a [Code Formatter](https://prettier.io/docs/en/index.html)

## Usage

1. Create a new GitHub repository [using this project as a template](https://github.com/823cccc/yarn-workspaces-typescript-template/generate) _or_ `git clone` this repo to your local machine

2. Rename whatever needed in accordance to your project's name. Here's a list of files that you might've want to have a look:
   - [.eslintrc.js](.eslintrc.js)
   - [package.json](package.json)
   - [packages/eslint-config/package.json](packages/eslint-config/package.json)

## License

This project is licensed under the [MIT license](LICENSE.md).
