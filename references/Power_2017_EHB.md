---
type: paper
year: 2017
authors: [Power]
journal: EHB
themes: [csr, ritual, cooperation, hbe]
projects: []
theories: [costly_signaling, signaling_theory_religion, multimodal_signals, credibility_enhancing_displays]
---

# Power (2017) Discerning Devotion: Testing the Signaling Theory of Religion

#type/paper #theme/csr #theme/ritual #theme/cooperation #theme/hbe #journal/EHB #theory/costly_signaling #theory/signaling_theory_religion #theory/multimodal_signals

**Bibliography**: Power, Eleanor A. 2017. "Discerning Devotion: Testing the Signaling Theory of Religion." *Evolution and Human Behavior* 38:82–91.

## Topic

This paper tests the signaling theory of religion from the perspective of the *receiver*, not the signaler. While prior research establishes that religious signalers are more prosocial (the signaler-side test), the author asks whether signal receivers actually perceive religious participants as more devout and prosocial. Drawing on 20 months of ethnographic fieldwork in two villages in Tamil Nadu, South India, the paper finds that different modes of religious practice — regular worship, public ritual acts, and possession — are informative of distinct sets of reputational qualities, and that villagers attend to the full suite of religious signals when evaluating their peers' character.

## Key Theory / Framework

The paper applies the **signaling theory of religion**, which holds that costly religious acts function as honest signals of an individual's commitment to the prosocial beliefs and values of the religious community. Signal honesty is maintained because the perceived costs of carrying out religious acts are higher for those not genuinely committed, so only truly committed individuals will choose to bear them (drawing on Grafen, 1990 and Akerlof, 1970 as signal honesty mechanisms). The author argues that for religious practice to constitute genuine "signals," researchers must examine not only whether signalers are actually more prosocial but also whether receivers attend to and correctly interpret those signals — a previously neglected side of the signaling framework.

The paper extends the basic costly signaling framework with two concepts from behavioral ecology. First, **multimodal signals**: different religious modalities (regular worship, public ritual acts, possession) operate as distinct signaling channels, each with its own costs, observability level, and reputational implications. Second, **multiplex signals**: each religious modality simultaneously conveys information about multiple distinct character traits, and different receivers may attend to different aspects of the same signal (the author cites Higham & Hebets, 2013; Partan & Marler, 1999, 2005; Hebets et al., 2016 for the multimodal/multiplex framework from behavioral ecology).

The paper derives two predictions:

> (1) People who invest more and costlier ways in the religious life of the village will be perceived as more devout and more prosocial. (2) Participating in more and costlier ways in the Mariyamman festival will lead to increased recognition as devout and prosocial in the days immediately following.

The paper frames the short-term festival effects in terms of **Bayesian updating**: villagers have strong priors about well-known older individuals, so festival acts produce less reputational revision for them than for younger, less-established individuals. Henrich's (2009) **credibility-enhancing displays (CREDs)** model is noted in the discussion as according "well with this broader signaling framework."

## Data & Methods

- **Data source**: original ethnographic fieldwork data; household census, free-list reputational surveys, festival participation records; official festival organizers' records and video footage for Mariyamman festival
- **Country/region**: Tamil Nadu, South India
- **Villages**: "Tenpatti" and "Alakapuram" (pseudonyms); Vaigai River area; 164 households in Tenpatti (371 adults) and 201 households in Alakapuram (438 adults)
- **Time period**: October 2011 – August 2013 (20 months); household census December 2011 – April 2012; reputational surveys February 2013 (Alakapuram) and April 2013 (Tenpatti); post-festival survey August 2013
- **N**: 809 adult residents (age 18+); 782 surveyed (97% overall; 96% Alakapuram, 98% Tenpatti); post-festival subsample N=50 (stratified random sample of Tenpatti residents, stratified by caste)
- **Unit of analysis**: individual adult villager
- **Religious denominations**: Hindu, Roman Catholic, Church of South India (CSI Protestant), non-denominational evangelical Christian; multiple caste groups (jati)
- **Religious practice variables**:
  - *Regular worship* (binary): worships at church/temple at least once per week (self-report + key informant corroboration); 82% of CSI residents and 72% of Catholics attend weekly; 44% of Hindu residents in Tenpatti visit the Mariyamman temple weekly; very few Hindu residents in Alakapuram attend regularly
  - *Weighted public ritual tally*: acts over the past year weighted by cost/difficulty; 37 respondents (stratified random, both villages) sorted 21 common acts on three 3-point scales (monetary cost; difficulty/pain — these two found equivalent by consensus analysis); consensus analysis (Romney, Weller, & Batchelder, 1986) in UCINET confirmed good fit to consensus model; each act weighted doubly: one score for monetary cost and one for difficulty/pain; 80% of villagers undertook at least one public ritual act in the previous year
  - *Possession* (binary): 43 residents (7%) identified by key informants (corroborated by the author) as regularly becoming possessed
  - *Weighted Mariyamman festival tally*: same weighting applied to 2013 Tenpatti Mariyamman festival acts; 61 of 255 adult Hindu Tenpatti residents participated (23% of adult Hindu residents)
