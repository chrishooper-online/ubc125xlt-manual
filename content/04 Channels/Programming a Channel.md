---
title: Programming a Channel
tags: [ubc125xlt, channels, how-to]
aliases: [Store a frequency, Enter Frequency, Program channel]
---

# Programming a Channel

At least one channel must be programmed before [[Scanning Stored Channels|scanning]] works.

## Steps
1. Press **`Hold`**, type the channel number (1–500), then press **`Pgm/E`** to open the [[Channel Menu]].
   *Alternative:* press `Hold`, turn the knob to the channel, then `Func` → `Pgm/E`.
2. Choose **Enter Frequency**, press `Pgm/E`. The current channel and frequency show.
3. Type the frequency with the number keys, using **`.Clr` as the decimal point** (e.g. `156.800`). Mistake? `.Clr` clears it.
4. Press **`Pgm/E`** to store.
5. Set any other options in the [[Channel Menu]], then press `.Clr` to back out.

## Shortcut
In Scan Hold, just type a frequency and press `Pgm/E` to store it quickly.

## What the scanner checks

| You see | Meaning | Do |
|---|---|---|
| Frequency changes slightly | Rounded to the nearest valid step (e.g. 151.473 → 151.475) | Nothing |
| `Out of Band` + 3 beeps | Outside coverage — see [[Specifications]] | `.Clr`, re-enter |
| `Frequency Exists – Confirm?` with a channel number | Already stored elsewhere | `Pgm/E` to store anyway, `.Clr` to change |

If there are several duplicates, it shows one in the same bank first, otherwise the lowest-numbered.

> [!tip]
> Default modulation and step come from the [[Band Plans|band plan]]. Air band (108–137 MHz) is always AM.

## Faster ways
- [[Storing Found Frequencies]] — save directly from a search or Close Call hit
- [[PC Programming]] — type hundreds of channels at a keyboard

---
Previous: [[Banks]] · Next: [[Channel Menu]] · [[Home]]
