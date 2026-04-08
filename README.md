# black-market

A Claude Code plugin marketplace by [ppazosp](https://github.com/ppazosp).

## Plugins

| Plugin | Description |
|--------|-------------|
| [anvil](https://github.com/ppazosp/anvil) | Spec-driven project management for solo developers |

## Install

```
/plugin marketplace add ppazosp/black-market
/plugin install anvil@black-market
```

Or add to `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "black-market": {
      "source": { "source": "github", "repo": "ppazosp/black-market" }
    }
  },
  "enabledPlugins": {
    "anvil@black-market": true
  }
}
```
