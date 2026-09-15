<p align="center">
	<img src="https://img.shields.io/badge/status-finished-success?color=%2312bab9&style=flat-square"/>
	<img src="https://img.shields.io/github/languages/top/jotavare/my-first-vscode-extension?color=%2312bab9&style=flat-square"/>
	<img src="https://img.shields.io/github/last-commit/jotavare/my-first-vscode-extension?color=%2312bab9&style=flat-square"/>
	<a href='https://www.linkedin.com/in/jotavare' target="_blank"><img alt='Linkedin' src='https://img.shields.io/badge/LinkedIn-blue?style=flat-square'/></a>
</p>

<p align="center">
	<a href="#about">About</a> •
	<a href="#features">Features</a> •
	<a href="#requirements">Requirements</a> •
	<a href="#getting-started">Getting started</a> •
	<a href="#npm-scripts">npm scripts</a> •
	<a href="#packaging">Packaging</a> •
	<a href="#contributing">Contributing</a> •
	<a href="#license">License</a>
</p>

## ABOUT

A minimal Visual Studio Code extension, generated with [Yeoman](https://yeoman.io/)'s
`generator-code`. It registers a single command, **Hello World**, which shows an
information message and opens the default browser on a Google image search for cats.

## FEATURES

- Adds a `Hello World` command to the Command Palette.
- Running the command shows an information message and opens
  `https://www.google.com/search?q=cats&tbm=isch` in the default browser.

## REQUIREMENTS

- [Node.js](https://nodejs.org/) and npm
- Visual Studio Code `^1.90.0`

## GETTING STARTED

```bash
npm install
npm run compile
```

Press `F5` in VS Code to launch a new Extension Development Host window with the
extension loaded, then run `Hello World` from the Command Palette
(`Ctrl+Shift+P` / `Cmd+Shift+P`).

## NPM SCRIPTS

| Script | What it does |
| --- | --- |
| `npm run compile` | Compiles the TypeScript sources with `tsc`. |
| `npm run watch` | Compiles in watch mode. |
| `npm run lint` | Lints `src` with ESLint. |
| `npm test` | Compiles, lints, then runs the extension test suite via `@vscode/test-cli`. Requires a graphical/headless VS Code test environment; it will download a VS Code build on first run. |

## PACKAGING

```bash
npx @vscode/vsce package
```

Produces a `.vsix` file that can be installed manually via
`Extensions: Install from VSIX...` in VS Code. The `.vsix` output is not
committed to this repository.

## CONTRIBUTING

This repository is finished and not open to changes.

## LICENSE

This project is available under the MIT License. For further details, please refer to the [LICENSE](https://github.com/jotavare/my-first-vscode-extension/blob/main/LICENSE) file.
