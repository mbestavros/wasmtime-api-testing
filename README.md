# Wasmtime API work

This repo contains a basic demo of an external crate calling the [Wasmtime](https://github.com/CraneStation/wasmtime) WASI runtime to load and run a WASM binary.

Currently, running the crate will load in `test.wasm` (located in the repo root) and run the `add` function within that binary, which will return a sum.