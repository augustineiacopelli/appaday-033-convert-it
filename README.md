# Convert It — AppADay #033

**Live App:** https://augustineiacopelli.github.io/appaday-033-convert-it/

Part of the [AppADay](https://augustineiacopelli.github.io/appaday/) project — one complete web app, every day.

## What It Does

Convert It is an instant unit converter covering 8 categories: Length, Weight, Temperature, Volume, Speed, Area, Data, and Time. Select a category tab, choose your from and to units, type a value, and the result updates instantly. A swap button flips the units in one tap. A formula line shows the base conversion factor so the math is always visible.

## Categories

| Category | Units |
|---|---|
| Length | mm, cm, m, km, in, ft, yd, mi |
| Weight | mg, g, kg, t, oz, lb, st |
| Temperature | °C, °F, K |
| Volume | ml, l, fl oz, cup, pt, qt, gal, m³ |
| Speed | mph, kph, m/s, knots, fps |
| Area | mm², cm², m², km², in², ft², acres, hectares |
| Data | bits, bytes, KB, MB, GB, TB |
| Time | ms, s, min, hr, day, wk, mo, yr |

## Technical Notes

- Single-file vanilla HTML/CSS/JS — no frameworks, no dependencies
- Temperature uses direct formula conversion (not base-unit scaling)
- All other categories use a base-unit scaling approach for accuracy
- Mobile-friendly: 16px inputs prevent Safari zoom, tap targets sized correctly

## Stack

HTML · CSS · JavaScript

---

*AppADay — Ship something every day. It compounds.*
