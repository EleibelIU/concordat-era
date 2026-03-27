# THE CONCORDAT ERA — VISUAL STYLE GUIDE

## For Adobe InDesign Layout and Production

This document specifies every typographic, color, and layout decision for the Concordat Era setting book and its companion volumes. Use it as your master reference when building InDesign templates and paragraph/character styles.

---

## I. DESIGN PHILOSOPHY

The Concordat Era sits at the intersection of three visual traditions: the Star Wars universe's technological aesthetic, the Napoleonic period's typographic formality, and a grimdark weathering that intensifies in sections dealing with the Sith, the Ashen Campaigns, and the Force crisis.

The guiding principle: **classicism under stress.** The book should look like a formal galactic document that has survived hard use. Clean geometry and sharp type hierarchy give the reader confidence in the material's authority. Texture, wear, and tonal shifts remind the reader that the galaxy producing this document is fraying.

The FFG Star Wars RPG line (Edge of the Empire, Age of Rebellion, Force and Destiny) is the closest published precedent. Study those books for their panel construction, sidebar treatment, and integration of art with text. Then strip away the bright color coding and replace it with something more muted, more worn, more Napoleonic.

---

## II. PAGE SPECIFICATIONS

| Property | Value |
|---|---|
| **Page size** | US Letter (8.5" × 11" / 215.9mm × 279.4mm) |
| **Margins** | Top: 0.625" / Bottom: 0.75" / Inside: 0.875" / Outside: 0.625" |
| **Columns** | 2-column default, 10pt gutter |
| **Bleed** | 0.125" all sides |
| **Slug** | 0.25" all sides (for production notes) |
| **Binding** | Perfect bound or case bound; set inside margin larger to compensate for gutter loss |

### Column Grid

