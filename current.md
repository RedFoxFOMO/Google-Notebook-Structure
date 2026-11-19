# Current Workspace Structure & Source Map (v3.2)

> **Rolling File Notice:** `current.md` is overwritten on every version push to reflect the latest active structure and source map. For immutable historical snapshots, see `vX.Y.md` files; for chronological history, see `changelog.md`.

- **Active Version:** `v3.2` (`X = 3` Structure, `Y = 2` Source Map)
- **Repository:** `https://github.com/RedFoxFOMO/Google-Notebook-Structure` (`main`)
- **Last Updated:** 2026-11-19

## Versioning Rules (`vX.Y`)
- **`X` (Structure):** Increments for changes to notebook hierarchy, naming/file layout, `[tag]` definitions, or presentation format.
- **`Y` (Source Map):** Increments for adding/removing/remapping sources or `[tag]`/airframe source links.
- **Both Increment:** When both structure and source mappings change.
- **Snapshot & Log Policy:** Each version creates a new snapshot file `vX.Y.md` (retaining prior `vX.Y.md` files) and appends a new entry to `changelog.md` (preserving prior entries), while `current.md` is overwritten with the latest state.

## Naming & Chat Isolation Conventions
- **Master Hubs:** Prefixed with `--` and formatted as `--Name-Master` with no spaces (e.g., `--Structure`, `--DCS-Master`, `--3DPrinting-Master`, `--Trading-Master`, `--Content-Master`, `--Personal-Master`).
- **Sub-Notebooks:** No spaces, first letter capitalized after hyphens (e.g., `Dcs-Jets`, `Dcs-Rotary`, `Dcs-Warbirds`, `3DPrinting-Projectx`, `Content-projectx`). Proper names retain natural spacing and casing (e.g., `Eve Online`, `Farm Sim 25`).
- **Chat Source Isolation:** Sources reside in each notebook's collective pool and are scoped per `[tag]` chat inside the notebook interface so only relevant sources are active for a given `[tag]`.

## Known Notebook & `[tag]` Map (Baseline from v2.2)

### `--DCS-Master`
- `[Core]` — Global gameplay rules, GUI, options, and settings.
- `[Map]` — Theater terrain guides and navigation references.
- `[VR]` — Headset optimization and OpenXR performance tuning.
- `[Editor]` — Mission Editor triggers, units, and scripting.
- `[Mod]` — User-mods, mod manager rules, and liveries.

### `Dcs-Jets`
- Airframe `[tag]`s: `[fa18]`, `[f14]`, `[a10]`, `[su25t]`, `[su25]`, `[mig19]`, `[mig21]`, `[m2000]`, `[f1]`, `[av8b]`, `[f4e]`, `[a4e]`.
- *Note:* Per-tag detailed scope notes should be populated directly in `current.md` / `vX.Y.md` as confirmed in your source map.

### `Dcs-Rotary`
- Airframe `[tag]`s: `[apache]`, `[blackshark3]`, `[hind]`, `[hip]`, `[huey]`, `[gazelle]`, `[chinook]`.
- *Note:* Per-tag detailed scope notes should be populated directly in `current.md` / `vX.Y.md` as confirmed in your source map.

### `Dcs-Warbirds`
- Airframe `[tag]`s: `[mustang]`, `[109]`, `[anton]`, `[dora]`, `[thunderbolt]`, `[spitfire]`, `[mosquito]`.
- *Note:* Per-tag detailed scope notes should be populated directly in `current.md` / `vX.Y.md` as confirmed in your source map.

### Other Tracked Notebooks
- `--Structure` — Tracks workspace structure, naming rules, `[tag]` conventions, and version/source-map snapshots.
- `--Trading-Master` — No `[tag]` definitions recorded yet.
- `--Personal-Master` — No `[tag]` definitions recorded yet.
- `--Content-Master` — No `[tag]` definitions recorded yet.
- `--3DPrinting-Master` — No `[tag]` definitions recorded yet.
- `Eve Online` — No `[tag]` definitions recorded yet.
- `Farm Sim 25` — No `[tag]` definitions recorded yet.
- `3DPrinting-Projectx` — No `[tag]` definitions recorded yet.
- `Content-projectx` — No `[tag]` definitions recorded yet.