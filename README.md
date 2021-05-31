# tsconfig

[![npm](https://img.shields.io/npm/v/@egomobile/tsconfig.svg)](https://www.npmjs.com/package/@egomobile/tsconfig)

Shared [TypeScript](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) config files for [e.GO](https://e-go-mobile.com/) projects.

## Install

```
$ npm install --save-dev @egomobile/tsconfig
```

## Usage

### tsconfig.json

```json
{
    "extends": "@egomobile/tsconfig",
    "compilerOptions": {
        "outDir": "dist",
        "target": "es2020",
        "lib": [
            "es2020"
        ]
    }
}
```

### TSLint / ESLint

[TSLint](https://palantir.github.io/tslint/) has been removed from that project.

Please use [ESLint](https://eslint.org/) with [eslint-config-ego](https://www.npmjs.com/package/eslint-config-ego) as basic Linter configuration.