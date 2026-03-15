# Master Thesis Concept Outline

## "Can People Detect LLM-Generated Misinformation, and What Attentional Strategies Distinguish Successful Detectors?"

| Field | Detail |
|-------|--------|
| **Status** | Early concept / seed |
| **Program** | Cognitive Science, University of Warsaw |
| **Direction** | 2 (AI-generated content) + B (eye-tracking) + i (university students) |
| **Expected Timeline** | 1 academic year (concept → defence) |

---

## 1. Research Problem

### 1.1 Background and Rationale

The rapid proliferation of Large Language Models — including OpenAI's GPT-4, Anthropic's Claude, Google's Gemini, and a growing ecosystem of open-source alternatives — has fundamentally altered the landscape of online misinformation. These models can now produce highly fluent, grammatically impeccable, and contextually coherent text that is virtually indistinguishable from content produced by professional human writers. This capability represents a qualitative shift in the misinformation threat landscape that demands urgent empirical attention.

Historically, misinformation has been characterised by identifiable surface-level cues: grammatical errors, awkward phrasing, sensationalist language, logical inconsistencies, or obviously fabricated claims that strain credulity. Decades of media literacy education have trained critical readers to look for precisely these "red flags." However, LLM-generated misinformation may systematically bypass these heuristic defences. When the language itself is flawless and the argumentation internally coherent, what remains for the human reader to detect?

This creates an asymmetry of unprecedented scale: the cost of producing convincing fake content has collapsed to near-zero (requiring only a text prompt and API access), while the cognitive resources required to evaluate each piece of content remain finite and taxing. Understanding how — and whether — humans can navigate this new information environment is not merely an academic question; it is a societal imperative with implications for democratic discourse, public health communication, and institutional trust.

### 1.2 Key Unknowns

The following empirical gaps motivate this research:

- **Detection capability**: Can people reliably detect LLM-generated fake articles at above-chance levels, or has artificial text quality crossed a threshold of human imperceptibility?
- **Attentional mechanisms**: What attentional strategies — as revealed by fine-grained eye-tracking — differentiate successful detectors from those who are routinely deceived? Are these strategies conscious or automatic?
- **Cue utilisation differences**: Do people rely on fundamentally different evaluative cues when assessing AI-generated content versus traditional human-written misinformation? If the familiar red flags are absent, what (if anything) replaces them?
- **Individual difference predictors**: Which cognitive traits, thinking dispositions, and prior experiences predict detection ability in this new domain? Does analytical thinking remain protective, or does AI-generated content specifically exploit reflective processors?
- **Metacognitive calibration**: Are people aware of their own limitations in detecting AI-generated content, or do they exhibit dangerous overconfidence?

### 1.3 Why This Matters Now

The urgency of this research is amplified by several converging trends:

1. **Model capability is increasing exponentially** — each generation of LLMs produces more convincing text, meaning today's findings establish a critical baseline before the problem potentially becomes intractable.
2. **Democratisation of access** — open-source models and free-tier APIs make sophisticated text generation available to any actor with malicious intent.
3. **Scaling of disinformation operations** — state and non-state actors can now generate personalised, contextually relevant misinformation at industrial scale.
4. **Inadequacy of current defences** — automated detection tools (watermarking, classifier-based approaches) remain unreliable and easily circumvented, meaning human judgment remains the last line of defence for many information consumers.

---

## 2. Research Questions and Hypotheses

### 2.1 Research Questions

**RQ1 — Detection accuracy deficit:**
Is detection accuracy systematically lower for LLM-generated misinformation compared to human-written misinformation? This question addresses whether AI-generated content represents a categorically different (and more dangerous) class of misinformation from the reader's perspective.

**RQ2 — Attentional signatures of successful detection:**
What attentional patterns — including fixation duration distributions, Area of Interest (AOI) allocation, temporal dynamics of reading strategy, and regression patterns — characterise individuals who successfully identify LLM-generated misinformation versus those who fail? This question seeks a mechanistic, process-level account of what successful detection actually looks like in real-time cognitive processing.

