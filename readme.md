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
		"outDir": "dist",
		"target": "es2018",
		"lib": [
			"es2018"
		]
	}
}
```
