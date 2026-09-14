# The Two-Doctrine Focal Staff

> **Source:** CP-2 (gear Item rail) + Ikaris Vows of Azar (broken staff = warlock).

## The Signature Asset

The demo's signature gear is a **focal staff** — 20 CP, `gear` item, Size Rank 0. Two doctrines, one chassis (mirrors psycho-frame/skiff):

| Doctrine | Item | Effect | Flavor |
|---|---|---|---|
| **Vow-Bound Staff** | `ikaris_vow_staff` | `{"kind":"stat_mod","acv_bonus":2,"ar":0,"note":"Vows of Azar - Archmage focal staff"}` | Granted by the archmage, the legal lane |
| **Broken Staff (Warlock)** | `ikaris_broken_staff` | Same bonus + `Defect: Marked (Oathbreaker)` returning 2 CP → `Weapon Enhancement: Drain (Mind)` | Forsaken, the illegal lane |

Both: 20 CP, rank C, `item_type: gear`, granted as starting gear (not a market buyout).

## Attributes

- Focal staff for spellcasting (ACV +2 bonus via `stat_mod`)
- Broken staff drains Mind on a hit (Drain enhancement)

## Engine Path

One `gear` row per doctrine in the `items` table, `effect_json` structured for `models.py`. No new engine field — exactly the CP-2 rail from Enid (chassis) / Cathedral (skiff).