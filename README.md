# My First Extension

![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

A minimal Visual Studio Code extension, generated with [Yeoman](https://yeoman.io/)'s
`generator-code`. It registers a single command, **Hello World**, which shows an
information message and opens the default browser on a Google image search for cats.

## Features

- Adds a `Hello World` command to the Command Palette.
- Running the command shows an information message and opens
  `https://www.google.com/search?q=cats&tbm=isch` in the default browser.

## Requirements

- [Node.js](https://nodejs.org/) and npm
- Visual Studio Code `^1.90.0`

## Getting started

```bash
npm install
npm run compile
```

Press `F5` in VS Code to launch a new Extension Development Host window with the
extension loaded, then run `Hello World` from the Command Palette
(`Ctrl+Shift+P` / `Cmd+Shift+P`).

## npm scripts

| Script | What it does |
| --- | --- |
| `npm run compile` | Compiles the TypeScript sources with `tsc`. |
| `npm run watch` | Compiles in watch mode. |
| `npm run lint` | Lints `src` with ESLint. |
| `npm test` | Compiles, lints, then runs the extension test suite via `@vscode/test-cli`. Requires a graphical/headless VS Code test environment; it will download a VS Code build on first run. |

## Packaging

```bash
npx @vscode/vsce package
```

Produces a `.vsix` file that can be installed manually via
`Extensions: Install from VSIX...` in VS Code. The `.vsix` output is not
committed to this repository.

## Contributing

This is a personal learning project and is not open to external contributions.
Issues and pull requests are disabled on this repository.

## License

[MIT](LICENSE)
