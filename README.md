# @andersdjohnson/tsconfig

> Shared TypeScript config for my projects.

## Install

```shell
$ npm add -D @andersdjohnson/tsconfig
```

[<kbd>copy</kbd>](https://copyhaste.com/c/?t=npm%20add%20-D%20%40andersdjohnson%2Ftsconfig)

## Use

```
{
	"extends": "@andersdjohnson/tsconfig",
  "include": ["src"],
	"compilerOptions": {
		"outDir": "dist"
	}
}
```

You must override any path-based compiler options (`outDir`, `outFile`, `rootDir`, `include`, `files`, etc.) as they are resolved from the config in which they're defined (see https://github.com/microsoft/TypeScript/issues/29172#issuecomment-450966221).
