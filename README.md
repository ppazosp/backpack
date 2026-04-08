# backpack

A Claude Code plugin marketplace by [ppazosp](https://github.com/ppazosp).

## Plugins

| Plugin | Description |
|--------|-------------|
| [anvil](https://github.com/ppazosp/anvil) | Spec-driven project management for solo developers |

## Install

```
/plugin marketplace add ppazosp/backpack
/plugin install anvil@backpack
```

Or add to `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "backpack": {
      "source": { "source": "github", "repo": "ppazosp/backpack" }
    }
  },
  "enabledPlugins": {
    "anvil@backpack": true
  }
}
```
