# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects


## Install

```
npm install --save-dev @sanv/tsconfig
yarn add --dev @sanv/tsconfig
```


## Usage

`tsconfig.json`

```json
{
	"extends": "@sanv/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "es2018",
		"lib": [
			"es2018"
		]
	}
}
```
