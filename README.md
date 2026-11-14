# Ore Drift

Mine glowing asteroids, upgrade your rig and buy your way out of the belt while other prospectors fly beside you online.

**▶ Play:** https://elivoronov-ctrl.github.io/ore-drift/

A 3D arcade mining game (Three.js) with live online multiplayer.

## Progression
- **Credits and upgrades:** sell ore at Station Argent and spend the credits on six upgrade lines (Mining Laser, Cargo Hold, Thrusters, Hull Plating, Ore Magnet, Deflector shield), each with 5 levels.
- **Ranks 1–10:** your rank goes up as your lifetime earnings grow.
- **Four zones**, each further out and richer than the last:
  1. **The Shallows**: iron and copper, safe.
  2. **Cobalt Drift**: cobalt, plus meteor storms.
  3. **Gilded Belt**: gold, plus pirate drones that shoot back.
  4. **Plasmite Abyss**: plasmite, proximity mines and heavy pirate traffic.
- **Win:** buy the Warp Drive for 30,000 cr. **Lose:** your hull reaches zero.

## Controls
| Action | Keyboard | Mouse / Touch |
|---|---|---|
| Steer | A / D or ← / → | Virtual stick (left/right) |
| Thrust / brake | W / ↑, S / ↓ | Stick up / down |
| Mining laser | Space (hold) | Hold left mouse / MINE button |
| Dock (at station) | E / Enter | DOCK button |
| Pause | P / Esc | II button |
| Mute | M | |

## Multiplayer
Enter a pilot name and launch. Everyone online shares the same belt through Supabase Realtime (broadcast and presence only, no database). You see the other ships, their mining lasers, an online count and a live earnings leaderboard. Asteroids are local to each player. If the connection fails, the game plays solo.

High score (best career earnings) is saved in localStorage.
