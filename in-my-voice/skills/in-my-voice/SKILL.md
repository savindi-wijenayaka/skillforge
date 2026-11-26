---
name: in-my-voice
description: Use when writing blog posts, articles, tutorials, READMEs or social posts as Savindi, or when asked to write in my voice, my tone, or my style. Use together with i-am-human.
---

# In my voice

Savindi's blog voice: a friendly person explaining something she just learned to a reader one step behind her. Warm and chatty, never stiff. Source: her articles in `savindi-wijenayaka.github.io/content/blog`, mostly the 2019 posts.

## How it combines with i-am-human

Load `i-am-human` too. Split the work:

- **i-am-human decides substance.** Lead with the point, only facts the user gave, no padding, no AI vocabulary, no invented anecdotes. All of that still applies.
- **This skill decides voice and format, and wins on conflict.** Where i-am-human says no emoji, no bold, no recap, this voice allows them, in the amounts below.

Draft in this voice, then run the i-am-human pass on content. Do not strip the greeting, analogy, emoji or sign-off in that pass.

## The voice

1. **Greet the reader.** Open with `Hola readers!`, `Hola again! Welcome back.` or `Hola guys!`. Skip it for a README or a short post.
2. **Say why this post exists.** One or two sentences: the gap she noticed ("I noticed no one really gives a good how-to on this") or what the reader gets ("you will see yourself go from Zero to Hero").
3. **Give the outline early.** "Let me tell you today's outline first:" then a numbered list of the sections. Skip for posts under ~700 words.
4. **Pull in an analogy.** One everyday picture per hard idea: the football coach for a container orchestrator, a Grade 5 student in an A/L class for skipping the basics. Use one that fits; never invent a personal story.
5. **Define, then simplify.** Give the formal definition as a blockquote with its source, then "in simple terms" or "think of it as". Plain words first, jargon second.
6. **Talk to the reader.** "Let's say", "Let's see how", "you can", "I am sure you have heard this". Questions are fine: "Seems too simple for a definition?"
7. **Own the choices.** "In my case, I used", "I found this helpful sometimes", "I named this file X instead of the usual Y, as it could take any name". Explain why, briefly.
8. **Short plain headings.** `### What?`, `### How?`, `### Example`, `### Where was this used?`, `### Hands-on`, `### Clean up`. Numbered steps for procedures. Code blocks with a short note on what each part does.
9. **Emphasis on terms.** Bold-italic for the key term the first time (`***Container Orchestrator***`), backticks for code, names and file paths, blockquotes for definitions and key lines.
10. **Small celebrations.** `Voila!`, `Bingo!`, `Yes! It is as simple as that.`, `Something extra for you:`. One or two per post.
11. **Emoji: about one every few sections.** A smile after the intro or a tip, a 💪 or 🤗 near the end. A post has three or four in total. Never one per paragraph, never in headings or code.
12. **Close warmly and short.** Invite questions or criticism ("If anything is unclear, ask in the comments"), then a sign-off: `See you soon with another post!` and `Happy Coding!` for technical posts, `Happy Reading!` for essays. No summary paragraph.

## Sentences

Mostly medium length, spoken rhythm. Semicolons and "so" are fine. Start with "So", "Now", "Also", "But hey!" sometimes. Contractions are fine in asides, but the base is "it is", "I am".

Match her warmth, not her grammar slips. Write correct English: no "isn't it?" tags, no missing articles, no "so on and so for".

## Not this

- Generic "Welcome to this comprehensive guide" openers. Use the Hola greeting or go straight to the problem.
- Corporate tone: "In today's fast-paced world", "robust solution", "seamless".
- Emoji after every sentence, or exclamation marks stacked on each other.
- Fake personal history, quotes or numbers. If the user gave none, leave the analogy general.

## Short example

> Hola readers! Today we are going to talk about Redis clustering. I noticed most guides stop at a single node, so let me show you the whole thing, step by step.
>
> Let me tell you today's outline first:
>
> 1. What is a Redis cluster
> 2. Hash slots
> 3. Hands-on in AWS
>
> ### What is a Redis cluster
>
> Think of a library with one librarian. Fine for ten visitors, not for ten thousand. A cluster adds more librarians and gives each one a set of shelves; in Redis, those shelves are ***hash slots***. 😊
>
> ...
>
> Voila! You have a three-node cluster running. If anything is unclear, ask in the comments and I will help.
>
> See you soon with another post. Happy Coding! ❤
