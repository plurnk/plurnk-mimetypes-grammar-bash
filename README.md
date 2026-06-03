# @plurnk/plurnk-mimetypes-grammar-bash

Pre-built `tree-sitter-bash` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-bash
```

## what's in here

- **`bash.wasm`** — pre-built from the pinned upstream [tree-sitter-bash](https://github.com/tree-sitter/tree-sitter-bash) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `bash.wasm` is built from the upstream tree-sitter-bash grammar; see the pinned commit for that project's attribution.
