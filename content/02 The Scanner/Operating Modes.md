---
title: Operating Modes
tags: [ubc125xlt, scanner, concepts]
aliases: [Modes, Scanning vs Searching, Scan vs Search]
---

# Operating Modes

## Scanning vs searching
- **Scanning** steps through frequencies you've **stored** in channels. It pauses on activity and moves on when the transmission ends.
- **Searching** steps through a **range** of frequencies you haven't stored, looking for anything active. Found something good? [[Storing Found Frequencies|Store it]].

## The modes

| Mode | Start with | What it does |
|---|---|---|
| [[Scanning Stored Channels\|Scan]] | `Scan` | Cycles through unlocked channels in enabled banks |
| [[Hold and Manual Selection\|Scan Hold]] | `Hold` | Stays on one channel |
| [[Custom Search]] | `Srch/Svc` | Searches your 10 user-defined ranges |
| [[Service Search]] | `Func` → `Srch/Svc` | Searches the 7 built-in service bands |
| [[Quick Search]] | `Hold`, type a frequency with a decimal point, `Hold` | Searches up/down from that frequency |
| [[Close Call\|Close Call Only]] | `Func` → `Hold` → *Close Call Mode* → *Close Call Only* | Jumps straight to strong nearby signals |

Each search mode also has a Hold state (press `Hold`).

## Layers on top
These work alongside Scan and Search:
- [[Priority Scanning]] — checks favourite channels every 2 seconds
- [[Close Call]] DND / Priority — checks for nearby transmitters in the background

## Conventional systems
The UBC125XLT is an **analogue conventional** scanner: each user group sits on fixed frequencies.
- **Simplex** — one frequency for talk and listen. Line-of-sight, typically 1–8 miles. Building sites, PMR446 handhelds.
- **Repeater** — radios transmit on an *input* frequency; a high-mounted repeater rebroadcasts on an *output* frequency, typically covering about 35 km. Program the **output** frequency to hear everyone.

It does not follow trunked or digital systems.

---
Previous: [[Scroll Control]] · Next: [[Band Plans]] · [[Home]]
