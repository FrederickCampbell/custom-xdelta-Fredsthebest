# Custom XDelta Patches – FredstheBest

This repository hosts my collection of custom `.xdelta` patches.  
Each patch is designed to apply cleanly to the verified Redump dump of the corresponding game.  

**Note:** This repository does **not** distribute ROMs/ISOs. You must legally own the original game to apply any patch.

---

## Current Patches
- **Pokémon XD – Gale of Darkness (Europe)** → Widescreen + 60FPS

---

## Usage
1. Download the desired `.xdelta` patch.  
2. Apply the patch using any compatible xdelta patcher (`xdelta3`, etc.).  

Example with `xdelta3`:
```bash
xdelta3 -d -s "original.iso" "patch.xdelta" "patched.iso"
