# The Concordat Era — Codex Instructions

## What This Is

A Star Wars KOTOR-era alternate history TTRPG setting book for Fate Condensed, built for an actual play podcast. The primary document is `Homebrewery/Setting Book.md`. This repository is the source of truth; Homebrewery drifts and should be used for rendering only.

The setting reimagines the post-Mandalorian Wars galaxy through Napoleonic historical parallels. Malak governs as Supreme Chancellor-General (First Consul) with permanent emergency powers and a surveillance apparatus targeting Force-sensitives. Revan returned from the Unknown Regions with a fracturing mind. The Force is dying.

**Campaign Year:** 4 CE (Concordat Era). Three years after the Concordat's founding.

---

## Repository Structure

| Path | Purpose |
|------|---------|
| `Homebrewery/Setting Book.md` | THE primary document. 23 chapters + appendices. |
| `Homebrewery/Style/KOTOR_DH_STYLE.css` | Custom Homebrewery CSS (Daggerheart-derived) |
| `docs/setting-book/phase1-design-notes.md` | Design philosophy, open questions, decisions |
| `docs/setting-book/lore-bible.md` | Expanded GM lore reference |
| `docs/production/style-guide.md` | Visual design spec (typography, color, layout) |
| `docs/guides/gm-guide.md` | GM philosophy |
| `docs/supplements/factions-and-species.md` | Jedi/Sith hierarchies + expanded species |

See `CLAUDE.md` and `AGENTS.md` at the repo root for full setting details: factions, Force crisis mechanics, Napoleonic parallels, literary influences, character maps, and chapter structure.

---

## Skills

Two skills govern work in this repo. Both are mandatory when their conditions apply.

### Brainstorming (Design Before Implementation)

**Trigger:** Any creative work. New sections, new characters, new worlds, new species entries, structural changes, feature additions. If you are about to write new content or restructure existing content, brainstorm first.

**Hard gate:** Do not write prose, create sections, or modify structure until the design has been presented and approved. This applies to every task regardless of perceived simplicity.

**Process:**
1. Explore project context (read relevant chapters, check cross-references)
2. Ask clarifying questions one at a time (prefer multiple choice)
3. Propose 2-3 approaches with trade-offs and a recommendation
4. Present the design in sections scaled to complexity
5. Get approval before proceeding
6. Write a design doc to `docs/superpowers/specs/YYYY-MM-DD-<topic>-design.md`
7. Self-review the spec for placeholders, contradictions, ambiguity, scope
8. Get user review of the written spec
9. Proceed to implementation

**Anti-pattern:** "This is too simple to need a design." Every project goes through brainstorming. Simple designs can be a few sentences, but the approval gate is non-negotiable.

**Scope check:** If a request describes multiple independent subsystems, decompose first. Each sub-project gets its own spec-plan-implementation cycle.

### Stop Slop (Prose Quality)

**Trigger:** Every piece of prose written or edited. All new text, all revisions, all expansions. Run this as a final pass before completing any writing task.

**8 Rules:**
1. Cut filler phrases. No throat-clearing openers, emphasis crutches, or adverbs.
2. Break formulaic structures. No binary contrasts, negative listings, dramatic fragmentation, rhetorical setups, false agency.
3. Use active voice. Every sentence needs a human subject doing something. No passive constructions. No inanimate objects performing human actions.
4. Be specific. No vague declaratives. Name the specific thing. No lazy extremes ("every," "always," "never").
5. Put the reader in the room. "You" beats "People." Specifics beat abstractions.
6. Vary rhythm. Mix sentence lengths. Two items beat three. No em dashes.
7. Trust readers. State facts directly. Skip softening, justification, hand-holding.
8. Cut quotables. If it sounds like a pull-quote, rewrite it.

**Quick checks before delivering prose:**
- Any adverbs? Kill them.
- Any passive voice? Find the actor, make them the subject.
- Inanimate thing doing a human verb? Name the person.
- Sentence starts with a Wh- word? Restructure it.
- "Here's what/this/that" throat-clearing? Cut to the point.
- "Not X, it's Y" contrasts? State Y directly.
- Three consecutive sentences match length? Break one.
- Paragraph ends with punchy one-liner? Vary it.
- Em-dash anywhere? Remove it.
- Vague declarative? Name the specific implication.

**Score 35+/50** on Directness, Rhythm, Trust, Authenticity, Density. Below 35: revise before delivering.

---

## Subagent and Orchestration Guidelines

### When to Use Subagents

Use the `Explore` subagent for:
- Searching the Setting Book for cross-references before making changes (character mentions, faction references, event citations across chapters)
- Gathering page numbers across multiple chapters to update the glossary or TOC
- Reading multiple files in parallel to build context (lore bible, phase1 design notes, style guide)
- Verifying consistency of a character's details across chapters

Specify thoroughness: `quick` (spot check), `medium` (relevant sections), `thorough` (full audit).

### Orchestration Patterns for This Repo

