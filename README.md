# Starveil

A celestial arena survivor for the browser, built for CrazyGames (SDK v3 integrated). Everything is drawn from basic shapes on a 2D canvas, set in Exo 2, with no 3D and no external art.

**You are a newborn star. Your mass is your life.** It burns away every second, and only the swarm you shatter can feed it. More mass means a wider glow, longer reach and harder hits, but it also draws more of the void.

- **Your star grows more complex as it levels:** Spark → Star → Giant → Pulsar → Galaxy. Each stage adds rays, orbiting moons, beams and spiral arms, plus +6% damage
- 6 stars (Sol, Nova, Luna, Vega, Sirius, Quasar), each built on its own primitive: circle, 4-point star, crescent, triangle, diamond, hexagon
- 8 weapons that can evolve (max weapon + its paired passive), and 8 passives
- 9 swarm types, all wayward stars: red dwarfs, stellar cinders, shooting stars, red giants, cepheids (pulsing variable stars), binary stars, pulsars that lock their beams on you, flare stars that erupt and charge, and black dwarfs that only show inside your glow. Each burns with its own corona and picks up orbiting planets as the run goes on
- 6 late-run stars with their own attacks: white dwarfs, Wolf-Rayet stars (radial bursts), magnetars (pull you in), stellar nurseries (spawn cinders), recurrent novas (shock rings) and quasars (sweeping jets)
- **Threat scaling:** every upgrade past your starting kit makes the swarm tougher, faster and denser (shown as THREAT on the HUD)
- Red giants go supernova when they die, and solar flares erupt under you (and ahead of you) all run long, so standing still gets you burned
- **Star Atlas** on the menu: every enemy and boss with its behaviour, a counter-tip and your lifetime tally. Stars stay locked until they first enter your glow
- **Never stand still:** linger inside one small patch of sky for 3 seconds and the Veil starts closing in. Your mass burns several times faster and solar flares rain down on you until you move
- A leaner swarm (at most 110 on screen) where each star is sturdier and quicker, so runs stay hard without the lag. Mass refills (+25) are rare
- **Opening cutscene** on your first run and before the tutorial (skippable, and replayable from INTRO on the menu)
- **Interactive tutorial** on your first run (or any time from HOW TO PLAY) that flows straight into the real run
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
