# Orbit Nova

A celestial arena survivor for the browser, built for CrazyGames (SDK v3 integrated). Everything is drawn from basic shapes on a 2D canvas, set in Exo 2, with no 3D and no external art.

**You are a newborn star. Your mass is your life.** It burns away every second, and only the swarm you shatter can feed it. More mass means a wider glow, longer reach and harder hits, but it also draws more of the void.

- **Your star grows more complex as it levels:** Spark → Star → Giant → Pulsar → Galaxy. Each stage adds rays, orbiting moons, beams and spiral arms, plus +6% damage
- 6 stars (Sol, Nova, Luna, Vega, Sirius, Quasar), each built on its own primitive: circle, 4-point star, crescent, triangle, diamond, hexagon
- 8 weapons that can evolve (max weapon + its paired passive), and 8 passives
- 9 swarm types: asteroids, pebbles, ice comets, dwarf moons, space jellies, binary pairs, satellites, meteors, and dark matter that only shows inside your glow. All are shaded by your star and pick up orbiting moonlets as the run goes on
- 3 multi-phase bosses: The Obelisk (3:00), The Eclipse (6:00), Event Horizon (10:00). Beat Event Horizon to ascend
- Earn shards each run and spend them in **The Forge** or on new stars
- Move: WASD / arrows / hold left mouse / drag. Dash (brief invulnerability): Space / Shift / right-click. Pause: P. Mute: M

| Evolution | Weapon + Passive |
|---|---|
| Lunar Cascade | Orbiting Moons + Gravity |
| Starburst | Star Shot + Spin |
| Plasma Storm | Ion Arc + Alignment |
| Supernova | Pulsar Wave + Density |
| Solar Flare | Corona + Magnetosphere |
| Comet Tide | Comets + Accretion |
| Starfall | Meteor Shower + Tidal Pull |
| Eclipse Ring | Saturn Ring + Solar Wind |

## Run
Open `index.html`. It is a single self-contained file. For SDK testing use a local server, e.g. `npx serve`.

## Ship to CrazyGames
Zip `index.html` and upload via the Developer Portal.
