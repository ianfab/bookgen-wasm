# bookgen-wasm

EPD opening book generation in the browser using the [WebAssembly port](https://github.com/fairy-stockfish/fairy-stockfish.wasm/tree/bookgen) of the Fairy-Stockfish based [book generator](https://github.com/fairy-stockfish/bookgen).

## Development

```
npm install

# Or use a local version of stockfish-nnue.wasm by e.g.
npm install bookgen.wasm@../bookgen-v2/src/emscripten/public

# Link node_modules/bookgen.wasm to public/lib
npm run link-lib

npm run serve
```

## Deployment

```
# Copy node_modules/bookgen.wasm to public/lib
npm run copy-lib

# Run vercel cli
npm run deploy
```
