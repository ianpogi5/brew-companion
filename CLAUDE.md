# Brew Companion — personal pour-over guide app

## Owner context
- User: beginner in pour-over, based in Philippines
- Grinder: Timemore C3 ESP (espresso variant — finer steps
  than regular C3, so pour-over settings sit coarser/further out)
- Brewer: generic glass cone dripper set with wooden stand +
  paper filters (V60-style technique applies)
- No scale yet (planned purchase); support both gram-based
  and spoon-approximation modes

## Beans in rotation
1. Excelsa (local, dark roast) — bold; prone to bitterness.
   ~1.8–2.0 rotations, water 88–92°C, brew 2:30–3:00
2. Ethiopian (light roast) — fruity/floral. ~1.6–1.8 rotations,
   water 93–96°C, brew 3:00–3:30
3. Barako — best brewed boiled (traditional Batangas style),
   coarse grind 2.5+ rotations, 1:12 ratio, sugar in pot
4. Beanhi (neighbor's local blend, whole beans) — reference
   "good cup"; grind setting TBD by matching their sample

## Features
- Bean picker → shows grind setting, ratio, temp for that bean
- Ratio calculator (1:15–1:16 default, adjustable)
- Guided pour timer: bloom (2x coffee weight, 30–45s), then
  circular pours to total time
- Taste troubleshooter: bitter → coarser/cooler/shorter;
  sour/weak → finer/hotter/longer
- Brew log: date, bean, rotations, ratio, temp, rating, notes
- Separate "kapeng barako (boiled)" mode with its own steps

## Tech preferences
- Single-page web app, mobile-first (used in kitchen on phone)
- Keep it simple; local storage for brew logs is fine
