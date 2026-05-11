# Homebrew Tap for DevSpecs

This is the official Homebrew tap for [DevSpecs CLI](https://github.com/devspecs-com/devspecs-cli) (`ds`).

## Installation

```bash
# Install directly (recommended)
brew install devspecs-com/tap/devspecs

# Or tap first, then install
brew tap devspecs-com/tap
brew install devspecs
```

The formula is named `devspecs`; the installed binary is **`ds`**.

## Update

```bash
brew update
brew upgrade devspecs
```

## Uninstall

```bash
brew uninstall devspecs
brew untap devspecs-com/tap  # optional
```

## Available Formulas

| Formula | Description |
|---------|-------------|
| `devspecs` | DevSpecs CLI — index and reference your specs, plans, and ADRs (`ds`) |

## About DevSpecs

DevSpecs CLI is a local-first tool for indexing and referencing planning artifacts (OpenSpec, ADRs, markdown plans, and more). Learn more at [github.com/devspecs-com/devspecs-cli](https://github.com/devspecs-com/devspecs-cli).

## Maintainers

`Formula/*.rb` files are **generated and updated by [GoReleaser](https://goreleaser.com)** when you release [devspecs-cli](https://github.com/devspecs-com/devspecs-cli). Do not edit them by hand; change release settings in [`.goreleaser.yml`](https://github.com/devspecs-com/devspecs-cli/blob/main/.goreleaser.yml) instead.

Until the first successful release upload, `brew install` may fail because no formula exists yet.
