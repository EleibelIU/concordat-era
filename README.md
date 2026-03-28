# The Concordat Era

A Star Wars KOTOR-era alternate history TTRPG setting for Fate Condensed, built for an actual play podcast.

The Concordat Era reimagines the post-Mandalorian Wars galaxy through Napoleonic historical parallels. Malak rules as a pragmatic authoritarian consul. Revan has vanished into the Unknown Regions. The Force is dying, and no one agrees on why. Three governments, five Jedi factions, a hidden Sith network, and a galaxy full of people trying to survive the aftermath of a war that broke everything.


## Documents

### Setting Book

| Document | Description |
|----------|-------------|
| [Setting Book](Homebrewery/Setting%20Book.md) | The definitive setting book. 13 chapters covering the political landscape, factions, species, worlds, the Force crisis, and character hooks. Written from the perspective of a reasonably informed citizen of the galaxy. |

### GM-Facing

| Document | Description |
|----------|-------------|
| [GM Guide](docs/guides/gm-guide.md) | An opinionated GM philosophy drawing on the Alexandrian, Sly Flourish, and Burning Wheel design traditions. Campaign genres, Sith/evil campaign variants, alternate timeframes. Not yet formatted for Homebrewery. |


> **This repo is the source of truth.** Homebrewery has persistent syncing issues and drifts from the canonical text. Always assume the Homebrewery versions are behind. Use them for rendering only.

Formatted source files live in [Homebrewery/](Homebrewery/). Layout uses [KOTOR_DH_STYLE.css](Homebrewery/Style/KOTOR_DH_STYLE.css), derived from the original Daggerheart theme.

| Book | Source | Homebrewery |
|------|--------|-------------|
| Setting Book | [Homebrewery/Setting Book.md](Homebrewery/Setting%20Book.md) | [Edit](https://homebrewery.naturalcrit.com/edit/8Bh534CEmzPy) |


## Status & TODO

Writing ongoing. Core documents complete; structural revisions and content expansion in progress.

### Art to Add
- [ ] Galaxy Map next to "Galaxy at a Glance"

### Revisions

#### (Pg. 33) The Deep Sith
- [ ] Clarify who Ajunta Pall is, who the Sith were before the Great Hyperspace War, and provide a yearly timeline (or fill in a few thousand years of history to maintain the mystique)
- [ ] Clarify who the Dark Jedi Exiles are and what differentiates a Dark Jedi from the Jedi Order or the Sith (readers will assume Jedi defectors; the text implies otherwise)
- [ ] Restructure section order: either introduce the Sith as an ideology first (parallel to the Jedi Order, what they are *now*) then go into history, OR start with history (Exar Kun, Ajunta Pall, Marka Ragnos, the Empire) and lead into what caused the Great Hyperspace War
- [ ] Beef up the Great Hyperspace War coverage (currently underserved now that Revan's war is de-emphasized)
- [ ] Remove the "Ancient Survivors" section and find a better place to integrate it
- [ ] Rename "The Shadow" section (consider: Cults, another faction name, or move under Chapter 13 which is brief and lacking)

### The Sith and Jedi
- [ ] Find room for both Sith and Jedi codes
- [ ] Expand the ideological side of both orders

### Art to Commission
- [ ] Galaxy Map depicting the new Mandalorian Wars and Malak's conquest

### Races
- [ ] Expand the Twi'lek writeup (and other species entries)

### Other Factions
- [ ] Expand Czerka, the Exchange, the Hutt Cartels, and regional powers (all grossly underexplored)

### Policy for Homebrew / Introducing Legends Subjects
- [ ] Define policy for integrating Legends material into the setting

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
