# SpydermanLock

A reverse-engineered, buildable rotary multi-point latch inspired by a forgotten cinematic mechanism and rebuilt as a modern mechanical/electronic system.

## Project direction

The mechanism is intentionally designed as a **real, manufacturable object**, not only as a visual prop.

### Material philosophy

The functional and visible mechanical parts should be **predominantly aluminum**:

- front plate: aluminum
- rotary hub: aluminum
- hand lever: aluminum
- rear cam: aluminum for prototype, steel/stainless option for high-wear builds
- receiver/strike: aluminum prototype or stainless steel for durability
- shaft: stainless steel recommended
- LED diffuser: translucent polycarbonate/acrylic

The rotary piece is a flagship part and should feel cold, solid, precise and overbuilt in the hand.

## Architecture

`90° manual rotation -> shaft -> rear cam -> frame receiver`

Optional electronics only report state; the lock remains mechanically understandable and manually operable without power.

## Planned repository structure

- `docs/` — blueprint, manual, architecture and reference notes
- `blender/` — Blender master assembly and parametric generator
- `cad/` — manufacturing geometry by component
- `manufacturing/` — STL/DXF/templates
- `electronics/` — sensors, lighting and firmware
- `bom/` — bill of materials
- `tests/` — mechanical and cycle validation

## Status

`Mk I / v0.1 — reconstruction and first manufacturable concept`

The next development branch builds the parametric Blender assembly and the aluminum-first mechanical specification.
