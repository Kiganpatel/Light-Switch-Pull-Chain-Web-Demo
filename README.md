# Light-Switch-Pull-Chain-Web-Demo

pull a braided rope to toggle a hanging Edison bulb. grab the bulb and throw it around.

[live demo](https://kiganpatel.github.io/Light-Switch-Pull-Chain-Web-Demo/)

## What's In It
- Verlet rope physics on the pull cord — drag it in any direction
- Free 2D pendulum on the bulb with real angular momentum
- Dynamic shadow casting from furniture onto the floor and walls, shifts as the bulb swings
- Dust motes that only appear inside the light cone
- Moths that orbit the bulb when the light's on
- Procedural Web Audio — click, electrical hum, bulb pop, rope swish
- Floorboards with per-plank light reflections

## What it looks like
<img width="1436" height="884" alt="Screenshot 2026-03-10 163829" src="https://github.com/user-attachments/assets/5cad5acc-ec94-4186-9317-3814380df97d" />

## Credits
- [Thomas Jakobsen](https://www.cs.cmu.edu/afs/cs/academic/class/15462-s13/www/lec_slides/Jakobsen.pdf) — his 2001 paper "Advanced Character Physics" is basically the bible for this kind of Verlet rope sim
- [Daniel Shiffman / The Coding Train](https://thecodingtrain.com) — his chain/pendulum videos made the constraint solver click for me

