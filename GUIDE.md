# GUIDE — How to record and navigate your lore

This quick guide explains how to use Chronicle as a personal universe operating system: how to record entries, connect them, and navigate a growing fictional world.

---

## Core entry types

- Character — people, creatures, or sentient beings. Fields: name, epithet, summary, role, affiliations, birth/death (if applicable), appearance, notes, relationships.
- Location — places, cities, regions, or realms. Fields: name, summary, coordinates (map refs), notable features, factions, important events.
- Event — happenings that affect the world (battles, discoveries, festivals). Fields: name, date (or era), summary, participants, outcomes, related locations.
- Artifact — objects with history or power. Fields: name, summary, origin, properties, current location, history.
- Concept — ideas, religions, laws, cultural practices. Fields: name, summary, variations, impact.

## Suggested entry structure (template)

Title: <short, canonical name>

Lede: 1–2 sentence summary.

Type: Character / Location / Event / Artifact / Concept

Tags: comma-separated keywords (e.g., pirate, ruling-house, forbidden-magic)

Canonical date / Era: (optional) — format clearly, or use eras (Age of Glass, Year 3 of the Guild)

Related entries: list of internal links to other entries (characters, places, events)

Full description: narrative, source notes, quotes, variations, contradictory accounts.

Notes & versions: keep a changelog or drafts, and mark what is canonical vs. variant.

---

## Navigation patterns

- Use tags and categories to group similar entries (e.g., all entries tagged `royalty` or `navy`).
- Build index pages (e.g., "All Characters", "All Locations") that automatically list entries of a type.
- Backlinks: when possible, display which pages link to the current entry to discover connections.
- Timelines: create event timelines for places or eras so you can see cause and effect.
- Maps: keep a map file or reference coordinates for locations; link map pins to entries.

## Versioning & exports

- Keep drafts in a separate field or with a `draft/` prefix in filenames.
- Periodically export your data to JSON or Markdown to create snapshots and enable tooling (generators, translators to campaign tools).
- Tag stable/canonical versions so you can revert or cite the version used in a story.

## Collaboration & canon

- If you collaborate, set clear rules for what counts as canonical vs. headcanon.
- Keep a changelog or use pull requests to review major additions when working with others.

## Example: character entry (template)

Title: Vael of the Glass Harbor

Lede: Vael stitched the broken districts of the Glass Harbor together with his maps and debts.

Type: Character

Tags: navigator, smuggler, Glass Harbor, faction:Harbormasters

Canonical date: Active 224–247 (Age of Glass)

Related entries: Glass Harbor (location); The Sundered Map (artifact); The Harbor Compact (event)

Full description: (long-form biography, motivations, contradictions, in-world quotes)

Notes & versions: Draft v0.9 — moved origin story from "Glass Harbor" to "Vael" on 2026-10-14.

---

## Tips for keeping your world usable

- Keep ledes short — they save time when scanning search results.
- Prefer links over repeated exposition; link to a character's birthplace rather than re-describing it.
- Use consistent tag names and date formats.
- Regularly prune or archive abandoned ideas to avoid clutter.

---

If you want, I can also add ready-made Markdown templates for each entry type, or make a simple JSON schema that you can import/export. Tell me which you prefer and I will add them to the repo.