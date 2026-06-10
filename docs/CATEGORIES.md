# Categories and Journals

The wiki's category structure and tracked journal list. Customize for your subdiscipline.

---

## Topic Categories

Six core categories aligned with an interdisciplinary position spanning religious studies, evolutionary anthropology, and cognitive science of religion. Each has its own folder under `general/` with `0_index.md` as the landing page.


| Category | Folder | Covers |
|---|---|---|
| Cognitive Science of Religion | `general/csr/` | MCI, agency detection, intuitive theism, dual inheritance, supernatural agent cognition, mentalizing, teleological bias|
| Cultural Evolution | `general/cultural_evolution/` | cultural transmission, dual inheritance theory, gene-culture coevolution, prestige/content bias, norm psychology, cumulative culture |
| Ritual & Costly Signaling | `general/ritual/` | ritualization, coalitional psychology,  threat-detection, signaling, CREDs, commitment displays |
| Cooperation | `general/cooperation/` | trust, prosociality, coordination |
| Human Behavioral Ecology | `general/hbe/` | Fertility, parental investment, mobility, kinship, division of labors |
| Behavioral Immune System | `general/bis/` | disgust, pathogen stress, prejudice, ingroup bias, purity norms |
| Korean Religions | `general/korean_religions/` | fork-religions, Korean protestantism, shamanism, new religious movements, everyday rituals |

### Cross-Cutting Categories

These exist for methodological/theoretical work that doesn't fit a substantive topic:

| Category | Folder | Covers |
|---|---|---|
| Methods | `general/methods/` | behavioral experiments, causal inference, Agent-based modeeling, phylogenetic comparative methods, multilevel models, etc. — substantive *methods* papers (not papers applying methods) |
| Theory | `general/theory/` | Signaling theory, evolutionary theory, Life history theory, Behavioral ecology etc. — cross-cutting theoretical frameworks |

### Area-Studies Categories (Independent Axis)

Population/area focus is *orthogonal* to topic. A paper can be in topic + area:

| Category | Folder | Notes |
|---|---|---|
| East Asia | `general/east_asia/` | Often pairs with kinship, division of labor, religious institutions |
| Korean Society | `general/korean_society/` | Often pairs with folk religions, multi-religious contact, shamanism, divination, religious demography |

Frontmatter convention: a paper's primary category is its *topic* category; area categories go in a separate `area_category` field or in the `themes` list.

---

## Tracked Journals

Journals get their own `journals/{Abbr}.md` file listing all ingested papers from that journal, newest-first. When a paper is ingested and its journal is "tracked", the wiki auto-registers it.

### CESR, Religious Studies & Evolutionary Anthropology (Always Tracked)

| Journal | Abbreviation | File |
|---|---|---|
| Evolution and Human Behavior | EHB | `journals/EHB.md` |
| Evolutionary Human Sciences | EHS | `journals/EHS.md` |
| Human Nature | HN | `journals/HN.md` |
| Behavioral and Brain Sciences | BBS | `journals/BBS.md` |
| Journal for the Scientific Study of Religion | JSSR | `journals/JSSR.md` |
| Religion, Brain & BehaviorR | RBB | `journals/RBB.md` |
| Journal of Cognition and Culture | JCC | `journals/JCC.md` |
| Current Anthropology | CA | `journals/CA.md` |
| American Anthropologist | AA | `journals/AA.md` |

### Adjacent Fields (Recommended)

| Field | Journals | Path |
|---|---|---|
| High-impact multidisciplinary | PNAS, NHB, ProcRoyB | `journals/Multi/` |
| Korean studies | 종교학연구, 종교와문화, 신종교연구 | `journals/Korean/` |


These get tracked if your work crosses fields. If not (e.g., pure ethnography lab), drop them.

### Adding a Journal to Tracking

When you ingest a paper from a journal not yet tracked, decide:

1. Is this likely to be a recurring ingestion source? → Add to tracked
2. One-off paper? → Leave untracked

Add a tracked journal by:
- Create `journals/{Abbr}.md` with the journal name as H1
- Add entry to CLAUDE.md's tracked journals table
- Add the journal abbreviation to your wiki's reserved `journal` frontmatter values

---

## Standard Abbreviation Table

The abbreviations Claude uses in citations and frontmatter:

| Journal | Abbreviation |
|---|---|
| Evolution and Human Behavior | EHB |
| Evolutionary Human Sciences | EHS |
| Human Nature | HN |
| Adaptive Human Behavior and Physiology | AHBP |
| Behavioral and Brain Sciences | BBS |
| Journal for the Scientific Study of Religion | JSSR |
| Religion, Brain & Behavior | RBB |
| Journal of Cognition and Culture | JCC |
| Current Anthropology | CA |
| American Anthropologist | AA |
| Proceedings of the National Academy of Sciences | PNAS |
| Nature Human Behaviour | NHB |
| Proceedings of the Royal Society B | ProcRoyB |
| Journal of Artificial Societies and Social Simulation | JASSS |
| Sociology of Religion | SocRel |
| Journal of Religion | JR |
| 종교학연구 | 종교학연구 |
| 종교와문화 | 종교와문화 |
| 한국문화인류학 | 한국문화인류학 |



For journals not in this list, use the most common short form. Consistency matters; once you use an abbreviation, stick with it. Wiki lint catches drift.

---

## Customization

For your subdiscipline, edit:

1. **`CATEGORIES.md`** (this file) — adjust the topic categories
2. **`CLAUDE.md`** — update the tracked journals table
3. **`templates/frontmatter_schemas.md`** — update reserved `themes` and `journal` values
4. **`general/{category}/0_index.md`** — create landing pages for each customized category

Don't fragment categories prematurely. Start with the seven defaults. Split a category only when one folder exceeds ~50 reference pages.

---

## Why Two Axes (Topic + Area)

A paper on costly signaling in Korean shamanic rituals belongs in two places conceptually:
- *Topic*: ritual & costly signaling
- *Area*: Korean society

Single-axis categorization forces a bad choice — either put it in ritual and lose Korea-cross-referencing, or invent a "Korean ritual" category that becomes a singleton.

Two-axis categorization keeps both:
- Folder placement: `general/ritual/` (topic primary)
- Frontmatter: `themes: [Ritual, CostlySignaling, KoreanReligions]`
- Linked from: `general/korean_society/0_index.md` "Ritual" sub-section

The two axes are *independent*. Most papers have one topic and zero areas (single-topic, non-area). Some papers have two areas (comparative). Rare papers have multiple topics + multiple areas.

The single-folder constraint (one paper goes in one folder) means: pick the topic that's most central to the paper's argument. Cross-references handle the rest.