**RQ3 — Moderating role of individual differences:**
Do individual differences in analytical thinking disposition, familiarity with AI systems, digital literacy competence, and open-minded thinking moderate detection ability? This question examines whether certain cognitive profiles confer protection — and conversely, whether certain profiles create vulnerability.

### 2.2 Hypotheses

**H1 — Accuracy deficit for LLM-generated content:**
Detection accuracy (proportion correctly classified as false) will be significantly lower for LLM-generated false articles compared to human-written false articles. The rationale is that LLM-generated content lacks the traditional surface-level cues (grammatical errors, sensationalist tone, logical gaps) that facilitate detection of human-written misinformation.

**H2 — Attentional strategy differences:**
Successful detectors will exhibit qualitatively different gaze patterns, specifically: (a) longer total fixation durations on source/metadata areas, indicating active source evaluation; (b) more regressions (re-reading of previously fixated text), indicating deeper critical processing; and (c) more non-linear reading patterns (scanning rather than serial reading), indicating strategic information search. These patterns reflect the deployment of effortful, analytic evaluation rather than passive, fluency-based acceptance.

**H3 — Protective role of analytical thinking and AI familiarity:**
Higher scores on the Cognitive Reflection Test (indicating disposition to override intuitive responses) and greater self-reported familiarity with AI systems (indicating calibrated expectations about AI capabilities) will independently predict better detection of LLM-generated content. The interaction between these predictors is of particular theoretical interest: AI familiarity may moderate the CRT effect by providing domain-specific knowledge about what AI text "should" look like.

**H4 — Metacognitive miscalibration:**
Confidence-accuracy calibration will be significantly poorer for LLM-generated items compared to human-written false items. Specifically, participants will exhibit higher confidence in incorrect judgments (accepting LLM-generated misinformation as true) because the very fluency and coherence of AI-generated text produces a subjective experience of comprehension ease that is misattributed to truthfulness (a fluency-truth illusion).

---

## 3. Methodology

### 3.1 Design Overview

This study employs a **within-subjects** experimental design in which each participant encounters all stimulus types, enabling direct comparison of detection performance across conditions while controlling for individual differences in baseline ability. The critical independent variable is **stimulus type** with three levels:

| Level | Description |
|-------|-------------|
| **True articles** | Genuine news articles from verified outlets |
| **Human-written false** | Known misinformation sourced from fact-checking databases |
| **LLM-generated false** | Artificially generated misinformation on matched topics |

The within-subjects approach maximises statistical power while minimising the required sample size — a practical advantage given the resource-intensive nature of eye-tracking data collection.

### 3.2 Participants

- **Target sample**: N = 60–80 university students (age 18+)
- **Justification**: An a priori power analysis (G*Power) for a within-subjects repeated-measures ANOVA with 3 levels, assuming a medium effect size (f = 0.25), α = .05, power = .80, and correlation among repeated measures of r = .50, yields a minimum required N of approximately 28. The target of 60–80 accommodates: (a) anticipated data loss from eye-tracking quality issues (~15–20% of participants), (b) sufficient power for individual-difference analyses and interaction effects, and (c) adequate sample for exploratory machine learning analyses.
- **Recruitment channels**: University participant pool systems, departmental mailing lists, social media posts in student groups, and snowball sampling through existing participants.
- **Inclusion criteria**: Native or near-native Polish/English (depending on stimulus language) reading proficiency, normal or corrected-to-normal vision, no diagnosed reading disorders.
- **Compensation**: Course credit or monetary compensation (amount TBD based on department norms).

### 3.3 Stimuli — The Critical Design Element

The quality and ecological validity of the stimuli are the single most important determinant of this study's contribution. The stimulus set must achieve the difficult balance of being controlled enough for experimental rigour while remaining naturalistic enough to generalise to real-world information encounters.

#### Stimulus Set Composition

A total of **45 short news articles** (150–200 words each), divided equally:

