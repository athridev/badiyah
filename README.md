# Badiyah: Sands of the Ancients — البادية: رمال الأوّلين

A fully Arabic voxel sandbox set in the Arabian desert around **110 AH (≈728 CE)**.
Mine, build, ride, and survive with the tools people actually had.

**Play: [badiyah.athari.dev](https://badiyah.athari.dev)**

Everything is one self-contained `index.html` — no build step, no bundler, no
image or audio assets. Terrain, block textures, item icons, animal models and
sound effects are all generated procedurally in the browser. The only external
dependency is Three.js from a CDN.

## The world

A 160×64×160 seeded world of dunes, sandstone mesas and oases: date palms,
lakebed clay, copper and iron veins, and ruined mudbrick houses (أطلال) with a
tannur still standing and iron buried under the floor. Day and night run on an
eight-minute cycle with a crescent moon and stars.

## Historical accuracy

The tool and material progression was reviewed for period accuracy and
deliberately departs from the genre's usual ladder:

- **No stone-tool tier.** Iron was universal in 8th-century Arabia and stone
  tools were two millennia gone. The first tier is **copper (نُحاس)**, which
  genuinely coexisted with iron for cheaper implements.
- **No coal ore.** Nobody was mining mineral coal here. **فحم is charcoal**,
  burnt from palm logs — which is how the fuel was actually made.
- **مِسْحاة is iron by definition** in the classical lexica, so the copper spade
  is a مِجْرَفة and مِسْحاة is reserved for the iron one.
- The **tannur (تَنُّور)** is a real kiln: it must be standing nearby to smelt
  iron, fire آجُرّ brick, or burn جِصّ plaster.

Blocks and tools use their classical Arabic names throughout — لَبِن، آجُرّ،
جِصّ، سَعَف، مِعْوَل، فأس، مِنْجَل، قَدُوم — and the UI is right-to-left with
Arabic-Indic numerals.

## Horses and camels

Arabian horses (خيل) roam the green oasis edges in four classical coat colours —
كُمَيت، أشقر، أشهب، أدهم — and dromedary camels (إبل) wander the open dunes.
Aim at one and right-click to ride. A wild mount will throw you; feed it three
dates (تمر) and it settles. Horses are fast and jump well; camels are slower,
taller and unbothered by sand.

## Controls

| | |
|---|---|
| `W A S D` | move |
| `W W` | sprint (double-tap) |
| mouse / arrows | look |
| left click | mine (hold) |
| right click | build, eat dates, ride an animal |
| `Space` | jump / swim |
| `Shift` | sprint, or dismount |
| `E` | inventory and crafting |
| `1`–`9` / wheel | select slot |
| `Esc` | pause |

Creative mode is toggled from the pause menu: everything is unlimited, nothing
can hurt you, and double-tapping `Space` lets you fly.

## Running locally

Any static file server works, or just open the file directly:

```bash
python3 -m http.server 8137 -d .
```

## Licence

© Adam Jaljoli. All rights reserved.
