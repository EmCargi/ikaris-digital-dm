# Feudal Magic & The Vows of Azar

> **Source:** BESM 4e Chapter 14, pp. 330–331 (Ikaris) + Ch.3 Race Templates (Elves p.39).

## Magic as Feudal Institution

Magic on Ikaris isn't learned — it requires **the Gift**, said to come from the Weaver. Mageborn children are detected in infancy (instinctive spells), adopted by sorcerers as heir-apprentices, and eventually "win their staff" to become sorcerers. Titles (sorcerer, archmage, Legate) are not hereditary.

## The Vows of Azar

A magical code binding sorcerers, archmagi, and Legates: **forbid harming the innocent, protect the weak.** Breaking the Vows → **warlock** (staff broken, honor stripped).

## Race Templates

- **Dark Elves** (Ch.3 p.39) — arrived from an Outer World connected to Ikaris before its gate was destroyed. Resilient (Ageing, Poisons), Supersense (Dark Vision). Insular, subterranean.
- **Elves** (Ch.14 p.330) — beautiful pointy-eared wanderers, all mages, matriarchal, treated like gypsies; sometimes called hellspawn by human mages.

## Powers → card_json

Powers (Force Field, Arcane Bolt, Mind Shield, Sixth Sense, Control Environment, Nether Flare, Healing) have **no DB column** — they live in `card_json.powers` + the `race` column as narrative, injected as prose (Enid/Cathedral pattern). The loadout DB columns carry techniques/skills/defects + Narrative Syntax.