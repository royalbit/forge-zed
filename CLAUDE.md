# Claude Instructions for forge-zed

## Project Overview

This is the **Zed extension** for Forge YAML - a deterministic formula calculator.

## Quick Start

```bash
# Build
rustup target add wasm32-wasip1
cargo build --target wasm32-wasip1 --release

# The extension requires forge-lsp in PATH
cargo install royalbit-forge
```

## Key Files

| File | Purpose |
|------|---------|
| `extension.toml` | Zed extension manifest |
| `src/lib.rs` | Extension code (spawns forge-lsp) |
| `languages/forge/highlights.scm` | 60+ Excel function highlighting |

## What This Extension Does

1. Registers "Forge YAML" language for `.forge.yaml` files
2. Spawns `forge-lsp` for LSP features (validation, completion, hover)
3. Provides syntax highlighting via tree-sitter queries

## Parent Project

This is a standalone repo for Zed marketplace submission.
Main project: https://github.com/royalbit/forge

## Protocol

Run `warmup.yaml` as working protocol for autonomous development.
