# 3D Asset Credits

## Kenney Furniture Kit

- Source: https://kenney.nl/assets/furniture-kit
- Local path: `/public/assets/3d/kenney-furniture-kit/`
- License: Creative Commons Zero, CC0 1.0 Universal
- Notes: The live Three.js scene loads GLB furniture and prop files from the pack, including desks, desk chairs, laptop/computer props, plants, bookcase, books, sofa, and floor lamp.

## Character Figures

- Source: Hand-built Three.js primitive geometry in `src/components/fieldwork-scene.tsx`
- License: Project-owned implementation
- Notes: Kenney/Quaternius character packs were researched, but the suitable free character downloads were gated through Itch/Google Drive flows that were not reliably fetchable as direct asset files in this environment. The scene therefore uses commercial-safe primitive people as the requested fallback for character figures, while still loading Kenney GLB assets for furniture and props.
