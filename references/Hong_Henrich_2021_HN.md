---
type: paper
year: 2021
authors: [Hong, Henrich]
journal: HN
themes: [cultural_evolution, ritual]
projects: []
theories: [divination_as_epistemic_technology, bayesian_belief_updating_divination, credibility_enhancing_displays, cultural_group_selection]
---

# Hong and Henrich (2021) The Cultural Evolution of Epistemic Practices: The Case of Divination

#type/paper #theme/cultural_evolution #theme/ritual #journal/HN #theory/divination_as_epistemic_technology #theory/cultural_group_selection

**Bibliography**: Hong, Ze, and Joseph Henrich. 2021. "The Cultural Evolution of Epistemic Practices: The Case of Divination." *Human Nature* 32:622–651. https://doi.org/10.1007/s12110-021-09408-6

## Topic

The paper addresses the cross-cultural ubiquity and historical persistence of divination practices despite their apparent epistemic inefficacy. The puzzle is framed at two levels: why do people believe divination generates accurate information, and why do such beliefs persist across generations even as evidence of failure accumulates? The authors integrate ethnographic evidence, historical analysis, and formal computational modeling to argue that divination is best understood as an epistemic technology, and that systematic biases in cultural information transmission explain its persistence.

## Key Theory / Framework

The paper's first theoretical move is to classify divination as an **epistemic technology** — a tool or method employed to reveal hidden information — rather than as expressive, political, or anxiety-reducing behavior. The argument rests on three recurrent functional features of divination cross-culturally: it is used for important decisions; it is costly and often requires a specialist; and it is approached in ways (repetition to verify results, discrimination among diviners by skill) that only make sense if actors are genuinely seeking accurate information.

The paper's second move is to construct a **formal Bayesian belief-updating model** to explain how individuals might systematically overestimate the efficacy of divination even while processing information reasonably. Each individual's belief in a technological practice (Δ) is represented as a beta distribution with parameters α and β (positive and negative evidence respectively); the mean α/(α+β) approximates subjective efficacy. Individuals update from three sources: personal experience, testimony from others, and observation of others' behavior. The model identifies three conditions that produce systematic overestimation: (i) strong intuitive priors (large α₀); (ii) underreporting of negative evidence (parameter θ); (iii) high perceived benefit-to-cost ratios (b/c) combined with high epistemic weight on observed action (w₀), which causes observers to misinfer strong belief from high action rates.

The paper also applies **CREDs (Credibility-Enhancing Displays; Henrich, 2009)** as a mechanism: observing costly actions (paying a diviner when ill) increases learners' confidence in the practice's efficacy even when the underlying causal mechanism is absent.

Finally, the paper proposes that the global decline of divination and the spread of scientific epistemology constitute a case of **cultural group selection**: European scientific and military technology gave European populations an advantage in intergroup competition; colonial diffusion and prestige-biased transmission then spread both the technologies and the epistemic institutions that generate them.

## Data & Methods

- **Fieldwork site**: Southwestern China; Yi ethnic group (Sichuan province) and Wa ethnic group (Yunnan province); described as small-scale agriculturalists with substantial market integration and access to modern medicine but retaining much traditional culture
- **Fieldwork duration**: Four months (ethnographic)
- **Interview N**: 76 Wa and Yi villagers (interview protocol in Electronic Supplemental Material [ESM])
- **Survey N**: 47 Yi adults
- **Survey instrument**: Direct question — "What percentage of the time do you think divination/magic (迷信) works?" — with responses recorded as a histogram (Fig. 2)
- **Regression analysis**: ESM Table S1; predictors: sex, age, formal schooling; outcome: perceived accuracy percentage
- **Agent-based simulation**: Individuals represented with beta(α, β) belief distributions; updated Bayesian-style from personal experience, testimony, and observed action; parameters: α₀/β₀ (prior), θ (proportion of negative outcomes unreported), b/c (perceived benefit-to-cost ratio), w₀ (epistemic weight on observed action); true efficacy set at r=0.1; multiple simulation runs; results reported as 95% CI from 10 independent runs per parameter combination; parameters listed in ESM Table S2
- **Unit of analysis (simulation)**: Individual agents across generations
- **Historical and comparative evidence**: Ancient Greece, early China, Japan (Meiji era), China (May Fourth Movement); drawn from secondary historical and ethnographic sources cited throughout

## Key Findings

### Finding 1: Wa and Yi villagers treat diviners as skilled practitioners whose accuracy can be evaluated

96% of 76 interviewed Wa and Yi villagers believe that certain diviners are "better" than others. 100% (n=16) of respondents asked about consulting multiple diviners made the analogy that this is like seeking advice from multiple doctors. Local doctors confirmed the instrumental orientation: one stated that "the primary goal of local health education is to convince people to go to the hospitals first when they get ill," indicating that divination and modern medicine are treated as functional alternatives by villagers. The Yi employ a two-step divination procedure (egg yolk reading followed by sheep shoulder blade burning) as corroborating evidence, and client skepticism about the first result triggers repetition of the full procedure until an auspicious sign appears.

