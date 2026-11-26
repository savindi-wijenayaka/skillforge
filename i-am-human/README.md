# i-am-human

Makes written output sound human and shorter. The rules come from the patterns catalogued in Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing).

## Install

```
/plugin install i-am-human --marketplace savindi-wijenayaka/skillforge
```

Or add the marketplace first (`/plugin marketplace add savindi-wijenayaka/skillforge`), then `/plugin install i-am-human@skillforge`.

## Use

The skill triggers on writing tasks (emails, READMEs, posts, docs, commit text) and on requests like "make this sound human" or "less verbose". Invoke it directly with `/i-am-human:i-am-human`.

## Files

- `skills/i-am-human/SKILL.md`: the writing recipe.
- `skills/i-am-human/patterns.md`: pattern catalog, loaded on demand.