| Category | Count | Source |
|----------|-------|--------|
| True articles | 15 | Sourced directly from verified, reputable news outlets; lightly edited only for length standardisation |
| Human-written false | 15 | Sourced from established fact-checking databases (e.g., Snopes, AFP Fact Check, Demagog); represents "organic" misinformation as it circulates naturally |
| LLM-generated false | 15 | Generated using structured prompting protocol (see §3.4); represents the emerging AI-misinformation threat |

#### Matching Protocol

Stimuli are rigorously matched across conditions on the following dimensions:
- **Topic**: 5 content categories (e.g., health, politics, technology, science, economics) × 3 articles per type per category, ensuring within-topic comparisons are possible
- **Length**: All articles standardised to 150–200 words (±10%)
- **Reading level**: Flesch-Kincaid scores matched within 1 grade level across conditions
- **Recency**: All topics drawn from a defined date range to avoid familiarity confounds
- **Source presentation**: True articles attributed to real outlet names; false articles attributed to plausible but fabricated outlet names (to prevent recognition-based shortcuts)

#### Validation

Prior to the main study, all stimuli undergo:
1. **Independent rating** by 3–5 trained raters for naturalness, fluency, and perceived credibility (using standardised scales)
2. **Pilot testing** with a small sample (N = 10–15) to identify ceiling/floor effects and ensure difficulty is appropriately calibrated
3. **Iterative refinement** — articles that produce extreme accuracy rates (>90% or <10%) are replaced

### 3.4 Stimulus Generation Protocol for LLM-Generated Content

This protocol must be rigorous, reproducible, and documented in sufficient detail for replication:

1. **Multi-model approach**: Use at least 3 distinct LLMs (GPT-4, Claude, Llama-3 or equivalent) to avoid any single model's stylistic fingerprint being a confound. Final stimulus set should draw from all models.

2. **Structured prompting**: Each false article is generated using a standardised prompt template:
   > "Write a [length]-word news article about [topic] in the style of a professional journalist. The article should contain the following false claim: [specific false claim]. The article should read as credible and well-sourced. Include a plausible but fictional attribution."

3. **Quality control pipeline**:
   - Generate 5–10 candidate articles per required item
   - Rate each candidate for: fluency (1–7), coherence (1–7), perceived credibility (1–7), naturalness compared to genuine journalism (1–7)
   - Select the top-rated candidate that best matches its paired true and human-false articles on surface features
   
4. **Documentation**: All prompts, model versions, generation parameters (temperature, top-p), and selection decisions are logged for full reproducibility.

5. **Ethical consideration**: Generated misinformation is never released publicly; all stimuli are used only within the controlled experimental context and debriefed.

### 3.5 Measures

#### Behavioural Measures (per article)

| Measure | Scale | Purpose |
|---------|-------|---------|
| Truth judgment | Binary: Real / Fake | Primary DV — detection accuracy |
| Confidence | 7-point Likert (1 = not at all confident, 7 = completely confident) | Metacognitive calibration |
| Sharing intention | 7-point Likert (1 = definitely would not share, 7 = definitely would share) | Ecological validity — real-world consequence proxy |
| Reaction time | Milliseconds from article presentation to judgment | Processing time / deliberation index |
| Open-ended justification | Free text (optional) | Qualitative data on conscious strategy; coded for cue types mentioned |

#### Eye-Tracking Measures

**Equipment**: Tobii Pro Spectrum (or equivalent research-grade system) operating at minimum 600 Hz sampling rate. Higher temporal resolution enables precise analysis of fixation dynamics and micro-saccadic events.

**Areas of Interest (AOIs)** defined for each article:

| AOI | Content | Theoretical significance |
|-----|---------|------------------------|
| Source/Author | Publication name, author byline | Source evaluation behaviour |
| Headline | Article title | First impression formation, expectation setting |
| Body text | Main article content | Deep reading vs. skimming |
| Image area | Photograph or graphic (if present) | Visual credibility cues |
| Metadata | Date, category tags, URL indicators | Peripheral credibility indicators |

