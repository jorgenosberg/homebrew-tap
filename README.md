# homebrew-tap

Personal Homebrew tap for [@jorgenosberg](https://github.com/jorgenosberg)
tools.

## Usage

```sh
brew tap jorgenosberg/tap
brew install <formula>
```

Or in one step:

```sh
brew install jorgenosberg/tap/<formula>
```

## Formulas

| Formula | Description |
| ------- | ----------- |
| [agentcfg](https://github.com/jorgenosberg/agentcfg) | Sync skills, hooks, and instruction files across local AI coding agent configurations. Includes `agentcfg` (CLI) and `lazyagentcfg` (TUI). |

## How this tap is updated

Formula files in `Formula/` are generated and pushed by
[GoReleaser](https://goreleaser.com) from each source repository on tag
release. Manual edits should be rare.
