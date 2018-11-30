# tsconfig [![Build Status](https://travis-ci.com/sindresorhus/tsconfig.svg?branch=master)](https://travis-ci.com/sindresorhus/tsconfig)

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
		"lib": [
			"es2018"
		]
	}
}
```


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
