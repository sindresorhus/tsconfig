# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

This config makes TypeScript not do any polyfilling, so only use syntax and features available in the JavaScript environments you target.

## Install

```sh
npm install --save-dev @sindresorhus/tsconfig
```

*This config requires TypeScript >=5.9 and Node.js >=20.*

## Usage

`tsconfig.json`

```json
{
	"extends": "@sindresorhus/tsconfig"
}
```
