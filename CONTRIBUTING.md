# Contributing to Forge Zed Extension

This project uses the **Forge Protocol AI-Only Development Model** ([ADR-011](https://github.com/royalbit/forge-protocol/blob/main/docs/adr/011-ai-only-development-no-external-prs.md)).

## How to Contribute

| Method | Description |
|--------|-------------|
| **Issues** | Report bugs, request features |
| **Discussions** | Ask questions, share ideas |
| **Forks** | Create your own version (carry `ethics.yaml` forward) |

## Why No Pull Requests?

This project is developed by an autonomous AI following the Forge Protocol. External PRs are an attack vector that could bypass ethics safeguards.

**Trust Model:**
```
Human Owner -> AI (autonomous) -> Tests Pass -> Direct Commit -> Main
```

**Key Points:**
- PRs require human code review (not the Forge model)
- AI reviews can be fooled by obfuscated malicious code
- Ethics.yaml integrity depends on controlled commit path
- 50-100x velocity comes from removing PR overhead

## Getting Credit

When AI implements your idea from an Issue, you'll be credited in the commit:

```
feat: Add syntax highlighting for new keyword

Implements feature as requested in #10 by @contributor.

Closes #10

Co-Authored-By: Claude <noreply@anthropic.com>
```

## For Forks

Forks are **encouraged**! The social contract:
- Carry `ethics.yaml` forward
- Preserve the spirit of Humanist Mode
- See [Forge Protocol ADR-008](https://github.com/royalbit/forge-protocol/blob/main/docs/adr/008-ethics-protocol-humanist-mode.md) for details

## Questions?

Open an [Issue](https://github.com/royalbit/forge-zed/issues).

Thank you for understanding!
