# EnchantVenture Pack

Client-side resource pack for the EnchantVenture modpack (Minecraft 26.2). It bundles:

- **Spanish (`es_ES`) translations** for mods included in the modpack that don't ship their own —
  without touching the mods themselves.

## Features

- 🗣️ `es_ES` language files for mods without Spanish support (99 mods, curated by hand).

## Requirements

- Minecraft **26.2** (pack format 88)
- The EnchantVenture modpack (or any subset of the mods it bundles)

## Installation

1. Download `EnchantVenture_Pack-<version>.zip` from [CurseForge](https://www.curseforge.com/minecraft/texture-packs/enchantventure-translations).
2. Place it in `resourcepacks/`.
3. Enable it in **Options → Resource Packs** (above any other resource pack that also translates
   the same mods, if applicable).
4. Set your game language to **Español (España)**.

## Coverage

Translations are added incrementally, mod by mod. See the
[Coverage page of the wiki](https://github.com/codex-skd/enchantventure-pack/wiki/Coverage) for the list of translated mods.

## Build

The resource pack content lives under `resourcepack/`. The build script validates the JSON files
and zips them with `pack.mcmeta` at the root (loads directly):

```bash
python build_pack.py
# → build/EnchantVenture_Pack-<version>.zip
```

Version is read from `version.txt`.

## Credits

- Spanish translations: **Stalking Dragons**.

## License

All Rights Reserved.
