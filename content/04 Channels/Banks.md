---
title: Banks
tags: [ubc125xlt, channels, concepts]
aliases: [Channel Banks, Storage Banks, Service Banks, Search Banks, Bank]
---

# Banks

The scanner uses three kinds of bank. In each mode, the **number keys switch banks on and off**, and the enabled ones show along the bottom of the [[Display Icons|display]].

## Channel storage banks — 10 × 50 = 500 channels
| Bank | Key | Channels |
|---|---|---|
| 1 | `1` | 1–50 |
| 2 | `2` | 51–100 |
| 3 | `3` | 101–150 |
| 4 | `4` | 151–200 |
| 5 | `5` | 201–250 |
| 6 | `6` | 251–300 |
| 7 | `7` | 301–350 |
| 8 | `8` | 351–400 |
| 9 | `9` | 401–450 |
| 10 | `0` | 451–500 |

Group them however suits you — by service, place or interest. Each bank can hold one [[Priority Scanning|priority channel]].

**Close Call Hits** is an extra, temporary bank holding the last 10 [[Close Call]] finds. Toggle it during Scan with `.Clr`.

> [!tip] Plan your banks
> Fill the [[Channel Log Template]] before programming. A common layout: 1 air, 2 marine, 3 amateur, 4 PMR446, 5 CB… leaving later banks for finds.

## Service search banks — 7
Built-in frequency lists: Emergency, Freenet, PMR, Marine, Aircraft, CB, HAM. Toggled with `1`–`7` in [[Service Search]].

## Custom search banks — 10
User-defined ranges, toggled with `1`–`9`, `0` in [[Custom Search]].

## Rules
- At least one bank must stay enabled. Turn them all off and you'll see `Nothing to Scan` or `Nothing to Srch`.
- In Close Call Only mode, keys `1`–`6` toggle the six [[Close Call Menu#Close Call Bands|Close Call bands]].

---
Previous: [[Factory Reset]] · Next: [[Programming a Channel]] · [[Home]]
