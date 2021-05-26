# Template: TypeScript ES6/CommonJS Package

This repository is a template for [JavaScript](https://en.wikipedia.org/wiki/JavaScript) packages written in [TypeScript](https://www.typescriptlang.org) and distributed via services like [npm](https://www.npmjs.com).

In order to be compatible with as many consumers as possible, the package's TypeScript code is complied to both [CommonJS](https://en.wikipedia.org/wiki/CommonJS) and ["ES6" module](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) formats. This allows the package to be consumed by runtimes like [Node.js](https://nodejs.org) or parsed by bundlers like [rollup.js](https://rollupjs.org/guide/en/).

## Features

- 🎨 Code formatting via [Prettier](https://prettier.io)
- 🏗️ TypeScript [transpilation](https://en.wikipedia.org/wiki/Source-to-source_compiler)
- 👕 TypeScript linting via [eslint](https://eslint.org)
- 🧪 TypeScript unit test runner via [tape](https://github.com/substack/tape), which produces [Test Anything Protocol](https://en.wikipedia.org/wiki/Test_Anything_Protocol)
- 📝 TypeScript documentation generation via [TypeDoc](http://typedoc.org)
- 👷 [Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration) via [GitHub Actions](https://github.com/features/actions)
- 📄 [MIT license](https://en.wikipedia.org/wiki/MIT_License)

## Metadata

There's always some metadata to update when using boilerplate code, so make sure to do the following:

- Update the package's `name`, `version`, `description`, `author`, etc in `package.json`
- Update the `LICENSE.md` with the appropriate year and owner
- Update the `CHANGELOG.md` with your package's changes (see [keep a changelog](https://keepachangelog.com/en/1.0.0/))
- Remove the `private: true` flag from `package.json` (if you intend to publish to npm)
- Replace this `README.md` with your own!

## Usage

### Formatting & Linting

A combination of [EditorConfig](https://editorconfig.org), [Prettier](https://prettier.io), and [ESLint](https://eslint.org) are used to keep the code base formatted consistently and adhering to best practices.

In short, EditorConfig informs your editor of the basic file formatting (indentation, line endings, etc), Prettier formats the code with a consistent style, and ESLint checks for bad practices, typing issues, and so on.

To format the code (according to EditorConfig and Prettier settings):

```sh
yarn format
```

To lint the code (using a Prettier format check and ESLint):

```sh
yarn lint
```

It is highly recommended to install editor plugins/integrations in order to make code formatting and linting as seamless as possible. It's much easier to catch violations at edit-time, rather than downstream when builds fail.

Editor integrations:

- [EditorConfig](https://editorconfig.org/#download)
- [Prettier](https://prettier.io/docs/en/editors.html)
- [ESLint](https://eslint.org/docs/user-guide/integrations)