- **Dependent variables**: nominations for 8 reputational qualities via free-listing (interviewees listed all those in the village with each quality, prompted to think of young, old, men, and women); qualities: (1) hardworking, (2) generous, (3) good at giving advice, (4) influential, (5) good character, (6) devout, (7) physically strong, (8) knowledgeable at carrying out functions and rituals; interviewees named an average of 18 people 26 times total; each villager was named on average 21 times by 14 individuals
- **Controls**: age, gender, caste, years of education, number of resident consanguineous kin (adults with r ≥ 0.125; analyzed in Descent, Hagen, 2005), whether ever held a committee or panchayat position
- **Method**:
  - *Prediction 1 (long-term)*: hurdle models (Cameron & Trivedi, 2013; Mullahy, 1986); binomial component predicts if nominations are zero or positive; truncated negative binomial component predicts magnitude among those nominated; overdispersion accommodated by negative binomial distribution; 8 separate hurdle models; stepwise model selection; R (R Core Team, 2014) with pscl package (Jackman, 2014; Zeileis et al., 2008)
  - *Prediction 2 (short-term)*: linear regression; outcome = change in percent of nominations received from before to after the Mariyamman festival (percent used rather than raw count because total nominations differ between the two survey waves); same covariates; 8 separate models

**Table 1 summary statistics**: Age mean 42.33 (SD 14.98); 455 F / 354 M; weighted public ritual tally mean 7.06 (SD 5.32, median 6, range 0–37); regular worship N=259 (32%); possession N=43 (5%); weighted Mariyamman festival tally (N=255 Hindu Tenpatti residents) mean 2.66 (SD 6.01, median 0, range 0–28).

## Key Findings

### Finding 1: Regular worship broadly increases nominations for nearly all prosocial qualities

In the binomial component of the hurdle models, regular worship significantly increases the odds of being nominated for every reputational quality except physically strong (Table 2). In the count component, among those nominated at least once, regular worship further increases expected nominations for generous (0.482, p<0.05), gives good advice (0.792, p<0.05), good character (0.470, p<0.05), and devout (1.409, p<0.001). The author argues the stronger effect of regular worship — relative to dramatic public ritual acts — reflects the accumulation of many months and years of visible demonstrations; consistent low-key worship is seen as an unassailable marker of devotion and prosociality precisely because it is not eye-catching or crowd-drawing.

### Finding 2: Weighted public ritual tally increases odds of nomination for most qualities except influential and good character

In the binomial component, the weighted tally is positively correlated with odds of being nominated for all qualities except influential (0.025, ns) and good character (0.025, ns; Table 2). Significant binomial coefficients include hardworking (0.136, p<0.001), devout (0.086, p<0.001), physically strong (0.064, p<0.01), and ritual knowledge (0.054, p<0.01). In the count component, the tally further increases expected nominations for devout (0.067, p<0.001) and gives good advice (0.051, p<0.05). An individual would need a weighted tally of 8 (roughly equivalent to one dramatic act and one simple act) to produce the same odds of being nominated as devout that regular worship alone confers.

### Finding 3: Possession marks someone as devout but carries negligible or negative associations with other qualities

