# The Concordat Era

A Star Wars KOTOR-era alternate history TTRPG setting for Fate Condensed, built for an actual play podcast.

The Concordat Era reimagines the post-Mandalorian Wars galaxy through Napoleonic historical parallels. Malak rules as a pragmatic authoritarian consul. Revan has vanished into the Unknown Regions. The Force is dying, and no one agrees on why. Three governments, five Jedi factions, a hidden Sith network, and a galaxy full of people trying to survive the aftermath of a war that broke everything.

**System:** Fate Condensed. The Force is an Extra costing 1 stunt slot, interacting with the setting's dead zone system and compel economy.

## Documents

### Player-Facing

| Document | Description |
|----------|-------------|
| [Setting Book](docs/setting-book/setting-book.md) | 13 chapters covering the political landscape, factions, worlds, the Force crisis, and character hooks. Written from the perspective of a reasonably informed citizen of the galaxy. |
| [Factions & Species Supplement](docs/supplements/factions-and-species.md) | Jedi internal factions, Sith hierarchy and diaspora, and expanded species writeups: Cathar, Miraluka, Selkath, Echani, Wookiees, Twi'leks, Zabraks, Duros. |
| [Fate Condensed Player Guide](docs/supplements/fate-condensed-player-guide.md) | Character creation, 19 skills with setting-specific descriptions, Force-Sensitive Extra mechanics, dead zone rules, party composition for actual play, Session Zero procedure. |

### GM-Facing

| Document | Description |
|----------|-------------|
| [GM Guide](docs/guides/gm-guide.md) | Six campaign genres, three Sith/evil campaign variants, five alternate timeframes, and an opinionated GM philosophy drawing on the Alexandrian, Sly Flourish, and Burning Wheel design traditions. |
| [Lore Bible](docs/setting-book/lore-bible.md) | Full timeline, deep faction history, Kreia/Triumvirate, Sith remnants, Jedi fractures, kolto economics, the Freighter Incident scenario, and open design questions. Split across two files pending merge. |
| [Style Guide](docs/production/style-guide.md) | Visual specifications for InDesign layout: fonts, colors, type hierarchy, master pages, and section-specific tonal shifts. |


##Homebrewery

> **This repo is the source of truth.** Homebrewery has persistent syncing issues and drifts from the canonical text. Always assume the Homebrewery versions are behind. Use them for rendering only.

Formatted source files live in [Homebrewery/](Homebrewery/). Layout uses [KOTOR_DH_STYLE.css](Homebrewery/Style/KOTOR_DH_STYLE.css), derived from the original Daggerheart theme.

| Book | Source | Homebrewery |
|------|--------|-------------|
| Setting Book | [Homebrewery/Setting Book.md](Homebrewery/Setting%20Book.md) | [Edit](https://homebrewery.naturalcrit.com/edit/8Bh534CEmzPy) |
| Lore Bible I | [Homebrewery/Lore Bible I.md](Homebrewery/Lore%20Bible%20I.md) | [Edit](https://homebrewery.naturalcrit.com/edit/PuSZMHesu1EL) |
| Lore Bible II | [Homebrewery/Lore Bible II.md](Homebrewery/Lore%20Bible%20II.md) | [Edit](https://homebrewery.naturalcrit.com/edit/GzvXtMiO5Hzs) |


##Status & TODO

Writing ongoing. Core documents complete; lore bible merge and structural revisions in progress. Currently in production/layout phase.

- [ ] Merge `lore-bible.md` and `lore-bible-supplement.md` into a single GM reference document
- [ ] Revise setting book structure: remove Part/Chapter hierarchy, use Chapters only
- [ ] Add additional planets to Chapter 8: Worlds, Regions, and Frontiers
- [ ] Create galactic map: Pre-Concordat era
- [ ] Create galactic map: Post-Concordat era
- [ ] Add all art assets to `/assets` folder
- [ ] Credit all artists used in cover art and illustrations; obtain permission where not cleared

---

<details>
<summary>Repository Structure</summary>

```
concordat-era/
├── docs/                              # Source markdown
│   ├── setting-book/
│   │   ├── setting-book.md            # Main setting book (13 chapters + appendices)
│   │   ├── lore-bible.md              # Expanded GM lore reference
│   │   ├── lore-bible-supplement.md   # Lore bible supplement (to be merged)
│   │   └── phase1-design-notes.md     # Phase 1 design Q&A and decisions
│   ├── supplements/
│   │   ├── factions-and-species.md    # Jedi/Sith hierarchies + expanded species
│   │   └── fate-condensed-player-guide.md
│   ├── guides/
│   │   └── gm-guide.md
│   └── production/
│       └── style-guide.md             # Typography, color palette, InDesign specs
├── Homebrewery/                       # Homebrewery-formatted source files
│   ├── Setting Book.md
│   ├── Lore Bible I.md
│   ├── Lore Bible II.md
│   └── Style/
│       ├── KOTOR_DH_STYLE.css         # Custom Homebrewery CSS (active)
│       └── OriginalDaggerheartStyle.css
├── PDF_Releases/                      # Exported PDFs
└── README.md
```

</details>
