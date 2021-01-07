# Svelte WasmerJS WASI Example

This is the Wasmer 'hello-world' example in a Svelte app. It's based on the Svelte webpack template rather than rollup because there's an issue outstanding using `@wasm/wasi` with rollup (see [issue #154](https://github.com/wasmerio/wasmer-js/issues/154#issuecomment-756134834)). 

All it does is write 'hello world' to the document, but the clever part is that the text is obtained from a wasm binary. See the Wasmer 'hello-world' [example](https://docs.wasmer.io/integrations/js/wasi/browser/examples/hello-world) for details.

# Instructions

## Prerequisites
Make sure you have Node.js installed.

## Build
If you don't have `yarn` use `npm run` instead of `yarn` in the following:
```
git clone https://github.com/happybeing/simple-svelte-wasmer-webpack
cd simple-svelte-wasmer-webpack
yarn && yarn dev
```
Once the build completes you can visit the app at localhost:8080 and should see the following:

> Standard Output: hello world 

## LICENSE

Everything in this project is subject to the GPL3.0 license. All contributions are accepted on the basis they conform to this license.

See also: [./LICENSE](./LICENSE)