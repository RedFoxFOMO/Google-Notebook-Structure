# Gemini Notebook Workspace — Structure & Source Map

This repository tracks the structure and source mapping for your Gemini Notebook workspace using a combined **`vX.Y`** version label inside a single master map file:

* **`X` (Structure):** Notebook hierarchy, `--` master hubs, sub-notebooks, and `[tag]` definitions.
* **`Y` (Source Map):** Which sources live in each notebook's pool and which `[tag]` categories they map to.

## Naming & Workflow Rules
* **Master Hubs:** Prefixed with `--` and formatted as `--Name-Master` with no gaps (for example, `--Structure`, `--DCS-Master`, `--3DPrinting-Master`, `--Trading-Master`, `--Content-Master`, `--Personal-Master`).
* **Sub-Notebooks:** No gaps, first letter capitalized after hyphens (for example, `Dcs-Jets`, `Dcs-Rotary`, `Dcs-Warbirds`, `3DPrinting-Projectx`, `Content-projectx`). Proper names keep their natural spacing and casing (`Eve Online`, `Farm Sim 25`).
* **Chat Source Isolation:** Sources sit in each notebook's collective pool; create dedicated chats per `[tag]` in the notebook interface and toggle only that `[tag]`'s sources active to avoid cross-contamination.