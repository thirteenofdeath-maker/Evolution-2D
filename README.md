# Evolution 2D — Battle Royale (Mobile Demo)

A mobile-browser AI Battle Royale inspired by the original `งู3.py`.

## Play

After GitHub Pages deployment, visit: https://thirteenofdeath-maker.github.io/Evolution-2D/

## Core game loop

1. **SEARCHING:** Start with two creatures. AI searches for weapons and food. Eating food creates an offspring with inherited, slightly mutated DNA.
2. **BATTLE:** Once the population reaches **10**, food is cleared, combat starts, and AI fights automatically. A shrinking storm encourages decisive fights.
3. **WINNER:** The last surviving creature wins and receives permanent HP and Power bonuses.
4. **NEXT ROUND:** The champion survives into the next round with a fresh opponent. The process repeats.

## Features

- 100% autonomous AI combat with hunting, cautious retreat, weapon range and cooldowns
- Food, reproduction, mutation, generations and basic traits
- Weapons: fist, knife, gun, bow, shield, green weapon
- Tier progression: Normal → Purple → Fire → Golden through kills
- Persistent champion from round to round
- Pause, 1×/2×/4×/8× speed, touch pan/zoom, creature inspector
- Local browser save/load

## Limitations

A playable **prototype** rather than a feature-complete port. It doesn't yet reproduce the original game's snake encounters, special gem rules, projectile physics, A* obstacle avoidance, full tier unlock logic or full battle effects. Mobile QA and game balance remain to be verified.

## Deploy

Repository **Settings → Pages → Source: GitHub Actions**. The workflow `.github/workflows/pages.yml` deploys on pushes to `main`.
