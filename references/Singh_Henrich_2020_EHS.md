---
type: paper
year: 2020
authors: [Singh, Henrich]
journal: EHS
themes: [ritual, cultural_evolution, hbe]
projects: []
theories: [cooperative_costly_signalling, credibility_enhancing_displays, supernatural_otherness]
---

# Singh and Henrich (2020) Why do religious leaders observe costly prohibitions? Examining taboos on Mentawai shamans

#type/paper #theme/ritual #journal/EHS #theory/cooperative_costly_signalling #theory/credibility_enhancing_displays #theory/supernatural_otherness

**Bibliography**: Singh, Manvir, and Joseph Henrich. 2020. "Why do religious leaders observe costly prohibitions? Examining taboos on Mentawai shamans." *Evolutionary Human Sciences* 2:e32, 1–15. https://doi.org/10.1017/ehs.2020.32

## Topic

The paper investigates why religious leaders across human societies observe costly prohibitions on food and sex, using Mentawai shamans (sikerei) on Siberut Island, Indonesia as the empirical case. Citing Winkelman and White (1987) as coded in Singh (2018), the authors note that trance practitioners abstained from food, sex, or social contact in 83% of societies in the cross-cultural sample, yet few if any quantitative data exist testing functional explanations for this near-universal pattern. The paper tests three hypotheses—cooperative costly signalling, credibility-enhancing displays (CREDs), and supernatural otherness—that are described as not mutually exclusive.

## Key Theory / Framework

**Cooperative costly signalling** (Sosis & Alcorta, 2003): costly behaviors serve as reliable signals of an actor's cooperative intent. Observers who see a shaman self-deny should infer that the shaman is more cooperative.

**Credibility-enhancing displays (CREDs)** (Henrich, 2009): costly acts that are consistent with one's proclaimed beliefs enhance the credibility of those beliefs for observers. A shaman who follows religious taboos provides a behavioral cue that the shaman genuinely believes the religious rules; observers should infer stronger religious belief from the self-denying shaman. The authors note that some behaviors can serve simultaneously as CREDs and cooperative costly signals, but the categories are not equivalent.

**Supernatural otherness** (Eliade, 1958; Mauss, 2001): observers infer that someone who self-denies is different from normal humans, and this supposed difference makes it more conceivable that the self-denier has superhuman powers such as healing or divine contact. The authors note researchers have not specified the mechanism, but propose possible candidates: perceptions that the self-denier has strange preferences, unique cognitive abilities, or has undergone transformation (e.g., becoming purer) as a result of denial.

Table 1 specifies the distinguishing predicted inferences: cooperative costly signalling predicts greater cooperativeness; CREDs predict greater religious belief; supernatural otherness predicts both greater difference from normal humans and greater supernatural power.

## Data & Methods

### Study 1: Taboo documentation

- **Data source**: Structured field interviews, Siberut Island, Indonesia
- **Country/region**: Four cultural regions of southern Siberut: Sabirut (n = 20), Sarereiket (n = 27), Silaoinan (n = 21), Taileleu (n = 20)
- **N**: 88 participants (one excluded from permanent dietary taboo condition for admitted ignorance)
- **Unit of analysis**: Cultural region (taboo frequency across regions)
- **Methods**:
  - Free-lists for initiation and healing taboos
  - Checklist of 14 items for permanent dietary taboos (13 items identified from pilot interviews as mentioned by more than one respondent; 1 control item—Mentawai langur—expected to be freely consumed)
  - Cultural consensus analyses on checklist data using AnthroTools package in R (Purzycki & Jamieson-Lane, 2017); no inferential analyses on free-list data
- **Analytic criterion**: Taboos shared across at least three cultural regions identified as more resistant to change and thus more likely functionally important

### Study 2: Costliness of permanent dietary taboos

- **Data source**: Field ranking tasks, Siberut Island
- **Country/region**: Siberut (same fieldsite)
- **N**: 40 non-shamans
- **Methods**:
  - Compiled list of all Mentawai wildlife from PHPA (1995) conservation plan appendix, verified for edibility and local names via focus groups; resulted in 77 consumed non-aquatic species (74 excluding the three commonly tabooed to shamans)
  - Photo-based ranking task: 24 photographs (21 randomly drawn from 74 non-tabooed non-aquatic species + 3 tabooed land species: gibbon *Hylobates klossii*, white simakobu monkey *Simias concolor*, three-striped squirrel *Lariscus obscurus*); participants divided photos iteratively into 8 piles from "most willing to give up" (1) to "least willing to give up" (8); mean ranking calculated per item
  - Aquatic species: participants named top 3 river and top 3 ocean species by frequency and preference; items ranked by number of times named
