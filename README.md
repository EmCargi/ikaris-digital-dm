# 💿 Ikaris: Swords & Sorcery — Game Disc for Chronos Core

*The feudal magic world of the Nine Shards. Vows of Azar, grand tourneys, the College of Harpers gate nexus, and the Seven Stars.*

> **Source:** BESM 4e Chapter 14 (Anime Multiverse) — First-party canon, no third-party IP.
> All content authored from the canon hooks. Regenerable via the Chronos engine.

---

## 🎮 Boot (when ready)

```text
/setting besm_ikaris       # swap discs in the TUI
/roster                      # Oath column
/module shards_tourney.json             # default starter module
```

| Contract layer | Status |
|---|---|
| **1 · Registration** | ✅ `besm_ikaris` in `config/settings.json` → `shards_tourney.json` |
| **2 · Module** | ✅ `modules/shards_tourney.json` (validator-passed) |
| **3 · Roster** | ✅ Starter characters authored (`Characters/`, 50 CP, `besm_ikaris`) |
| **4 · Economy** | ✅ Seed catalog + chassis as `Item` |
| **5 · Lore Vault** | 🏗️ `World/` `Characters/` `Factions/` `Locations/` `Mechanics/` |

> **Status: SCAFFOLDED** — disc directory + proposal exist. Layers 1–5 wired via Chronos Core engine.

## 🗂️ Structure

```
ikaris-digital-dm/
├── README.md               ← this home page
├── Characters/             ← PC/NPC sheets (besm_ikaris)
├── data/                   ← roster DB + catalog
├── Factions/               ← organizations & groups
├── Locations/              ← region & landmark sheets
├── Mechanics/              ← system rules & supplements
├── modules/                ← playable labyrinth modules
├── scripts/                ← import/parser utilities
└── World/                  ← lore vault
```

---

*Disc for the Chronos Core console. Swap via `/setting besm_ikaris`.*
