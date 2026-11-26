# skillforge

Claude Code plugin marketplace. One plugin per directory.

## Install

```
/plugin marketplace add <github-user>/skillforge
/plugin install <plugin>@skillforge
```

Update: `/plugin marketplace update skillforge`.

Local test without installing: `claude --plugin-dir ./<plugin>`.

## Plugins

| Plugin | What it does |
|---|---|
| `i-am-human` | Makes written output sound human and less verbose. |

## Adding a plugin

1. Create `<name>/.claude-plugin/plugin.json` and `<name>/skills/<name>/SKILL.md`.
2. Add an entry to `.claude-plugin/marketplace.json` with `"source": "./<name>"`.
3. Run `claude plugin validate .` at the root and in the plugin folder.