The primary layout uses a **2-column grid** with a **10pt (0.139") gutter**. Full-width elements (chapter openers, major art, pull-out sidebars) span both columns. Stat blocks and callout boxes can occupy a single column or span 1.5 columns with text wrap.

Build an underlying **6-column micro-grid** for positioning flexibility. The 2 main text columns each occupy 3 micro-columns. This lets you place sidebars, margin notes, and art at half-column or third-column increments without breaking the visual rhythm.

---

## III. COLOR PALETTE

### Core Palette

| Role | Swatch Name | Hex | CMYK | Usage |
|---|---|---|---|---|
| **Primary background** | Parchment Cream | #F2EBD9 | 0/3/12/5 | Default page background tint |
| **Dark background** | Void Black | #1A1A1E | 70/62/52/75 | Chapter openers, Sith sections, dramatic spreads |
| **Primary text** | Charcoal | #2C2C2C | 65/57/53/55 | Body text on light backgrounds |
| **Light text** | Pale Gold | #E8DCC0 | 6/9/22/0 | Body text on dark backgrounds |
| **Heading accent** | Burnished Gold | #C4A35A | 15/27/72/8 | Chapter titles, rule lines, ornamental elements |
| **Secondary accent** | Republic Crimson | #8B2D2D | 15/88/72/30 | Alerts, Sith-section headers, warning callouts |
| **Tertiary accent** | Officer Blue | #3D5A73 | 72/40/20/18 | Concordat-affiliated sections, hyperlinks, cross-references |
| **Muted olive** | Campaign Green | #6B7055 | 40/25/55/30 | Military sections, Remnant content, stat block headers |
| **Warm neutral** | Dust | #A89A82 | 18/22/35/12 | Table borders, secondary rule lines, margin annotations |

### Section-Specific Tonal Shifts

The base palette applies across the book. Certain sections shift the balance:

**Concordat/Republic content:** Emphasize Officer Blue and Burnished Gold. Backgrounds stay Parchment Cream. Clean, institutional feel. Think military dispatches and Senate records.

**Sith content (Triumvirate, Korriban, Diaspora):** Shift background toward Void Black or a deep charcoal (#242428). Headers in Republic Crimson. Body text switches to Pale Gold. Ornamental elements darken. The section should feel like reading by low light in a tomb.

**Remnant/Military Operations:** Campaign Green replaces Officer Blue as the secondary accent. Backgrounds may tint slightly cooler (#EDE8D6). Lean into the weathered-document feel: heavier texture overlays, rougher rule lines.

**Frontier/Wild Space:** Desaturate. Reduce accent usage. Backgrounds tint warmer and grainier. The frontier sections should look like they were printed on worse paper.

**Jedi/Force content:** Burnished Gold takes over as the dominant accent. Backgrounds brighten slightly. The visual grammar says "old authority" — formal, traditional, and slightly out of date.

---

## IV. TYPOGRAPHY

### Font Selection

The type system uses three families: a Didone serif for display, a humanist serif for body, and a geometric sans-serif for mechanical/technical elements. This combination bridges the Napoleonic-era typographic tradition (Didone) with science-fiction readability (humanist + geometric).

#### Display / Headers: **Playfair Display** (or Bodoni Moda)

- Free via Google Fonts; Bodoni Moda is the alternate if you want more Napoleonic severity
- High-contrast thick/thin strokes evoke Didot and Bodoni, the defining typefaces of Napoleonic-era printing
- Use for: Chapter titles, section headers (H1, H2), title page, part openers
- **Do not use below 14pt.** The extreme stroke contrast breaks down at small sizes.

If budget allows, consider licensing **Freight Display Pro** or **Didot LT** for a more refined version of this role.

#### Body Text: **Crimson Pro** (or Crimson Text)

- Free via Google Fonts
- Old-style serif with generous x-height and comfortable reading rhythm at 9–11pt
- Designed for sustained reading; performs well in two-column layouts
- Use for: Body text, extended sidebars, long-form descriptions
- If you want a commercial alternative with more weights: **Freight Text Pro**, **Garamond Premier Pro**, or **Minion Pro** (bundled with InDesign/Creative Cloud)

#### Technical / Mechanical: **Inter** (or Barlow)

- Free via Google Fonts; Barlow is an alternate with slightly more personality
- Clean geometric sans-serif for stat blocks, tables, page numbers, running headers, mechanical callouts
- Pairs with Didone display and humanist body without competing
- Use for: Stat blocks, table headers, page folios, running headers/footers, figure captions, sidebar titles when the sidebar is mechanical rather than narrative

#### Accent / Calligraphic (Sparingly): **Cormorant Garamond Italic** or **EB Garamond Italic**

- For epigraphs, in-universe quotes, and handwritten-style annotations
- Used at the start of chapters for an in-world quote or journal entry
- Limit to 2–3 instances per chapter maximum

### Type Hierarchy

| Element | Font | Weight | Size | Leading | Tracking | Case | Color |
|---|---|---|---|---|---|---|---|
| **Book title** | Playfair Display | Bold | 42pt | 48pt | +50 | Title Case | Burnished Gold |
| **Part title** (PART I, II, etc.) | Playfair Display | Bold | 30pt | 36pt | +100 | ALL CAPS | Burnished Gold |
| **H1 — Chapter title** | Playfair Display | Bold | 24pt | 28pt | +30 | Title Case | Burnished Gold on dark / Charcoal on light |
| **H2 — Section header** | Playfair Display | SemiBold | 16pt | 20pt | +20 | Title Case | Charcoal |
| **H3 — Subsection** | Inter | SemiBold | 12pt | 16pt | +30 | ALL CAPS | Officer Blue or Campaign Green |
| **H4 — Minor heading** | Inter | Medium | 10pt | 14pt | +20 | Title Case | Charcoal |
| **Body text** | Crimson Pro | Regular | 10pt | 13pt | 0 | Sentence case | Charcoal |
| **Body bold** | Crimson Pro | SemiBold | 10pt | 13pt | 0 | Sentence case | Charcoal |
| **Body italic** | Crimson Pro | Italic | 10pt | 13pt | +5 | Sentence case | Charcoal |
| **Sidebar body** | Crimson Pro | Regular | 9pt | 12pt | 0 | Sentence case | Charcoal or Pale Gold |
| **Sidebar title** | Inter | Bold | 11pt | 14pt | +40 | ALL CAPS | Burnished Gold |
| **Stat block header** | Inter | Bold | 10pt | 13pt | +30 | ALL CAPS | Pale Gold on dark bg |
| **Stat block body** | Inter | Regular | 9pt | 12pt | 0 | Sentence case | Charcoal or Pale Gold |
| **Table header** | Inter | SemiBold | 9pt | 12pt | +20 | ALL CAPS | Pale Gold on Campaign Green bg |
| **Table body** | Inter | Regular | 9pt | 12pt | 0 | Sentence case | Charcoal |
| **Caption** | Inter | Regular Italic | 8pt | 10pt | +10 | Sentence case | Dust |
| **Page folio** | Inter | Medium | 8pt | — | +30 | — | Dust |
| **Running header** | Inter | Medium | 7.5pt | — | +60 | ALL CAPS | Dust |
| **Epigraph / In-world quote** | Cormorant Garamond | Italic | 11pt | 15pt | +5 | Sentence case | Burnished Gold |

### Paragraph Styles to Build in InDesign

Create the following paragraph styles in your InDesign template. Name them with the prefix `CE_` for easy identification:

- `CE_Body`
- `CE_Body_Bold`
- `CE_Body_Italic`
- `CE_Body_FirstPara` (no indent, drop cap optional)
- `CE_Body_Continued` (first-line indent: 0.2")
- `CE_H1_Chapter`
- `CE_H2_Section`
- `CE_H3_Subsection`
- `CE_H4_Minor`
- `CE_Sidebar_Title`
- `CE_Sidebar_Body`
- `CE_Stat_Header`
- `CE_Stat_Body`
- `CE_Stat_Label` (bold, for "Aspects:", "Stunts:", etc.)
- `CE_Table_Header`
- `CE_Table_Body`
- `CE_Caption`
- `CE_Epigraph`
- `CE_Folio`
- `CE_RunningHead`
- `CE_Callout` (for boxed warnings, GM notes, etc.)
- `CE_BulletList`
- `CE_NumberList`

### Character Styles

- `CE_Char_Bold`
- `CE_Char_Italic`
- `CE_Char_BoldItalic`
- `CE_Char_SmallCaps` (for in-text game terms like FATE POINTS, STRESS)
- `CE_Char_Accent` (Burnished Gold highlight for key terms on first reference)

---

## V. LAYOUT ELEMENTS

### Chapter Openers

Each chapter opens on a recto (right-hand) page with a full-bleed dark background (Void Black or a dark atmospheric texture). The chapter number and title sit in the upper third in Burnished Gold. Below, a 3–5 line epigraph in Cormorant Garamond Italic (an in-world quote from a character relevant to the chapter's content). The lower half of the page can hold a full-width piece of art or a textured field with a brief chapter summary in Pale Gold Inter.

The facing verso (left-hand) page is blank or carries a full-bleed piece of art. Chapter content begins on the next recto.

This pattern gives the book a prestige-hardcover cadence. It costs pages. That's the point.

### Running Headers and Folios

**Verso (left) running header:** Book title in `CE_RunningHead`
**Recto (right) running header:** Current chapter title in `CE_RunningHead`
**Folio (page number):** Centered at bottom of page or aligned to outside margin, in `CE_Folio`

Running headers and folios do not appear on chapter openers, full-bleed art pages, or the title page.

### Rule Lines

Horizontal rule lines separate major sections within a chapter. Use Burnished Gold at 0.5pt weight. For Sith sections, switch to Republic Crimson at 0.75pt. For frontier/military sections, use Dust at 0.5pt.

A thin (0.25pt, Dust) horizontal rule below every running header creates visual separation from the text block.

### Sidebars

Two sidebar styles:

**Narrative sidebar** (lore, in-world perspective, character vignettes): Tinted background panel (Parchment Cream darkened 10%, or a parchment texture overlay). Left border: 2pt Burnished Gold rule. Title in `CE_Sidebar_Title`. Body in `CE_Sidebar_Body`.

**Mechanical sidebar** (stat blocks, Fate rules references, skill lists): Darker background panel (Void Black at 90% or a dark blue-grey). Title in `CE_Stat_Header`. Body in `CE_Stat_Body`. All text in Pale Gold or white. This is where Inter does its work.

### Tables

Table headers: Campaign Green background, Pale Gold text in Inter SemiBold ALL CAPS.
Table body: Alternating rows of Parchment Cream and a slightly warmer cream (#EDE6D0) for readability.
Table borders: 0.5pt Dust.
Sith-section tables: Swap header background to Republic Crimson. Body rows alternate Void Black (#1A1A1E) and a slightly lighter black (#242428). Text in Pale Gold.

### Callout Boxes

For GM warnings, player notes, and rules clarifications:

- 1pt Republic Crimson border
- Light cream interior (or Void Black interior for Sith sections)
- Small icon or glyph in the upper-left corner (a Concordat seal, a lightsaber, a dead-zone warning symbol)
- Title in Inter Bold, body in Crimson Pro Regular at 9pt

### Drop Caps

First paragraph of each chapter and each major section (H1, H2) begins with a drop cap: 3-line height, Playfair Display Bold, Burnished Gold. The drop cap should align to the baseline of the third line of body text.

### Ornamental Elements

Use sparingly. The Napoleonic influence comes through in:

- **Thin decorative rules** flanking Part titles (symmetrical hairline rules with a small central ornament — a star, a geometric knot, or a faction symbol)
- **Corner ornaments** on chapter opener pages (subtle, geometric, gold-on-dark)
- **Section dividers** between major parts of the book: a centered ornamental rule (not a fleuron or fantasy scroll — think neoclassical geometry. Stars, lines, angular patterns)

Avoid: filigree, Celtic knots, fantasy scrollwork, anything that reads "D&D." The visual language is imperial and restrained, not medieval.

---

## VI. TEXTURE AND BACKGROUND TREATMENT

### Base Page Texture

A subtle parchment or linen texture across all non-dark pages. Opacity 5–10% — the reader should feel it more than see it. Source a high-resolution (300dpi minimum) seamless tileable texture and place it on a locked background layer.

### Dark Page Texture

Chapter openers and Sith sections use a dark textured background: deep charcoal or black with a subtle noise grain or cracked-stone texture at 5–8% opacity. The effect should suggest ancient stone or carbon-scored metal, not digital darkness.

### Weathering

Apply weathering effects at the margins and corners: faint scorch marks, edge darkening (vignette), or foxing spots. These should be on a separate layer so you can dial them up (Sith/frontier content) or down (Concordat/Jedi content) per section.

- **Concordat sections:** Minimal weathering. Clean and institutional.
- **Remnant sections:** Moderate weathering. Worn but maintained.
- **Sith sections:** Heavy weathering. Charred edges, deep texture.
- **Frontier sections:** Moderate-to-heavy. Dusty, faded, sun-bleached quality rather than char.

---

## VII. ART DIRECTION NOTES

### Art Style

When commissioning or sourcing art, aim for:

- Painterly realism, not photorealism or cartoons
- Muted, desaturated palette that matches the color system above
- Napoleonic military portraiture influences: characters in formal poses, officers in structured compositions, battle scenes with the dynamic sweep of David or Gros paintings
- KOTOR visual DNA: Mandalorian armor, Jedi robes with a worn-campaign quality, Sith architecture that feels ancient rather than sleek, Republic ships that look functional rather than elegant

### Art Placement

- **Full-bleed art:** Chapter openers and section dividers. 1–2 per chapter.
- **Half-page art:** Placed at the top or bottom of a text page, spanning both columns. 2–4 per chapter.
- **Quarter-page / column art:** Character portraits, location vignettes, equipment illustrations. Placed within a single column with text wrap (8pt text wrap offset).
- **Spot illustrations:** Small (1"–2") illustrations in margins or inline with text. Faction symbols, weapon silhouettes, ship profiles. Tinted in the section's accent color.

---

## VIII. MASTER PAGES TO BUILD

Create these master pages in your InDesign template:

| Master Page | Description |
|---|---|
| **A-Default** | 2-column text page, light background, running headers, folios |
| **B-Dark** | 2-column text page, dark background (Sith sections), light text, crimson accents |
| **C-ChapterOpener** | Full-bleed dark background, centered title block, epigraph area, no running header/folio |
| **D-FullArt** | Full-bleed art placeholder, no text frame, no running header/folio |
| **E-HalfArt** | Upper half: full-width art placeholder. Lower half: 2-column text |
| **F-Blank** | No content (for facing pages opposite chapter openers) |
| **G-Appendix** | 2-column, denser layout (9pt body, 11pt leading), for reference tables and indices |
| **H-StatBlock** | Specialized layout with pre-placed stat block frames, dark sidebar panels |

---

## IX. INDESIGN PRODUCTION NOTES

### File Organization

Structure your InDesign project as a **Book file (.indb)** containing individual chapter documents:

```
concordat-era-book.indb
├── 00-front-matter.indd
├── 01-chapter-one.indd
├── 02-chapter-two.indd
├── ...
├── 13-chapter-thirteen.indd
├── A1-appendix-timeline.indd
├── A2-appendix-glossary.indd
├── supplement-factions-species.indd
├── fate-condensed-guide.indd
└── gm-guide.indd
```

Each chapter document uses the same template file (shared paragraph styles, swatches, and master pages via a **synchronized Book**).

### Layers

Use these layers in every document (top to bottom):

1. **Annotations** (non-printing, for production notes)
2. **Folios & Headers** (running headers, page numbers)
3. **Text** (all text frames)
4. **Art** (placed images, illustrations)
5. **Sidebar Panels** (background panels for sidebars and stat blocks)
6. **Rules & Ornaments** (decorative lines, section dividers)
7. **Page Texture** (background texture, locked)
8. **Page Background** (base color fill, locked)

### Export Settings (Print PDF)

- PDF/X-4 preset
- 300dpi image resolution minimum
- Embed all fonts (subset if needed)
- Include bleed marks and crop marks
- Color: CMYK for print / RGB for screen PDF

### Export Settings (Screen PDF)

- Smallest File Size preset, modified:
  - 150dpi images
  - RGB color
  - Include bookmarks from TOC
  - Interactive hyperlinks for cross-references
  - No bleed/crop marks

---

## X. TEMPLATE SHOPPING LIST AND RECOMMENDATIONS

### Recommended Starting Templates

You don't need to build from zero. These InDesign templates will give you pre-built paragraph styles, master pages, and layout structures that you can reskin with the Concordat Era's visual identity.

#### Tier 1: Best Fit (Buy One of These)

**1. Aegis Creative — Fantasy RPG Book InDesign Template 2**
- Price: ~$35
- Platform: DriveThruRPG / DMsGuild
- Format: .INDD files (InDesign native — works for you since you own InDesign)
- What you get: Complete book template with chapter structure, paragraph styles, master pages, organized as an InDesign Book file. Includes decorative elements (torn paper banners, wax seals, ornamental frames)
- Why it fits: The most complete RPG-specific InDesign template available. The decorative elements are fantasy-coded, but the underlying structure (paragraph styles, master pages, column grids, chapter organization) is exactly what you need. Strip the fantasy textures, apply the Concordat Era color palette and fonts, and you have a working production template in a few hours rather than days.
- Link: [DriveThruRPG](https://www.drivethrurpg.com/en/product/280742/fantasy-rpg-book-indesign-template-2)

**2. Aegis Creative — Horror RPG Book InDesign Template**
- Price: ~$20-35
- Platform: DriveThruRPG
- Format: .INDD files
- What you get: Dark-themed template designed for horror RPGs. Built-in dark backgrounds, light-on-dark text styles, atmospheric texture integration.
- Why it fits: The Sith sections, dead zone content, and grimdark tone of the Concordat Era map directly to horror RPG visual grammar. Buy this alongside the Fantasy template. Use the Fantasy template's structure for Concordat/Republic/Jedi sections, and the Horror template's dark-page treatment for Sith/frontier/Ashen content. Between the two, you have master pages for every tonal register in the book.
- Link: [DriveThruRPG](https://www.drivethrurpg.com/en/product/376336/Horror-RPG-Book--InDesign-Template)

#### Tier 2: Supplementary Resources

**3. Classic Explorer Template (Explorers Design)**
- Price: $20 minimum (itch.io pay-what-you-want)
- Platform: itch.io
- Format: InDesign + Affinity Publisher files
- What you get: Clean, gridded template with solid paragraph style foundations. More OSR/old-school focused, but the underlying grid system and style organization is excellent.
- Why it fits: Good for studying how a professional template structures paragraph styles and master pages. The free starter template lets you test before buying.
- Link: [itch.io](https://explorers.itch.io/classic-explorer-template)

**4. DMsGuild InDesign Templates and Beginner's Guide**
- Price: Free / PWYW
- Platform: DriveThruRPG / DMsGuild
- What you get: Letter and A4 templates, 43 paragraph styles, 16 character styles, 6 background options, stat block frames. Includes a beginner's guide to InDesign layout.
- Why it fits: Even if you don't use this template directly, the beginner's guide is worth the download for anyone new to RPG book layout in InDesign. The paragraph style naming conventions are also a useful reference for building your own.
- Link: [DriveThruRPG](https://www.drivethrurpg.com/en/product/249157/InDesign-Templates-and-Beginners-Guide)

#### Tier 3: Learning Resources

**5. Eternal Rule Games — "How to Design, Typeset, and Lay Out Your Tabletop RPG Rulebook"**
- Free article/guide
- Covers page setup, grid construction, paragraph style creation, and export settings for InDesign specifically
- Link: [Eternal Rule Games](https://eternalrule.com/creating-your-rpg-supplement-part-3-layout/)

**6. Storytelling Collective — "Laying Out Your Solo Adventure Gamebook Using Adobe InDesign"**
- Online course (check for current pricing)
- Step-by-step InDesign workflow for RPG content
- Link: [Storytelling Collective](https://www.storytellingcollective.com/courses/solo-adventure-gamebook-layout)

**7. Javier Beltrán's Portfolio (Monte Cook Games layout)**
- Study this for professional RPG layout at the highest tier. Beltrán laid out a 160-page RPG book for Monte Cook Games with color-coded chapters, stat tables, pull quotes, and maps. His portfolio shows how a professional handles the exact problems you'll face.
- Link: [jpbeltran.com](https://jpbeltran.com/book-layout)

### Font Acquisition

All primary fonts in this style guide are free:

| Font | Source | License |
|---|---|---|
| Playfair Display | [Google Fonts](https://fonts.google.com/specimen/Playfair+Display) | SIL Open Font License |
| Bodoni Moda (alternate display) | [Google Fonts](https://fonts.google.com/specimen/Bodoni+Moda) | SIL Open Font License |
| Crimson Pro | [Google Fonts](https://fonts.google.com/specimen/Crimson+Pro) | SIL Open Font License |
| Inter | [Google Fonts](https://fonts.google.com/specimen/Inter) | SIL Open Font License |
| Cormorant Garamond | [Google Fonts](https://fonts.google.com/specimen/Cormorant+Garamond) | SIL Open Font License |
| Barlow (alternate sans) | [Google Fonts](https://fonts.google.com/specimen/Barlow) | SIL Open Font License |

If you want to upgrade to commercial fonts later, the premium equivalents are:

| Role | Free Font | Premium Upgrade | Approx. Cost |
|---|---|---|---|
| Display | Playfair Display | Freight Display Pro | ~$50-100 |
| Display (alt) | Bodoni Moda | Didot LT Std | ~$35-70 |
| Body | Crimson Pro | Freight Text Pro or Minion Pro (free with CC) | ~$50-100 or free |
| Technical | Inter | Aktiv Grotesk | ~$50-200 |

### Texture and Background Resources

Search these marketplaces for seamless tileable textures:

- **Textures.com** — High-res parchment, stone, metal textures. Many free with account.
- **CreativeMarket** — Search "parchment texture seamless" and "dark grunge texture seamless." Budget $10-30 for a texture pack.
- **Envato Elements** — Subscription model. Search "aged paper texture" and "dark stone texture." Good if you need volume.

For the Napoleonic weathering feel, search specifically for: "foxed paper texture," "aged vellum," "scorched paper edges," "linen paper texture."

---

## XI. WORKFLOW RECOMMENDATION

### Step-by-Step Production Path

1. **Buy the Aegis Creative Fantasy RPG Template 2** ($35). Open it. Study the paragraph styles, master pages, and book file organization. This is your structural foundation.

2. **Buy the Aegis Creative Horror RPG Template** (~$20-35). Study the dark-page master pages and light-on-dark text styles. You'll graft these into the main template for Sith sections.

3. **Download all fonts** from Google Fonts. Install them on your system.

4. **Clone the Aegis template.** Rename everything with the `CE_` prefix. Replace their fonts with yours (Playfair Display, Crimson Pro, Inter, Cormorant Garamond). Replace their color swatches with the Concordat Era palette from Section III.

5. **Rebuild master pages** to match Section VIII. You'll keep the Aegis template's structural bones (text frame positions, column grids, margin settings) but replace all visual elements (backgrounds, textures, ornaments, rule lines) with the Concordat Era's visual language.

6. **Build a test chapter.** Take Chapter 1 of the setting book and flow it into the template. This will reveal which paragraph styles need adjustment, which master pages need additional variants, and where the font sizing or leading needs tuning for your specific content density.

7. **Iterate on the test chapter** until you're satisfied. Then flow the rest of the book.

8. **Produce section-specific variants** as you reach Sith content, military content, and frontier content. Each tonal shift requires swapping master pages and may require alternate paragraph styles (e.g., `CE_Body_Dark` for light text on dark backgrounds).

---

*End of The Concordat Era: Visual Style Guide*
