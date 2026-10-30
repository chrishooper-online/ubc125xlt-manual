---
title: Custom Search
tags: [ubc125xlt, searching, how-to]
aliases: [Custom search ranges, Search limits, Program Limits, Srch]
---

# Custom Search

Searches up to **10 ranges you define**. Each runs from its lower to its upper limit.

**Start:** `Srch/Svc`

## Factory ranges
| Bank | Key | Range (MHz) | Covers |
|---|---|---|---|
| 1 | `1` | 25.0000 – 27.9999 | HF / CB 27 MHz |
| 2 | `2` | 28.0000 – 30.1999 | 10 m amateur |
| 3 | `3` | 30.2000 – 49.9999 | VHF low |
| 4 | `4` | 50.0000 – 88.0000 | 6 m / 4 m, VHF low |
| 5 | `5` | 108.0000 – 136.9999 | Civil air band |
| 6 | `6` | 137.0000 – 143.9999 | Satellites, VHF |
| 7 | `7` | 144.0000 – 174.0000 | 2 m amateur, marine, VHF high |
| 8 | `8` | 225.0000 – 399.9999 | Military air band |
| 9 | `9` | 400.0000 – 512.0000 | UHF, 70 cm, PMR446 |
| 10 | `0` | 806.0000 – 960.0000 | 800/900 MHz |

## Change a range
1. In Custom Search: `Func` → `Pgm/E` (opens the [[Search Menu]])
2. **Program Limits** → `Pgm/E`
3. Choose **Search Bank 1–10** → `Pgm/E`
4. **Lower** → `Pgm/E` → type the frequency → `Pgm/E`
5. **Upper** → `Pgm/E` → type the frequency → `Pgm/E`
6. `.Clr` to go back; repeat for other banks; `Srch/Svc` to start

> [!example] Narrow it down
> Searching all of 144–174 MHz takes a while. To find activity on, say, the 2 m amateur band only, set a bank to 144.0000 – 146.0000.

## While searching
Same controls as [[Service Search]]: number keys toggle banks, knob or `Srch/Svc` skips/reverses, `Hold`, `Pgm/E` to store, `L/O` to lock out.

Turbo Search kicks in automatically on 5 kHz-step bands, roughly tripling speed.

---
Previous: [[Service Search]] · Next: [[Quick Search]] · [[Home]]
