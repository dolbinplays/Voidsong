# Voidsong Prototype

v0.26.05.23.1431 - Battle Theater

A single-file browser prototype for a space-fantasy tactical RPG inspired by the Sega Genesis era: army preparation, commanders, hired troop squads, class paths, terrain bonuses, rock-paper-scissors matchups, spells, equipment bonuses, phase-aware music, visible enemy turns, and cinematic troop-specific battle theater.

## Run Locally

Open `index.html` in a browser.

## Host On GitHub Pages

1. Put `index.html` at the root of a GitHub repository.
2. In GitHub, open the repository settings.
3. Enable Pages from the main branch root.
4. Visit the published GitHub Pages URL.

## Prototype Notes

- The current art is layered paper-doll style made in HTML and CSS.
- Mission 1 is "The Fall of Lyra Gate."
- The War Council screen lets the player spend a shared 240-crown treasury on troop hires.
- Commanders can choose class paths: Guardian, Blade, or Astral.
- Relics and class paths now affect attack, defense, morale, and spell power.
- The soundtrack is extracted under `assets/music/Soundtrack`.
- All 20 heroic Genesis rock tracks are available for player-side moments.
- All 10 evil ominous Genesis rock tracks are available for enemy phase and bad-guy pressure.
- Enemy phase now resolves one unit at a time with map highlights, pauses, movement beats, and attack beats.
- Battle scenes now vary by troop type: archers volley, pikes brace, beasts lunge, and melee troops charge.
- Battle scenes include commander labels, matchup captions, and damage popups.
- The player wins by surviving 6 turns or routing Lord Varkos.
- The player loses if Prince Cael is routed or an enemy reaches the western escape gate.
- Deployment lets each commander choose a troop squad and relic before the mission starts.
- The battle window mirrors the tactical tile terrain.
- Prince Cael has an arm-mounted Star Glaive with shield and thrown-glaive actions.
- This is intentionally static and dependency-free so it can be hosted anywhere.