**Eye-tracking metrics extracted**:

- **Total fixation duration per AOI** — cumulative attention allocation
- **First fixation location** — initial attentional priority
- **Fixation count per AOI** — granularity of processing
- **Dwell time proportion** — relative attention distribution
- **Number of regressions** — re-reading, reconsideration, critical evaluation
- **Reading pattern classification** — linear (top-to-bottom) vs. scanning (non-sequential) vs. focused (concentrated on specific regions)
- **Pupil dilation** (exploratory) — cognitive effort / surprise
- **Saccade amplitude distributions** — global vs. local processing

#### Individual Difference Measures

| Instrument | Construct | Items | Citation |
|------------|-----------|-------|----------|
| Cognitive Reflection Test (CRT-7) | Analytic vs. intuitive thinking | 7 | Toplak et al. (2014) |
| Need for Cognition (short form) | Enjoyment of effortful thinking | 18 | Cacioppo et al. (1984) |
| Digital Literacy Scale | Competence in digital environments | ~15 | Hargittai (2005) or similar |
| AI Familiarity Questionnaire | Experience with and knowledge of AI tools | ~10 | Custom-developed, piloted |
| News Consumption Habits | Sources, frequency, platform usage | ~8 | Adapted from Reuters Digital News Report |
| Actively Open-minded Thinking | Willingness to revise beliefs | 7 | Baron (2019) |

### 3.6 Procedure

The entire experimental session is conducted individually in a controlled laboratory environment to ensure eye-tracking data quality.

| Phase | Duration | Activities |
|-------|----------|------------|
| **1. Informed consent & intake** | ~15 min | Written informed consent; demographics questionnaire; individual difference battery (CRT, NFC, digital literacy, AI familiarity, news habits, AOT) |
| **2. Eye-tracker setup** | ~3 min | Seating adjustment, chin rest positioning (if applicable), 5-point calibration, validation (accepting mean accuracy < 0.5° visual angle) |
| **3. Practice trials** | ~5 min | 3 practice articles (1 true, 1 human-false, 1 LLM-false) with corrective feedback and explanation; opportunity for questions |
| **4. Main experimental task** | ~35–45 min | 45 articles presented in fully randomised order; self-paced reading with eye-tracking; after each article: truth judgment → confidence → sharing intention → (optional) justification. Mandatory breaks after articles 15 and 30 (minimum 60 seconds, self-terminated) |
| **5. Post-task questionnaire** | ~5 min | Strategy self-report (what did you look for?); AI awareness questions (did you think any articles were AI-generated?); task difficulty ratings |
| **6. Debriefing** | ~5 min | Full disclosure of study purpose; explanation of stimulus types; provision of media literacy resources; opportunity for questions and withdrawal |

**Total session duration**: approximately 70–80 minutes.

**Quality control measures during data collection**:
- Re-calibration between breaks if drift exceeds 1° visual angle
- Tracking ratio threshold: exclude trials with < 75% valid gaze samples
- Participant-level exclusion if overall tracking ratio < 70%

---

## 4. Analysis Plan

### 4.1 Behavioural Analyses

**Primary analysis — Detection accuracy by stimulus type:**
- Repeated-measures ANOVA: accuracy ~ stimulus type (true / human-false / LLM-false)
- Planned contrasts: human-false vs. LLM-false (critical comparison for H1)
- Effect size reporting: partial η² and Cohen's d for pairwise comparisons

