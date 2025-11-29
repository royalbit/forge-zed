# Forge-Zed

@warmup.yaml
@ethics.yaml

ON CONFUSION → re-read warmup.yaml + .claude_checkpoint.yaml

Rules: 4hr max, 1 milestone, WASM builds, ship it.

## Recovery Commands

```bash
cargo build --target wasm32-wasip1 --release    # Must succeed
cargo clippy --target wasm32-wasip1 -- -D warnings  # Zero warnings
```

## Key Files

- `warmup.yaml` - Full protocol (RE-READ when confused)
- `extension.toml` - Zed extension manifest
- `src/lib.rs` - Extension entry point
- `.claude_checkpoint.yaml` - Session state (if exists)