- **Measure**: Willingness-to-give-up, stated by the authors to integrate both preference for an animal and its availability

### Study 3: Observer inferences about self-denying shamans

- **Data source**: Vignette field experiment, two villages in interior Siberut
- **Country/region**: Interior Siberut, Indonesia
- **N**: 96 participants initially; 68 in final analytic sample (excluded: 12 failed final comprehension check; 11 contradicted themselves on ≥3 of 4 pairs of questions targeting the same inference; 9 alternated between characters for ≥13 of 14 questions; 26 total failed at least one check, of whom 6 failed more than one; 2 additional excluded for experimenter error)
- **Unit of analysis**: Individual participant binary choice
- **Dependent variables**: For each of four trait dimensions—belief, cooperativeness, difference from normal humans, supernatural power—which of two described shamans exhibits more of that trait
- **Design**: Each participant received two shaman vignettes: one self-denying character (abstaining from either additional hunted animals or sex with wife) and one control character (stating food preferences without taboo). Character images and background details counterbalanced; category of self-denial (food or sex) randomized. Comprehension questions administered before and after trait questions.
- **Method**: Mixed effects logistic regression (glmer, lme4 package; Bates et al., 2015); main predictor = factor with four levels corresponding to inference type (belief, cooperativeness, difference, power); covariates: participant sex, counterbalanced information, category of self-denial; random effect for participant ID; effects package (Fox & Weisberg, 2019) for average probability estimates; emmeans package (Lenth, 2019) for pairwise comparisons with Holm–Bonferroni adjustment
- **Factor analysis**: Exploratory factor analysis (Supplementary Table S7) to test unidimensionality of each question set; belief and power were unidimensional; two cooperativeness questions (coop3 and trus1) and one difference question (diff1) did not load with others and were removed; post-removal Cronbach's alpha > 0.75 for belief, cooperativeness, and power; α = 0.55 for difference; for all four sets: unidimensionality criterion = 1
- **Data and code**: OSF project site, https://osf.io/3mbkz

## Key Findings

### Finding 1: Seven initiation taboos appear across all four cultural regions

Respondents reported 54 taboos on shamans during initiation; 13 were mentioned in at least three of the four cultural regions. Seven prohibitions were reported across all four regions: eating without self-control, eating sour foods, committing adultery, having sex with one's spouse, having sex with anyone, and doing any kind of work (including hunting, repairing a house, or tending to gardens). Eating without self-control is defined by the authors as eating while walking or casually sitting, or eating immediately foraged food; eating with self-control means eating only when sitting in a house with others, with food prepared at an earlier time.

### Finding 2: Nine healing taboos appear across all four cultural regions

Respondents reported 52 taboos during healing ceremonies. No taboos were mentioned in only three regions; nine were mentioned in all four study regions. As with initiation taboos, healing taboos center on work, food, and sex.

### Finding 3: Five animal species are permanently tabooed across all four regions

Cultural consensus analysis of the 14-item checklist identified five species permanently tabooed to shamans across all four cultural regions: eels (*Anguilla bicolor*), flounders (Pleuronectiformes), gibbons (*Hylobates klossii*), the white morph of the simakobu monkey (*Simias concolor*), and three-striped squirrels (*Lariscus obscurus*). The control item (Mentawai langur) was confirmed as non-tabooed: only one of 87 respondents reported it as prohibited, and that respondent specified the taboo required unique circumstances.

### Finding 4: Permanent dietary taboos vary in costliness; some target anomalous rather than costly items

Among 24 foraged land animals in the ranking task, the three tabooed non-aquatic species ranked: gibbon (10th), white simakobu monkey (16th), three-striped squirrel (21st) out of 24. Among river species, eel (*Anguilla bicolor*) ranked 2nd in preference and frequency (after shrimp). Among ocean species, no participant named flounder when listing preferred saltwater items; the authors note that interior Siberut communities never come into contact with flounders, and in follow-up conversations several participants admitted to never having eaten one.

