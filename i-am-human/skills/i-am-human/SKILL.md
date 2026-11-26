---
name: i-am-human
description: Use when writing or rewriting prose a person will read or post as their own, such as emails, READMEs, posts, docs, essays, messages, bios, or commit and PR text, or when asked to sound human, less robotic, less verbose, or to remove AI-sounding writing.
---

# I Am Human

LLM prose drifts to the statistical average: generic, upbeat, padded. Human prose is specific, plain and ends when the point is made.

Applies to the text you deliver, not to chat with the user about it.

## Write it like this

1. **Lead with the point.** First sentence is the answer, the announcement, or the ask. No preamble, no "Here's a draft".
2. **Name the specific thing, from the user's facts only.** A number, a name, a date, a failure mode they gave you. If none exists for a sentence, cut it; never invent one to fill the gap.
3. **Use plain words and plain verbs.** "is", "has", "used", "wrote", "tried". Swap `serves as`, `boasts`, `utilize`, `leverage`, `showcase` for these.
4. **Say each thing once.** One idea per sentence, no closing recap. Stop at the last new fact.
5. **State claims straight.** Positive form, own the opinion, name the source or drop the attribution. No "it's worth noting", no "may potentially".
6. **Vary shape.** Mix short and long sentences. Use two items or four as often as three. Plain paragraphs; a list only when content is a list.
7. **Plain formatting.** Sentence-case headings, straight quotes, no emoji, no bold for emphasis, no inline-header bullets. Commas and periods mostly; dashes rarely.
8. **Match the register of the place.** A Slack message is short and casual. A README is direct. Copy the user's own phrasing if samples exist.
9. **Deliver only the text.** No intro line, no sign-off offering more help, no caveat padding. Note a missing fact in one short line after the text, only if you had to invent nothing.

## Before you send

Read the draft against `patterns.md` in this directory, then cut and rewrite. Replacing a flagged word with a synonym does not fix the pattern; restructure the sentence around the actual fact.

Target: 30-50% shorter than your first draft, same facts.

## Short beats invented

A short text with three real facts beats a vivid one with made-up anecdotes, lessons, thanks or numbers. Every claim in the text must trace to the user's input. If the user gave a word count, treat it as a ceiling: deliver the real facts in fewer words, then name the missing detail in one line. Closing lines ("happy to chat", "thanks to all") count only if the user asked for them.
