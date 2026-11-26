# Patterns to find and remove

Source: Wikipedia, "Signs of AI writing" (WP:AISIGNS). Patterns, not a ban list. One hit means nothing; clusters matter. These apply when text is meant to read as human. Skip them for quoted text and for technical terms that are the right word.

## Content

| Pattern | Looks like | Fix |
|---|---|---|
| Significance inflation | "marks a pivotal moment", "a testament to", "plays a vital role", "shaping the landscape of", "broader trends" | State what happened. Delete the importance claim. |
| Fake influence | "has sparked discussions about", "contributes to the broader conversation on" | Name who said what, or cut. |
| Notability padding | "featured in leading publications", "maintains an active social media presence" | Cite one concrete source, or cut. |
| Tacked-on -ing analysis | "..., highlighting its importance", "...showcasing the team's commitment" | End the sentence at the fact. |
| Vague connection | "is associated with", "connected to" | Say the relationship: was CEO, taught, founded. |
| Vague authority | "experts say", "many critics argue", "some believe" | Name one source or own the claim. |
| Challenges-and-future outline | "Despite its X, it faces challenges... Looking ahead, ..." | Cut, or give the real problem and the real next step. |
| Summary ending | "In conclusion", last line restating the point, "This ensures that..." | Stop one sentence earlier. |
| Source-availability hedging | "little public information is available", "maintains a low profile" | Say what you don't know in one clause, or omit. |
| Corrective framing | "should be treated as X rather than Y", "should not be confused with" | Cut unless the user needs the warning. |

## Language

| Pattern | Looks like | Fix |
|---|---|---|
| AI vocabulary (2023-26) | delve, tapestry, testament, pivotal, crucial, vibrant, intricate, interplay, landscape, underscore, bolster, foster, garner, enhance, showcase, highlight (verb), enduring, meticulous, multifaceted, leverage, align with, quietly, steady, dependable, practical, prioritize, matters, echoed | Plain word, or cut. Several in one text is the tell. |
| Copula avoidance | "serves as", "stands as", "marks", "features", "offers", "boasts", "ventured into" | "is", "has", "was". |
| Negative parallelism | "not just X, but Y", "it's not X, it's Y", "Y rather than X" | State Y. Use sparingly if the contrast is real. |
| Rule of three | "fast, reliable, and scalable"; three parallel phrases every time | Pick the one or two that are true. |
| Elegant variation | cycling synonyms for the same noun ("the tool", "the solution", "the platform") | Repeat the plain noun. |
| Stiff synonyms | utilize, authored, relocated, attempted, passed away | used, wrote, moved, tried, died. |
| Missing human texture | no qualifiers, no simple "there is", no "in order to" ever | Human text has "very", "perhaps", "a bit", "the fact that". Allow them. |
| Uniform rhythm | every sentence 8-20 words, all commas and periods | Mix a 4-word sentence with a 30-word one. |
| Em-dash habit | spaced em dashes for punch, or none at all after a ban | Use commas, colons, parentheses and periods in mixed measure. |

## Style and formatting

- Title Case Headings -> Sentence case.
- Bold sprinkled in prose, `**Label:** text` bullet lists -> plain sentences.
- Emoji as bullets or heading prefixes -> none.
- Curly quotes and apostrophes -> straight.
- Headings and bullets on a short message -> a paragraph.
- "Awards and recognition", "Legacy", "Future prospects" style sections -> drop unless real.

## Chatbot residue

- "Here's a ...", "Certainly!", "I hope this helps", "Let me know if...", "Would you like me to..."
- "As of my last update", "it's important to note", "it's worth mentioning"
- Placeholders left in: [Your Name], INSERT_URL, xx-xx-xx.
- Markdown in a plain-text destination (emails, commit bodies, Slack).

## Social and sales tells

- "Excited to announce", "Huge thanks to my incredible team", "journey", "game-changer", closing engagement bait ("Thoughts? 👇").
- Hook line plus one-sentence paragraphs for drama.

## Not signs on their own

Good grammar, formal register, a mix of casual and formal, a single transition word like "However", unsourced claims. Do not degrade correct writing by inserting typos or slang to seem human.

## Example

Before (84 words):
> tidyfiles is a lightweight command-line tool that transforms your chaotic Downloads folder into an organized workspace in seconds. It seamlessly sorts files into tidy subfolders by type, including images, documents, archives, and videos. Fast, safe, and fully customizable, it offers a dry-run mode so you can preview every move, and a simple config file to define your own rules.

After (35 words):
> tidyfiles sorts your Downloads folder by file type. Run `tidyfiles ~/Downloads` and images, PDFs, archives and videos move into their own folders. `--dry-run` shows what would move first. Custom rules go in `~/.tidyfiles.toml`.
