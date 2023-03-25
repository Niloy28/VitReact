# VitReact

A starter for React with Typescript with Vite and static code testing with ESLint (including React Hooks linting) and formatting with Prettier.

![Vite + React + Typescript + Eslint + Prettier](/resources/screenshot.png)

## Tools Included

- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

## Installation

Clone the repo, **OR** Run command

```
npx degit Niloy28/VitReact project-name
```

Then, run `yarn install`

Add `"eslint.validate": [
		"javascript",
		"javascriptreact",
		"html",
		"typescriptreact"
	]` to `settings.json` in VSCode if linting does not work.

## Start

Run `yarn dev` to start the development server.

## Setting up VSCode

#### (Optional, but recommended)

1. Install [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) and [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) extension for VSCode.
2. Make sure both are enabled.
3. Enable formatOnSave inside VSCode.
4. Open a .tsx file and check if ESLint and Prettier are enabled.
