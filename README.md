# 3D Print Pricing

Price your 3D print jobs from real production costs. Built by JakinsCraft.

🌐 Web app: https://pappyakins.github.io/3d-print-cost/
📱 Android APK: see [Releases](../../releases)

## What it prices

Every production factor that eats into a print job:

- **Filament** — presets (PLA, PETG, ABS, ASA, TPU, Nylon, PC) with editable $/kg, grams from your slicer
- **Electricity** — printer watts × print hours × your $/kWh
- **Machine wear** — printer cost ÷ lifespan hours
- **Labor** — design time (one-off, spread across quantity) + post-processing per unit
- **Failed prints / waste %** allowance
- **Post-processing materials** (paint, glue, sandpaper…), **packaging**, **overhead**

## Sell prices

Two margin tiers, margin-on-selling-price:

- 👍 **Very good** — 50% margin
- ⭐ **Ideal** — 70% margin

Each with a $x.99 charm-price option and job revenue/profit math.

## Invoices

Business name + tagline (editable in Settings, saved as text), invoice numbering,
bill-to, HST toggle, notes, custom logo upload — export a real PDF through the
Android native share sheet.

## Data

No account, no server. Everything (settings, projects, presets) stays in
localStorage on your device.

## Android build

Capacitor project in `android/` (`com.jakinscraft.print3dcost`). Release APKs are
attached to each GitHub release.
