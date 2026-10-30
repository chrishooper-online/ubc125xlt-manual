---
title: Batteries and Charging
tags: [ubc125xlt, getting-started, power]
aliases: [Charging, Battery Switch, Ni-MH, Charge Timer, Power]
---

# Batteries and Charging

## Power options
1. 2 × AA **Ni-MH** rechargeables (2.4 V) — supplied
2. 2 × AA **alkaline** (3.0 V) — not supplied
3. **USB** power, 5 V 500 mA, from a computer or USB adapter

## The battery switch
Inside the battery compartment is a switch marked **ALK** / **Ni-MH**. Set it with a pen tip to match the cells fitted.

> [!danger] Never charge alkalines
> Non-rechargeable batteries can get hot or burst if charged. Never fit alkalines with the switch on Ni-MH. Never use or charge **Ni-Cd** cells in this scanner.

Also:
- Don't mix old and new cells, different types, or rechargeables of different capacities.
- Remove weak cells — leaking batteries destroy circuits.

## Charging Ni-MH cells
1. Switch to **Ni-MH**, fit only Ni-MH cells.
2. **Turn the scanner off.** It only charges when off.
3. Connect the USB cable to the scanner and to a computer port (**not a USB hub**) or a USB charger.
4. The display shows `Charging`, then `Charge Complete`.

> [!note]
> Don't charge below 4 °C or above 45 °C. Charging takes longer if the scanner is in use.

The first time you connect to a computer, Windows may ask for a driver — see [[PC Programming]].

### Charge status messages
| Message | Battery | Meaning |
|---|---|---|
| `Charging` | Ni-MH | Charging in progress |
| `Charge Complete` | Ni-MH | Fully charged |
| `No Battery` | none | No cells fitted |
| `Charge Off` | Alk / Ni-MH | Not charging — switch is set to ALK |
| `Battery Error` | Ni-MH | Cells can't be charged (dead) |
| `Illegal Voltage` | Ni-MH | USB power is out of range |

If the scanner can't immediately tell whether the cells are good, it shows the battery icon while it checks. If it can't confirm they're good within 60 seconds, it stops and the icon blinks.

## Charge timer
Sets how long charging runs. **Default: 14 hours.** Range 1–14 hours.

`Func` → **power/backlight** key → *Set ChargeTime* → choose hours → `Pgm/E` → `.Clr` to exit.

| Cell capacity | Suggested max charge |
|---|---|
| 1500 mAh | 9 h |
| 1800 mAh | 11 h |
| 2000 mAh | 12 h |
| 2100 mAh | 13 h |
| 2200 mAh | 13 h |
| 2300 mAh (supplied) | 14 h |

> [!warning]
> The timer restarts every time you plug in the USB cable, or charge while it's already connected.

## Low battery
The battery icon blinks and a tone sounds every 15 seconds. Recharge or replace.

## Battery Save
After 1 minute with no transmission in Scan Hold or any Search Hold mode (without Priority or Close Call active), the receiver cycles off for 1 s and on for 300 ms to stretch battery life.

## Memory backup
Stored channels are kept for an extended time if power is lost.

---
Previous: [[Unboxing and Connections]] · Next: [[UK Listening Law]] · [[Home]]
