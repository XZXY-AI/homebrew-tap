# XZXY-AI homebrew tap

Homebrew formulas for XZXY-AI command-line tools.

## Install

```bash
brew tap XZXY-AI/tap
brew install ccg-router
```

Or in one shot:

```bash
brew install XZXY-AI/tap/ccg-router
```

## Available formulas

| Formula | Description | Repo |
|---------|-------------|------|
| `ccg-router` | Local routing daemon for Claude Code (Anthropic-compatible) and Codex CLI (OpenAI-compatible). One daemon, both CLIs, local SQLite usage ledger, three routing strategies, streaming passthrough. | [XZXY-AI/ccg-router](https://github.com/XZXY-AI/ccg-router) |

## Updating

Formulas are auto-updated by `goreleaser` on each `vX.Y.Z` tag in the source repos. To force a refresh after a new release:

```bash
brew update
brew upgrade ccg-router
```

## Verifying

Release archives are signed with `cosign` keyless signing. Verification command per release is in each source repo's `SECURITY.md`.
