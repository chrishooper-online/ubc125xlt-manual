---
title: CTCSS and DCS
tags: [ubc125xlt, channels, concepts]
aliases: [CTCSS, DCS, PL, DPL, Tone squelch, Sub-audible tones]
---

# CTCSS and DCS

## What they are
**CTCSS** (Continuous Tone-Coded Squelch System) and **DCS** (Digital Coded Squelch) add an inaudible tone or code to an FM transmission. Motorola calls them PL and DPL.

They let a radio — or your scanner — **open squelch only when the right tone arrives**. Uses:
- Repeater access control
- Filtering out other users sharing or near the same frequency

The scanner recognises **50 CTCSS tones** and **104 DCS codes**: [[Tone and Code Tables]]. FM only.

## Per-channel setting
`Hold` → channel → `Pgm/E` → **Set CTCSS/DCS**

| Option | Squelch opens when… |
|---|---|
| Off *(default)* | Any signal — tones ignored |
| CTCSS | The chosen tone is present (you're then asked for the tone) |
| DCS | The chosen code is present (you're then asked for the code) |
| CTCSS/DCS Search | Any signal — and the tone/code in use is **displayed** |
| No Tone | Only signals with **no** tone or code |

> [!tip] Finding the tone
> Set the channel to **CTCSS/DCS Search**, wait for a transmission and read the tone off the display (it blinks while searching). Then set the channel to that exact tone to filter out everyone else.

## In search and Close Call
Tone search is a separate on/off setting, **default On**, shared by search and Close Call. See [[Search Menu]] and [[Close Call Menu]].

---
Previous: [[Text Tags]] · Next: [[Modulation and Step]] · [[Home]]
