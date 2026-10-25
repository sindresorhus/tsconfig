# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

This config makes TypeScript not do any polyfilling, so only use syntax and features available in the JavaScript environments you target.

## Install

```sh
npm install --save-dev @sindresorhus/tsconfig
```

*This config requires TypeScript >=6.0 and Node.js >=22.*

## Usage

`tsconfig.json`

```json
{
	"extends": "@sindresorhus/tsconfig"
}
```

TypeScript no longer includes `@types/node` automatically. If your project uses Node.js APIs, install `@types/node` and add it to `types`:

```json
{
	"extends": "@sindresorhus/tsconfig",
	"compilerOptions": {
		"types": ["node"]
	}
}
```
