# espower-typescript-babel (experimental)

power-assert instrumentor for TypeScript and Babel

## Usage

Put tsconfig.json (target: ES6) in your project root and

```bash
$ npm i teppeis/espower-typescript-babel
$ mocha --compilers ts:espower-typescript-babel/guess test/**/*.ts
```
