---
title: Delay
tags: [ubc125xlt, channels, scanning]
aliases: [Channel Delay, Search Delay, Resume, Scan delay]
---

# Delay

Controls what happens when a transmission **ends** (positive) or how long to **listen** before moving on (negative). **Default: 2 s.**

| Setting | Behaviour |
|---|---|
| −10 sec | Listen for 10 s, then resume even if still talking |
| −5 sec | Listen for 5 s, then resume |
| 0 sec | Resume immediately when the signal drops |
| 1–5 sec | Wait that long for a reply, then resume |

> [!tip] When to use which
> - **2–3 s** for conversations: you hear both sides.
> - **0 s** for busy data-like channels you only want to glance at.
> - **Negative** for channels that transmit constantly — the scanner samples them and moves on.

## Where to set it
| Applies to | Path |
|---|---|
| One channel | `Hold` → channel → `Pgm/E` → *Set Delay* |
| All searches **and** Close Call | `Func` → `Pgm/E` in any search → *Set Delay* ([[Search Menu]]) |
| Close Call **and** all searches | `Func` → `Hold` → *Set Delay* ([[Close Call Menu]]) |

The search delay and Close Call delay are the same setting, reachable from two menus.

---
Previous: [[Modulation and Step]] · Next: [[Deleting Channels and Banks]] · [[Home]]