**Single chapter edit:**
1. Read the target chapter section
2. Read cross-referenced chapters (characters/events that appear elsewhere)
3. Make edits
4. Run Stop Slop pass on new prose
5. Update TOC if page count changed (count `\page` breaks)
6. Update glossary entries for any modified characters, locations, or terms

**New world or species entry:**
1. Brainstorm: read existing entries in Ch21/Ch22 for format and depth
2. Read the lore bible and factions-and-species supplement for source material
3. Propose structure and content outline, get approval
4. Write the entry
5. Run Stop Slop pass
6. Add glossary entries
7. Update TOC page numbers
8. Check if the world/species is mentioned in other chapters; add cross-references if needed

**Multi-chapter expansion (e.g., expanding all species entries):**
1. Brainstorm the full scope: which entries, what depth, what order
2. Decompose into independent sub-tasks (one per entry)
3. For each entry: read existing content → write expansion → Stop Slop pass → glossary update
4. After all entries: recount `\page` breaks, update full TOC, verify cross-references

**Cross-reference audit:**
- Use `Explore` subagent with `thorough` to find all mentions of a character/faction/term across the full Setting Book
- Compare details for consistency (ages, dates, titles, relationships)
- Fix discrepancies

---

## Content Quality Standards

The expanded Alek (Ch8), Kaeranth (Ch9), Clan Ordo (Ch10), and Force Crisis POVs (Ch6) define the quality floor. Study them before writing new content.

### Detail Density

No unnamed NPCs. No unquantified problems. No undated events.

- **Characters:** age, homeworld, titles, named staff/rivals, specific Force abilities with degradation, injuries.
- **Factions:** headcount, territory count, named leaders at multiple levels, specific operations with targets.
- **Worlds:** named population centers, controlling authority, economic base, named local NPCs.
- **Species:** named institutions, communication methods, specific cultural practices, named communities.

**Test:** Remove all proper nouns, numbers, and dates. If the section still reads coherently, it lacks detail.

### Actionable Campaign Material

Every paragraph needs at least one actionable element: a decision pending, a conflict present, a secret to discover, a leverage point, or a resource to compete over.

**Ratio targets:** Origins/biography sections: 65% worldbuilding / 35% hooks. Current operations: 40/60. Final operational paragraphs: 30/70. POV sections: 25/75.

**The Ch6 test:** "The Baran Do Sages issued their first incorrect forecast in 1 CE; three storms hit populated areas without warning" gives a GM a mission, a faction contact, a timeline, and stakes. "The Force is weakening and people are scared" gives nothing. Every sentence must pass this test.

### Subsection Templates

**Characters:** Opening (title, age, location) → Origins (dates, mentors) → Force Capabilities (abilities, degradation) → Institutional Relationships (named subsections with friction) → Current Operations (2-3 quantified crises) → Player-facing closing

**Factions/Clans:** Opening (leader, headcount, territory) → Ideology (stated as belief) → Quantified Problem 1 → Quantified Problem 2 → Named rival relationships → GM paragraph (entry points)

**Worlds:** Opening (authority, strategic importance) → Geography (named districts) → Politics (who governs, quantified tension) → Economy/daily life (commodities, costs) → Force/crisis impact → Player hooks (3-4 scenarios)

**Species:** Opening (population status, homeworld) → Social structure (institutions) → Communication/culture (specific practices) → Current era pressures → Diaspora/galactic role → PC implications

### Star Wars Names

Use the Star Wars Name Generator API (`https://vqcjvexnwxnwvaoeofka.supabase.co/functions/v1/generate-names`) for new named characters. No Earth-derived or generated-sounding names.

---

## Formatting Conventions

**Homebrewery Markdown:**
- `\page` for page breaks, `{{pageNumber,auto}}` on every page
- `{{Ch2,tab}}` for chapter tab markers
- `{{footnote ...}}` page footnotes, `{{descriptive ...}}` in-world flavor boxes, `{{note ...}}` GM sidebars
- `#` chapter titles, `##` major sections, `####` character names, `#####` subsections within character entries

---

## Editing Checklist

Run this checklist for every edit to the Setting Book:

- [ ] Read the relevant chapter section before making changes
- [ ] Check cross-references (characters, events, factions mentioned in other chapters)
- [ ] Run Stop Slop pass on all new prose (score 35+/50)
- [ ] Recount `\page` breaks and update TOC if page numbers shifted
- [ ] Update glossary entries (descriptions and page numbers) for any modified content
- [ ] Hook test: every sentence serves as a potential player or GM hook

---

## Current Goals

The next phase expands Chapter 21 (Worlds and Frontiers) and Chapter 22 (Peoples and Species) to match the encyclopedic treatment in Chapters 8, 9, and 10. See `AGENTS.md` for the full list of 13 worlds and 11 species requiring expansion. Secondary goals include Independent Powers faction profiles, Sith/Jedi code statements, Deep Sith restructuring, and Rakata consolidation.
