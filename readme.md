# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```
$ npm install --save-dev @sindresorhus/tsconfig
```

## Usage

`tsconfig.json`

```json
{
	"extends": "@sindresorhus/tsconfig",
	"compilerOptions": {
		"outDir": "dist"
	}
}
```

When you are targeting a higher version of NodeJS check the relevant ECMA Version and add it as `target`:

```json
{
	"extends": "@sindresorhus/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2021"
	}
}
```