The authors propose that permanent dietary taboos target not only costly items but also anomalous ones. All five tabooed species are known as *makatai* (bad, broken, evil). With the exception of the three-striped squirrel, all are anomalous: eels are described as slippery and compared with snakes in myths; flounders are regarded as "split fish" (*laitak katsila*); the white simakobu is the only white primate on the island; gibbons are likened to humans. The authors argue, citing Douglas (2002), Leach (1964), and Sperber (1996), that anomalous entities are regarded as impure or sacred, and that rejecting them may enhance perceptions of a practitioner's difference from normal humans.

### Finding 5: Participants infer self-denying shamans to be stronger believers in Mentawai religious rules (belief strongest)

In the vignette experiment (N = 68), average estimated probability that a participant selects the self-denying character for belief questions: Pr = 0.92 (95% CI: 0.85, 0.96). This is the highest of the four trait inferences and provides support for the CREDs hypothesis.

### Finding 6: Participants infer self-denying shamans to be more cooperative

Average estimated probability for cooperativeness: Pr = 0.88 (95% CI: 0.78, 0.94). Supports the cooperative costly signalling hypothesis.

### Finding 7: Participants infer self-denying shamans to have greater supernatural power

Average estimated probability for supernatural power: Pr = 0.84 (95% CI: 0.72, 0.91). Supports the supernatural otherness hypothesis (power prediction).

### Finding 8: Participants infer self-denying shamans to be more different from normal humans (weakest effect)

Average estimated probability for difference from normal humans: Pr = 0.78 (95% CI: 0.64, 0.88). This is the weakest of the four inferences but still well above chance. Supports the supernatural otherness hypothesis (difference prediction).

### Finding 9: Belief significantly exceeds difference; belief vs. power is marginally significant

Pairwise comparisons (Holm–Bonferroni adjusted): belief vs. difference: odds ratio = 3.19 (SE = 1.08, z-ratio = 3.42, p < 0.01). Belief vs. power: odds ratio = 2.20 (SE = 0.68, z-ratio = 2.54, p = 0.055, described by the authors as marginally significant). No significant pairwise differences among any other coefficients.

### Finding 10: Food and sex self-denial produce statistically indistinguishable inferences

The category of self-denial (food vs. sex) had no significant effect on any trait inference: odds ratio = 0.399 (SE = 0.242, p = 0.13). Many participants spontaneously referred to the self-denying character as *makeikei* (tabooed) regardless of which specific prohibition was depicted, likening the novel forms of self-denial to recognized taboos.

### Finding 11: Single shaman dominates healing calls; competition among shamans documented

In a sample of 44 healing ceremonies across two interior Siberut villages, a single shaman was called for 14 ceremonies (32%); the next most successful shaman was called for 6 (14%). The median number of ceremonies in which a shaman was called was 3; the mode was 1. The authors use this distribution to motivate the argument that shamans should benefit from promoting perceptions of prosociality, credibility, and supernatural power.

### Finding 12: Limitations acknowledged

The authors identify two limitations of Study 3. First, the self-denying character in the vignette went beyond normative taboo adherence—abstaining from additional hunted animals or abstaining completely from sex, rather than from the specific items (eels, gibbons, etc.) that normatively apply. The experiment thus risks capturing inferences about voluntary additional self-denial rather than normative adherence. Second, the food items the experimental character rejected (pangolins, Pagai Island macaques, flying foxes) differ from those actually tabooed to Mentawai shamans. The authors argue that two findings justify the interpretation despite these limitations: (a) food and sex conditions produced similar inferences, and (b) participants spontaneously classified the novel self-denial as *makeikei*.

## Relevance to This Project

*(No active project assigned.)*

## 학술 대화 / Scholarly Conversation

- **builds on**: [Singh (2018) *BBS*](../references/Singh_2018_BBS.md) — prior work establishing that shamans cross-culturally observe costly ascetic prohibitions; the present paper provides the first quantitative field-experimental test of observer inferences from shaman taboo adherence
- **related to**: [Power (2017) *EHB*](../references/Power_2017_EHB.md) — both test receiver-side inferences from costly religious behavior empirically; cited in the Discussion as prior evidence for costly religious signaling; Power tests multimodal signaling in an agrarian South Indian context, while Singh & Henrich focus on ascetic taboos in a small-scale horticulturalist society

## Verification Metadata

- **Layer used**: Layer 1 — `papers/papers_md/Singh_Henrich_2020_EHS.md` — full read 2026-06-14
- **Empty sub-sections**: none
- **Last verification**: 2026-06-14
