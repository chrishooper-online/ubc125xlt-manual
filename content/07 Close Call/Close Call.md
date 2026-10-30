---
title: Close Call
tags: [ubc125xlt, close-call, concepts]
aliases: [Close Call RF Capture, CC, Close Call Only, RF capture]
---

# Close Call

## What it does
A normal search tunes frequency by frequency, listening for activity. **Close Call** instead **detects a strong nearby signal directly and tunes to it**. It's how you find out what a handheld radio near you is using — at airshows, motorsport, marinas, events.

## Works well / works poorly
| Good | Poor |
|---|---|
| Handheld and mobile two-way radios close by | Areas full of strong transmitters (pager masts, multi-use towers, traffic systems) |
| Places with few other strong sources | Highly directional antennas (e.g. amateur beams) |
| | Many transmitters at once |
| | TV broadcast stations |

## Close Call modes
Set via `Func` → `Hold` → *Close Call Mode* ([[Close Call Menu]]):

| Mode | Behaviour |
|---|---|
| Close Call Off | Disabled |
| Close Call DND | Checks for hits **between** transmissions — no interruptions (on by default after reset) |
| Close Call Pri | Checks every 2 s, **even during** a transmission |
| Close Call Only | Does nothing but Close Call, continuously |

DND and Pri run in the background of Scan and Search, and show the Close Call icon.

## Close Call Only mode
- Top line `Close Call`; `CC Search` scrolls on line two; the icon blinks
- Keys `1`–`6` toggle the six [[Close Call Menu#Close Call Bands|bands]]; at least one must stay on, otherwise `All Band Off!`
- `Hold`, then turn the knob, to sit on one band

When it finds a signal: `CC Found!`, plus a beep and/or flash if [[Close Call Menu#Close Call Alert|alerts]] are on. Press any key except `Hold` to see the frequency.

| Do | How |
|---|---|
| Hold on the hit | `Hold` |
| Quick Search from here | In Hold, turn the knob, then `Hold` — see [[Quick Search]] |
| Dismiss the hit | Turn the knob |
| Lock out | `L/O` once / twice — see [[Lockouts]] |
| Store | `Pgm/E` — see [[Storing Found Frequencies]] |
| Exit | `Scan` (or `Srch/Svc`) |

## Close Call Hits bank
The **last 10 hits** from any Close Call mode are kept in a temporary bank, **Close Call Hits**. They're lost at power-off — [[Storing Found Frequencies|store]] any you want to keep. Turn on *Scan Hits* to have them included in Scan.

> [!note]
> Close Call operates from −10 °C to +50 °C. It needs a strong signal — see the sensitivity figures in [[Specifications]].

---
Previous: [[Storing Found Frequencies]] · Next: [[Close Call Menu]] · [[Home]]