Possession significantly increases odds of nomination as devout (binomial coefficient 2.208, p<0.01) and decreases odds of being seen as hardworking (−1.155, p<0.05; Table 2). In the count component, possession increases expected nominations for devout (1.842, p<0.001) and ritual knowledge (1.279, p<0.01), but decreases expected nominations among those nominated as influential (−2.762, p<0.05). The author interprets this as: during possession, the relevant signaler is the deity rather than the possessed person, so possession reveals fervent belief but conveys limited insight into the individual's own character and capabilities. The strong cultural association between possession and low-caste, low-class women in Tamil Nadu (Kapadia, 1995) may further dampen any positive associations despite statistical controls.

### Finding 4: Short-term festival acts increase recognition for hardworking and physically strong; devout effect is smaller

In the post-festival linear regressions, the weighted festival tally is significantly positively associated with change in nominations for hardworking (β=0.017, p<0.05; R²=0.143, adj. R²=0.097) and physically strong (β=0.027, p<0.05; R²=0.158, adj. R²=0.113; Table 3). A person undertaking two dramatic acts at the festival is predicted to receive approximately one additional nomination as physically strong and approximately two additional nominations as hardworking. Devout shows the largest coefficient (β=0.028, p<0.10) but the lowest R² (0.049), driven by near-zero coefficients for all other covariates in that model.

### Finding 5: Short-term festival effects are concentrated entirely in the under-40 group

Splitting the 255 adult Hindu Tenpatti residents at age 40, festival participation significantly alters reputation only for those under 40 (Table 4). Under 40 (N=103): hardworking (β=0.021, p<0.05), good advice (β=0.023, p<0.05), good character (β=0.028, p<0.05), physically strong (β=0.049, p<0.01). Age 40 and over (N=149): no significant effect for any quality. There is no significant difference in the level of festival participation between age groups (mean weighted festival tally 8.25 for under-40 vs. 8.00 for over-40; t=−0.21, p=0.831). The author interprets this via Bayesian logic: for older, well-known individuals villagers already have ample prior information and need only minimal updating; for younger, less-established individuals each signal is more informative.

### Finding 6: Festival acts form part of an accumulated prior, not an isolated signal

Pearson correlation between weighted festival tally and year-long public ritual tally: r=0.29 (p<0.0001). Mean weighted festival tally is 3.10 for regular worshippers vs. 1.06 for non-regular worshippers (t=−3.86, p=0.0002). Only five of the 61 festival participants had no other recorded public ritual acts in the previous year. Festival acts are thus one new data point added to a long prior record, which explains why short-term effects are smaller than long-term associations.

### Finding 7: Devout reputation does not mediate the prosocial reputation effects

Most reputational qualities are weakly correlated with the reputation for being devout (Table A.11 in Supplementary Materials). The author concludes that being perceived as devout does not mediate the other prosocial associations; rather, religious practice directly and simultaneously predicts both devotion and the other prosocial traits. The most nominated person in Tenpatti for devout was named by 179 villagers (50% of the village); the next most nominated person received exactly 100 fewer nominations (footnote 12).

## Relevance to This Project

*(No active project assigned. Update when a project hub is created.)*

## Scholarly Conversation

- **builds on**: Sosis & Alcorta (2003, *Evolutionary Anthropology*) — foundational application of costly signaling to religious ritual; Power shifts the test to the receiver side
- **builds on**: Irons (2001, *Currents in Theology and Mission*) — signaling theory of religion; costly religious acts signal commitment to group norms
- **related to**: [Roes & Raymond (2003) *EHB*](../references/Roes_Raymond_2003_EHB.md) — both test evolutionary accounts of religion in EHB; Roes & Raymond test the societal-level mechanism (between-group competition → society size → moralizing gods); Power tests the individual-level mechanism (religious acts → reputation); complementary levels of analysis
- **related to**: [Lang & Kundt (2023) *RBB*](../references/Lang_Kundt_2023_RBB.md) — both apply the Hebets et al. (2016) complex signaling framework to ritual/religious behavior; Power's "multiplex" concept parallels Lang & Kundt's "pluripotent"; both treat ritual as a multi-channel signaling system, applied independently at different levels (individual ethnographic vs. evolutionary)

## Verification Metadata

- **Layer used**: Layer 1 — `papers/papers_md/Power_2017_EHB.md` — full read 2026-06-10
- **Empty sub-sections**: none
- **Last verification**: 2026-06-10