**Signal Detection Theory (SDT) framework:**
- Compute sensitivity (d') and response bias (criterion c) separately for:
  - Discrimination of human-false from true
  - Discrimination of LLM-false from true
- Compare d' values to test whether LLM content is genuinely harder to discriminate (reduced sensitivity) or whether participants simply adopt a more liberal criterion

**Mixed-effects modelling (full model):**
```
accuracy ~ stimulus_type * CRT * AI_familiarity + digital_literacy + NFC + AOT + (1 + stimulus_type | participant) + (1 | item)
```
- Random intercepts and slopes by participant; random intercepts by item (to generalise beyond specific stimuli)
- Model comparison via likelihood ratio tests and AIC/BIC

**Metacognitive calibration (H4):**
- Confidence-accuracy calibration curves computed separately by stimulus type
- Over/under-confidence index: mean confidence for incorrect trials
- Brier score decomposition (reliability, resolution, uncertainty)

**Reaction time analysis:**
- Linear mixed models: log(RT) ~ stimulus_type * accuracy + (1|participant)
- Tests whether correct detections take longer (reflecting deliberation) vs. shorter (reflecting automatic pattern recognition)

### 4.2 Eye-Tracking Analyses

**AOI-based analyses:**
- Mixed ANOVA: dwell time proportion ~ AOI × stimulus_type × accuracy (correct/incorrect)
- Critical interaction: Do successful detectors allocate proportionally more attention to source/metadata AOIs specifically for LLM-generated content?
- Bayesian analysis for key null results (if source checking does NOT predict success, this is theoretically important)

**Temporal dynamics:**
- Divide reading time into thirds (early / middle / late)
- Test when attentional differences between successful and unsuccessful detectors emerge
- Time-locked analyses: at what point do accurate responders begin fixating source information?

**Scanpath analysis:**
- Construct AOI transition matrices for each trial
- Compare transition patterns between correct and incorrect trials using Levenshtein distance or ScanMatch
- Identify signature sequences (e.g., headline → source → body vs. headline → body → judgment)

**Reading strategy profiling:**
- K-means or hierarchical cluster analysis on eye-tracking features to identify distinct reading strategy profiles (e.g., "careful checkers," "fluency-riders," "scanners")
- Test whether strategy cluster membership predicts accuracy differentially across stimulus types

### 4.3 Exploratory and Advanced Analyses

**Machine learning classification:**
- Feature set: all eye-tracking metrics + behavioural measures + individual differences
- Target: correct vs. incorrect detection of LLM-generated items
- Algorithms: Random Forest, SVM, and gradient boosting (XGBoost)
- Evaluation: nested cross-validation (outer: 5-fold for performance estimation; inner: 5-fold for hyperparameter tuning)
- Feature importance analysis (SHAP values) to identify most diagnostic predictors
- Practical question: Can we predict who will be "fooled" from their gaze behaviour alone?

**Qualitative analysis of justifications:**
- Thematic coding of free-text responses to identify cue categories
- Comparison of reported cues vs. actual gaze behaviour (do people know what they actually looked at?)
- Inter-rater reliability assessed via Cohen's κ

**Strategy awareness analysis:**
- Correlation between self-reported post-task strategy descriptions and objectively measured gaze patterns
- Tests metacognitive accessibility of detection strategies

---

## 5. Expected Contributions

### 5.1 Theoretical Contributions

- **Extends misinformation detection theory to AI-generated content**: The existing literature on fake news detection (dominated by Pennycook, Rand, and colleagues) has overwhelmingly used human-written stimuli. This study provides the first eye-tracking evidence for how people process AI-generated misinformation specifically, testing whether established theoretical frameworks (classical reasoning vs. intuition models) hold in this new domain.

- **Provides a mechanistic, process-level account**: Rather than merely documenting that people fail to detect AI-generated misinformation (which existing survey studies suggest), this research reveals *how* they fail — what they look at, what they miss, and when their processing goes wrong. This moves beyond outcome-level description to cognitive mechanism.

- **Tests the continued validity of source-checking heuristics**: If the primary defence against misinformation has been "check the source," does this strategy remain effective when the content itself provides no additional diagnostic cues? The eye-tracking data can directly test whether source-checking behaviour is both present and sufficient.

- **Informs dual-process models**: Tests whether detection of AI-generated content requires fundamentally different cognitive operations than detection of human-written misinformation, or whether the same analytical processes (indexed by CRT) are protective across both domains.

### 5.2 Practical Contributions

- **Media literacy curriculum design**: Identifies what attentional strategies actually work for detecting AI-generated content, directly informing what educators should teach. If source-checking predicts success, this validates existing curricula. If alternative strategies emerge, this demands curriculum reform.

- **Vulnerability profiling**: Identifies which cognitive profiles are most susceptible to AI-generated misinformation, enabling targeted intervention design. Are low-CRT individuals disproportionately affected, or does AI content fool everyone equally?

- **Platform and interface design implications**: If specific AOIs (e.g., source attribution areas) are critical for detection, this informs how platforms should design article layouts and where credibility indicators should be placed for maximum salience.

- **Policy-relevant evidence**: Provides empirical data relevant to policy debates about AI-generated content labelling, disclosure requirements, and platform governance.

### 5.3 Methodological Contributions

- **Establishes a replicable stimulus generation protocol**: The detailed, documented pipeline for creating controlled LLM-misinformation stimuli can be adopted by other researchers, standardising methodology in this emerging field.

- **Demonstrates eye-tracking as a tool for studying online credibility evaluation**: Extends eye-tracking methodology (traditionally applied to reading comprehension and advertising) to the critical applied domain of misinformation detection.

- **Provides a stimulus validation framework**: The matching, rating, and pilot-testing procedures create a template for rigorous stimulus development in AI-content research.

---

## 6. Feasibility Assessment

### 6.1 Required Resources

| Resource | Availability | Notes |
|----------|--------------|-------|
| Eye-tracking lab | Check with supervisor/department | Required: research-grade tracker (≥600 Hz), dedicated testing room, appropriate lighting |
| LLM API access | Available (commercial APIs) | Cost estimate: ~$50–150 for stimulus generation (depends on iteration needed) |
| Participant pool | University student population | 60–80 participants; realistic within 1–2 months of active data collection |
| Software — Stimulus presentation | PsychoPy (free) or SR Research Experiment Builder (licensed) | Integration with eye-tracker required |
| Software — Analysis | Python (free: pandas, statsmodels, scikit-learn), R (free: lme4, brms) | All open-source options available |
| Ethical approval | University ethics board | Required before any data collection; allow 4–8 weeks for review process |
| Pilot participants | 10–15 for stimulus validation | Can be recruited informally |
| Pre-registration | OSF or AsPredicted | Required before main data collection begins |

### 6.2 Timeline Feasibility

For a 1-year master thesis, a realistic timeline:

| Phase | Duration | Period |
|-------|----------|--------|
| Literature review & concept refinement | 2 months | Months 1–2 |
| Stimulus development & generation | 1.5 months | Months 2–3.5 |
| Ethics application & approval | 1.5 months | Months 3–4.5 |
| Pilot testing & stimulus validation | 1 month | Months 4.5–5.5 |
| Pre-registration | 2 weeks | Month 5.5 |
| Main data collection | 2 months | Months 6–8 |
| Data processing & analysis | 2 months | Months 8–10 |
| Writing & revision | 2–3 months | Months 9–12 |

### 6.3 Potential Challenges and Mitigations

| Challenge | Risk Level | Mitigation |
|-----------|------------|------------|
| Difficulty matching LLM and human stimuli | High | Iterative generation-and-rate pipeline; multiple LLMs; independent rater validation; willing to discard poor matches |
| Rapid LLM capability changes | Medium | Document exact model versions used; frame findings as "current state" benchmark; discuss generalisability in limitations |
| Eye-tracking data quality | Medium | Strict calibration standards; re-calibration protocol; liberal exclusion criteria with over-recruitment buffer |
| Lab scheduling constraints | Medium | Block-booking time slots; run multiple participants per day; recruit broadly to fill cancellations |
| Multiple comparisons / p-hacking risk | High | Pre-registration of all confirmatory analyses; clear separation of confirmatory vs. exploratory; correction for multiple tests (Holm-Bonferroni or Bayesian approach) |
| Participant fatigue (70–80 min session) | Low–Medium | Mandatory breaks; self-paced design; engaging task; compensation appropriate to duration |

---

## 7. Key Literature

### Foundational — Misinformation and Fake News Detection
- Pennycook, G., & Rand, D. G. (2019). Lazy, not biased: Susceptibility to partisan fake news is better explained by lack of reasoning than by motivated reasoning. *Cognition*, 188, 39–50.
- Pennycook, G., & Rand, D. G. (2021). The psychology of fake news. *Trends in Cognitive Sciences*, 25(5), 388–402.
- Bago, B., Rand, D. G., & Pennycook, G. (2020). Fake news, fast and slow: Deliberation reduces belief in false (but not true) news headlines. *Journal of Experimental Psychology: General*, 149(8), 1608.
- Roozenbeek, J., et al. (2022). Psychological inoculation improves resilience against misinformation on social media. *Science Advances*, 8(34).

### AI-Generated Content Detection
- Jakesch, M., et al. (2023). Human heuristics for AI-generated language are flawed. *PNAS*, 120(11).
- Clark, E., et al. (2021). All that's 'human' is not gold: Evaluating human evaluation of generated text. *ACL 2021*.
- Zhou, X., & Zafarani, R. (2020). A survey of fake news: Fundamental theories, detection methods, and opportunities. *ACM Computing Surveys*, 53(5), 1–40.
- Vaccari, C., & Chadwick, A. (2020). Deepfakes and disinformation: Exploring the impact of synthetic political video on deception, uncertainty, and trust. *Social Media + Society*, 6(1).

### Eye-Tracking and Reading / Credibility
- Rayner, K. (1998). Eye movements in reading and information processing: 20 years of research. *Psychological Bulletin*, 124(3), 372.
- Rayner, K. (2009). The 35th Sir Frederick Bartlett Lecture: Eye movements and attention in reading, scene perception, and visual search. *Quarterly Journal of Experimental Psychology*, 62(8), 1457–1506.
- Krause, N. M., et al. (2020). Fake news: A new obsession with an old phenomenon? — Eye-tracking study. *Computers in Human Behavior*, 112.
- Salovich, N. A., et al. (2021). Can confidence help account for and redress the effects of reading inaccurate information? *Memory & Cognition*, 49, 293–310.

### Individual Differences — Thinking Dispositions
- Toplak, M. E., West, R. F., & Stanovich, K. E. (2014). Assessing miserly information processing: An expansion of the Cognitive Reflection Test. *Thinking & Reasoning*, 20(2), 147–168.
- Baron, J. (2019). Actively open-minded thinking in politics. *Cognition*, 188, 18–24.
- Cacioppo, J. T., Petty, R. E., & Kao, C. F. (1984). The efficient assessment of need for cognition. *Journal of Personality Assessment*, 48(3), 306–307.

---

## 8. Next Steps

### Immediate Actions (within 2 weeks)
- [ ] Schedule meeting with potential supervisor to discuss feasibility and lab access
- [ ] Begin systematic literature review (focus on 2022–2026 publications on AI-content detection)
- [ ] Identify available eye-tracking equipment and book familiarisation session
- [ ] Draft initial ethics application based on institutional requirements

### Short-term (within 1–2 months)
- [ ] Finalise research questions and hypotheses based on supervisor feedback
- [ ] Begin stimulus generation pilot (test prompting strategies across LLMs)
- [ ] Select and prepare individual difference measures (obtain permissions, translate if needed)
- [ ] Complete power analysis with finalised design parameters
- [ ] Write pre-registration document

### Medium-term (within 3–4 months)
- [ ] Submit ethics application
- [ ] Complete stimulus set (generation, matching, independent rating)
- [ ] Program experiment (PsychoPy/Experiment Builder + eye-tracker integration)
- [ ] Conduct pilot study (N = 10–15)
- [ ] Refine stimuli and procedure based on pilot data
- [ ] Submit pre-registration (OSF)

---

*Document created: March 2026 | Last updated: March 2026*