### Finding 2: Perceived accuracy is substantially above true efficacy but shows marked individual variation

Among 47 Yi adults, mean perceived accuracy of divination/magic was 64.25% (SD=26.48). 83% of participants reported values over 50%; 9% reported that divination never works. The modal response was approximately 75%. The distribution does not pattern with sex, age, or level of formal schooling (regression in ESM Table S1). The authors note that responses may be biased downward because the interviewer was an ethnic Han from the United States.

### Finding 3: Strong intuitive priors prevent belief convergence to true efficacy

Simulation results (Fig. 4) show that larger α₀ values shift agents' equilibrium belief distributions toward 1 (strong belief in efficacy). Crucially, because each new generation of agents begins with fresh innate priors, empirical experience is insufficient to overwhelm intuitive prior beliefs. This "reassertion of the prior" mechanism means that, even under optimal Bayesian updating, populations may sustain substantial confidence in the efficacy of an epistemically worthless practice across generations. Other parameter values held constant at b=5, c=1, θ=0.0; true efficacy r=0.1; mean equilibrium beliefs were 0.11 (α₀=1), 0.22 (α₀=10), and 0.34 (α₀=20).

### Finding 4: Underreporting of negative evidence inflates equilibrium beliefs

With no underreporting (θ=0.0), mean equilibrium belief was 0.19 — slightly above true efficacy (r=0.1) due to priors alone. With 30% underreporting (θ=0.30), mean rises to 0.26; with 60% underreporting (θ=0.60), mean rises to 0.32 (Fig. 5; other parameters: α=β=1, b=5, c=1). The no-underreporting distribution falls closest to the true efficacy vertical line. The authors attribute plausible underreporting mechanisms to: (a) confirmation bias; (b) diviners' reputational incentives to advertise successes; (c) norm psychology, in which revealing failed predictions constitutes a norm violation in communities where divination is dominant. Historical Chinese textual records show significant underreporting of failed divination predictions as well as failed rainmaking.

### Finding 5: High perceived benefit-to-cost ratios generate overestimation via behavior observation

When perceived benefit is large relative to cost, most individuals perform the action regardless of fine differences in their underlying belief distribution — a piecewise relationship between belief and action (b/c). Naive observers who weight observed action heavily (large w₀) then misinfer high belief from high action rates. Simulation results (Fig. 7): mean equilibrium beliefs were 0.092 (b/c=5), 0.145 (b/c=10), and 0.136 (b/c=20), all compared to true efficacy r=0.1; action rate for b/c=5 was 0.11, meaning few agents acted, and the low-action signal pulled beliefs toward lower efficacy. The high b/c case reverses this: near-universal action provides misleading evidence of near-universal belief. When b/c=1 (break-even), w₀ is negatively correlated with efficacy estimates because no individual acts.

### Finding 6: Scientific epistemology spread as cultural group selection

The paper argues that the global decline of divination cannot be explained without the diffusion of Western scientific institutions. Two historical cases are analyzed: (a) Meiji Japan — following exposure to Western military technology (Perry expedition, mid-19th century), Japan established Western-style scientific and educational institutions; traditional practices including divination were labeled superstitious (迷信/めいしん) and some banned; (b) Republican China — the May Fourth Movement (1919) proposed categorical rejection of traditional culture in favor of Western democracy and science; during the Republic of China era (1912–1949), divination came to be viewed as irrational superstition to be eradicated. Both cases illustrate that internal epistemic modernization is difficult; external group-level influence was required. The authors interpret this as cultural group selection: European technological advantage generated colonial diffusion and prestige-biased transmission of both the products and the institutions of science.

## Relevance to This Project

## 학술 대화 / Scholarly Conversation

- **alternative**: [Sosis (2003) *HN*](../references/Sosis_2003_HN.md) — Sosis explains persistence of religious behavior via costly commitment signaling (why those who believe perform rituals at greater cost, sustaining community credibility); Hong & Henrich explain persistence via belief-formation biases in cultural transmission (why individuals come to believe in epistemic efficacy in the first place); these are complementary but distinct mechanisms for religious/ritual persistence

## Verification Metadata

- **Layer used**: Layer 1 — `papers/papers_md/Hong_Henrich_2021_HN.md` — full read 2026-06-11
- **Empty sub-sections**: Relevance to This Project (no active project assigned)
- **Notes**: Fig. 5 caption contains a typo in the original published paper — θ values for the two underreporting conditions are printed as "0.13" and "0.0" but should be 0.30 and 0.60, as confirmed by the prose ("30% and 60% negative cases not revealed") and the internal inconsistency of two θ=0.0 conditions yielding different means (0.19 vs. 0.32). Fig. 7 values (b/c conditions) read cleanly.
- **Last verification**: 2026-06-11
