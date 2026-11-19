# Gemini Notebook Workspace — Structure & Source Map (v3.2)

> **Rolling File Notice:** `current.md` is overwritten on every new version push to reflect the latest active structure and source map. Immutable historical snapshots live in `vX.Y.md` files, and chronological history lives in `changelog.md`.

- **Active Version:** `v3.2` (`X = 3` Structure, `Y = 2` Source Map)
- **Repository:** `https://github.com/RedFoxFOMO/Google-Notebook-Structure` (`main`)
- **Last Updated:** 2026-11-19

## Versioning Rules (`vX.Y`)
- **`X` (Structure):** Notebook hierarchy, `--` master hubs, sub-notebooks, `[tag]` definitions, and presentation/file structure.
- **`Y` (Source Map):** Which sources live in each notebook's collective pool and which `[tag]` categories or airframes they map to.
- **Both Increment:** When both structure and source mappings change.
- **File Policy:** Each version creates a new `vX.Y.md` file (retaining older `vX.Y.md` files) and appends a new section to `changelog.md` (preserving prior entries), while `current.md` is overwritten with the latest version state.

## Naming & Chat Isolation Conventions
- **Master Hubs:** Prefixed with `--` and formatted as `--Name-Master` with no gaps (e.g., `--Structure`, `--DCS-Master`, `--3DPrinting-Master`, `--Trading-Master`, `--Content-Master`, `--Personal-Master`).
- **Sub-Notebooks:** No gaps, first letter capitalized after hyphens (e.g., `Dcs-Jets`, `Dcs-Rotary`, `Dcs-Warbirds`, `3DPrinting-Projectx`, `Content-projectx`). Proper names keep their natural spacing and casing (e.g., `Eve Online`, `Farm Sim 25`).
- **Chat Source Isolation:** Sources sit in each notebook's collective pool; create dedicated chats per `[tag]` in the notebook interface and toggle only that `[tag]`'s sources active to avoid cross-contamination.

## Notebook Hierarchy, `[tag]` Purposes & Source Map (Baseline from v2.2)

### `--DCS-Master`
- `[Core]` — Global gameplay rules, GUI, options, and settings.
- `[Map]` — Theater terrain guides and navigation references.
- `[VR]` — Headset optimization and OpenXR performance tuning.
- `[Editor]` — Mission Editor triggers, units, and scripting.
- `[Mod]` — User-mods, mod manager rules, and liveries.

### `Dcs-Jets`
Airframe module `[tag]`s and intended document pairs (Official Flight Manual + Chuck's Guide where applicable):
- `[fa18]` — F/A-18C Hornet (ED Official Flight Manual + Chuck's Hornet Guide)
- `[f14]` — F-14 Tomcat (ED Manual + Chuck's Tomcat Guide)
- `[a10]` — A-10C (ED Manual + Chuck's Warthog Guide)
- `[su25t]` — Su-25T Frogfoot (ED Manual)
- `[su25]` — Su-25A Frogfoot (ED Manual)
- `[mig19]` — MiG-19P Farmer (ED Manual + Chuck's Guide)
- `[mig21]` — MiG-21bis Fishbed (ED Manual + Chuck's Guide)
- `[m2000]` — Mirage 2000C (ED Manual + Chuck's Guide)
- `[f1]` — Mirage F1 (ED Manual + Chuck's Guide)
- `[av8b]` — AV-8B Night Attack (ED Manual + Chuck's Guide)
- `[f4e]` — F-4E Phantom II (ED Manual + Chuck's Guide)
- `[a4e]` — A-4E-C Skyhawk (Community Mod Docs)

### `Dcs-Rotary`
Airframe module `[tag]`s and intended document pairs:
- `[apache]` — AH-64D Apache (ED Official Manual + Chuck's Apache Guide)
- `[blackshark3]` — Ka-50 Black Shark 3 (ED Official Manual + Chuck's Ka-50 Guide)
- `[hind]` — Mi-24P Hind (ED Official Manual + Chuck's Hind Guide)
- `[hip]` — Mi-8MTV2 Hip (ED Official Manual; no standalone Chuck's Guide)
- `[huey]` — UH-1H Huey (ED Official Manual)
- `[gazelle]` — SA342 Gazelle (ED / Steam Manual + Chuck's Gazelle Guide)
- `[chinook]` — CH-47F Chinook (ED Early Access Guide)

### `Dcs-Warbirds`
Airframe module `[tag]`s and intended document pairs:
- `[mustang]` — P-51D Mustang (ED Official Manual + Chuck's Mustang Guide)
- `[109]` — Bf 109 K-4 (ED Official Manual + Chuck's Guide)
- `[anton]` — Fw 190 A-8 Anton (ED Official Manual + Chuck's Guide)
- `[dora]` — Fw 190 D-9 Dora (ED Official Manual + Chuck's Guide)
- `[thunderbolt]` — P-47D Thunderbolt (ED Official Manual + Chuck's Guide)
- `[spitfire]` — Spitfire LF Mk. IX (ED Official Manual + Chuck's Guide)
- `[mosquito]` — Mosquito FB VI (ED Official Manual + Chuck's Guide)

### Other Tracked Notebooks
- `--Structure` — Tracks workspace structure, naming conventions, `[tag]` definitions, and version/source-map tracking.
- `--Trading-Master` — Tracked master hub (detailed `[tag]` scope to be added as defined).
- `--Personal-Master` — Tracked master hub (detailed `[tag]` scope to be added as defined).
- `--Content-Master` — Tracked master hub (detailed `[tag]` scope to be added as defined).
- `--3DPrinting-Master` — Tracked master hub (detailed `[tag]` scope to be added as defined).
- `Eve Online` — Sub-notebook / proper-name workspace (detailed `[tag]` scope to be added as defined).
- `Farm Sim 25` — Sub-notebook / proper-name workspace (detailed `[tag]` scope to be added as defined).
- `3DPrinting-Projectx` — Sub-notebook (detailed `[tag]` scope to be added as defined).
- `Content-projectx` — Sub-notebook (detailed `[tag]` scope to be added as defined).