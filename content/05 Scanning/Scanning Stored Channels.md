---
title: Scanning Stored Channels
tags: [ubc125xlt, scanning, how-to]
aliases: [Scan, Scan mode, Scanning]
---

# Scanning Stored Channels

Press **`Scan`**.

The scanner runs through every **unlocked** channel in every **enabled** [[Banks|bank]], in channel order, at up to 80 channels a second. It stops on activity and resumes after the channel's [[Delay]].

After the normal banks, it scans the **Close Call Hits** bank, if that's enabled and not empty.

## The display while scanning
- Top line: current bank
- Second line: `SCAN` scrolling, with ↑ or ↓
- Bottom: enabled bank numbers; the one being scanned flashes

## Controls

| Do | How |
|---|---|
| Toggle banks | `1`–`9`, `0` |
| Toggle Close Call Hits bank | `.Clr` |
| Skip a long transmission / reverse direction | Turn the [[Scroll Control]] or press `Scan` |
| Stay on a channel | `Hold` — see [[Hold and Manual Selection]] |
| Temporary lockout | `L/O` once |
| Permanent lockout | `L/O` twice quickly — see [[Lockouts]] |

## When it stops on a signal
- Top line: bank and channel number, or its [[Text Tags|tag]]
- Second line: scanner channel number and frequency
- **P** if it's a priority channel, plus modulation, priority and Close Call icons
- Any CTCSS/DCS tone: blinking if it's searching for tones, solid if programmed

> [!warning] `Nothing to Scan`
> All banks are switched off, or nothing is programmed. Turn a bank on with its number key.

---
Previous: [[Deleting Channels and Banks]] · Next: [[Hold and Manual Selection]] · [[Home]]
