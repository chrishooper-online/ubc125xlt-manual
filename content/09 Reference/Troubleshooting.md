---
title: Troubleshooting
tags: [ubc125xlt, reference, troubleshooting]
aliases: [Problems, Error messages, Birdies, Fault finding]
---

# Troubleshooting

> [!info]
> Uniden's manual has no troubleshooting table. This page gathers the messages and fixes scattered through it.

## Display messages
| Message | Cause | Fix |
|---|---|---|
| `Nothing to Scan` | All channel banks switched off | Press a bank's number key — [[Banks]] |
| `Nothing to Srch` | All search or service banks off | Press a bank's number key |
| `All Band Off!` | All Close Call bands off in Close Call Only | Press `1`–`6` — [[Close Call Menu]] |
| `All Locked!` | Every channel/frequency in the bank is locked out | Unlock some — [[Lockouts]] |
| `Out of Band` (3 beeps) | Frequency outside coverage | See [[Frequency Range Tables#Gaps]] |
| `Frequency Exists – Confirm?` | Already stored elsewhere | `Pgm/E` to store anyway, `.Clr` to cancel |
| `Priority Scan No Channel` | No priority channel in enabled banks | [[Priority Scanning\|Set one]] |
| `Charge Off` | Battery switch on ALK | Set to Ni-MH if using rechargeables — [[Batteries and Charging]] |
| `No Battery` | No cells fitted | Fit cells |
| `Battery Error` | Ni-MH cells dead | Replace cells |
| `Illegal Voltage` | USB power out of range | Use a computer port (not a hub) or a different charger |
| `All Memory Clear` | Factory reset done | — [[Factory Reset]] |
| Blinking battery + beep every 15 s | Battery low | Recharge or replace |

## Common problems
| Problem | Try |
|---|---|
| Won't charge | Scanner must be **off**; switch on Ni-MH; computer port, not hub; check `Set ChargeTime` |
| Never reaches `Charge Complete` | Charge timer may end first, or the scanner was in use — check the timer setting for your cell capacity |
| Stops but no sound | A birdie (below), or a [[CTCSS and DCS\|tone]] mismatch on that channel |
| Stops on noise everywhere | Raise [[Volume and Squelch\|squelch]] |
| Misses weak stations | Lower squelch; use an external antenna — [[Unboxing and Connections]] |
| Hears several users on one channel | Set the channel's CTCSS/DCS tone |
| Can't select FM on air band | By design — air band is AM only |
| Step or modulation change didn't stick | Search step and most modulation changes reset at power-off — [[Modulation and Step]] |
| Keys don't respond | Keypad lock — `Func` → `L/O` |
| Close Call finds the wrong thing or nothing | Too many strong transmitters nearby — see [[Close Call#Works well / works poorly]] |
| Locked-out channels came back | Temporary lockouts clear at power-off; lock out twice for permanent |

## Birdies
Every receiver produces some internal signals. If the scanner stops with no audio, it may be a **birdie**. On the UBC125XLT they cluster at **multiples of 16 MHz** (e.g. 32 MHz, 480 MHz) from the internal CPU clock.

Fix: [[Lockouts|lock out]] the frequency.

---
Previous: [[Tone and Code Tables]] · Next: [[Glossary]] · [[Home]]
