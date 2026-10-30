# CLAUDE.md — UBC125XLT Manual vault

Guidance for Claude when working in this folder.

## What this is
An Obsidian vault holding a linked, searchable manual for the **Uniden Bearcat UBC125XLT** handheld scanner, **European/UK edition**. It is based on Uniden's owner's manual (UB374ZV, 2013), rewritten as short, linked notes. `Home.md` is the index (map of content).

## Folder structure
Numbered folders in reading order — keep the numbering:

| Folder | Contents |
|---|---|
| `01 Getting Started` | Quick start, unboxing, batteries, UK listening law |
| `02 The Scanner` | Keys, display, scroll knob, operating modes |
| `03 Setup` | Band plans, volume/squelch, display menu, keypad lock, reset |
| `04 Channels` | Banks, programming, channel menu, tags, CTCSS/DCS, delay |
| `05 Scanning` | Scanning, hold, priority, lockouts |
| `06 Searching` | Service, custom, quick search, search menu, storing finds |
| `07 Close Call` | Close Call and its menu |
| `08 PC Programming` | USB driver and software |
| `09 Reference` | Menu map, specs, frequency/tone tables, troubleshooting, glossary |
| `Templates` | Channel Log Template |

## Note conventions
Every note follows this pattern:

1. **YAML frontmatter**
   ```yaml
   ---
   title: Note Title            # matches the file name
   tags: [ubc125xlt, <section>, <kind>]
   aliases: [Other names people might search for]
   ---
   ```
   - First tag is always `ubc125xlt`.
   - Section tags: `getting-started`, `scanner`, `setup`, `channels`, `scanning`, `searching`, `close-call`, `pc-programming`, `reference`.
   - Kind tags (optional): `how-to`, `concepts`, `menu`, `reference`, `troubleshooting`, `template`, `moc`.
2. **One `# H1`** matching the title, then `##` sections.
3. **Footer** — a horizontal rule, then previous/next links in reading order and a link home:
   ```
   ---
   Previous: [[Prev Note]] · Next: [[Next Note]] · [[Home]]
   ```

## Writing style
- UK English spelling (colour, organise, licence) and UK context (Ofcom, PMR446, UK band plans).
- Short, plain sentences. Numbered steps for procedures; tables for reference data.
- Keys in backticks exactly as printed: `Func`, `Hold/CC`, `Srch/Svc`, `Pgm/E`, `L/O`, `.Clr`, `Scan`. Display text in backticks too: `Charging`, `Charge Complete`.
- Two-key combos written as "press `Func`, then `Hold`".
- Frequencies in MHz with three decimals where relevant (`145.500`).
- Use Obsidian callouts: `[!tip]`, `[!note]`, `[!info]`, `[!warning]`, `[!danger]`.
- Link generously with wikilinks by note name (`[[Close Call]]`, `[[Priority Scanning|priority channel]]`). Escape the pipe inside tables: `[[Priority Scanning\|priority]]`.

## Accuracy
- Facts must come from the UBC125XLT owner's manual (UK edition) or a reliable source. Don't guess at key sequences, menu names, ranges or defaults — if unsure, say so in the note or ask.
- Keep the UK edition in mind: band plans, service banks and frequency coverage differ from the US model.
- `UK Listening Law` is a summary, not legal advice — keep that framing and its sources.

## When adding or changing notes
- Put the note in the correct numbered folder with full frontmatter and footer.
- Add it to `Home.md` under the right section with a one-line description.
- Update the previous/next footers of its neighbours so the reading chain stays unbroken.
- If it introduces a menu or term, update `09 Reference/Menu Map.md` and/or `Glossary.md`.
- Don't rename notes without updating every wikilink to them.
- Don't touch `.obsidian/` settings.
