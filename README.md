# skillforge

Claude Code plugin marketplace by Savindi Wijenayaka. One plugin per directory.

## Install

Add the marketplace once, then install what you want:

```
/plugin marketplace add savindi-wijenayaka/skillforge
/plugin install i-am-human@skillforge
```

Claude Code 2.1.275 or later can do it in one step:

```
/plugin install i-am-human --marketplace savindi-wijenayaka/skillforge
```

Update with `/plugin marketplace update skillforge`.

## Plugins

| Plugin | What it does |
|---|---|
| [`i-am-human`](i-am-human) | Makes written output sound human and less verbose, based on Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing). |
| [`in-my-voice`](in-my-voice) | Writes in Savindi's blog voice. Use with `i-am-human`. |

## Develop

Test a plugin locally without installing: `claude --plugin-dir ./i-am-human`.

To add a plugin:

1. Create `<name>/.claude-plugin/plugin.json` and `<name>/skills/<name>/SKILL.md`.
2. Add an entry to `.claude-plugin/marketplace.json` with `"source": "./<name>"`.
3. Run `claude plugin validate .` at the root and in the plugin folder.
