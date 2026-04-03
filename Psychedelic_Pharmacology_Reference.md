# Comprehensive Psychedelic Pharmacology Reference
## For Time-Based Neurological Simulation Development

**Compiled: 2026-04-03**
**Sources: PubMed/PMC clinical studies, PsychonautWiki, Erowid, MAPS, Imperial College London, Johns Hopkins, DrugBank, NIMH-PDSP Database**

---

## TABLE OF CONTENTS

1. [LSD (Lysergic Acid Diethylamide)](#1-lsd)
2. [Psilocybin / Psilocin](#2-psilocybin)
3. [DMT (N,N-Dimethyltryptamine)](#3-dmt)
4. [Mescaline](#4-mescaline)
5. [MDMA (3,4-Methylenedioxymethamphetamine)](#5-mdma)
6. [Ketamine](#6-ketamine)
7. [Ayahuasca (DMT + MAOIs)](#7-ayahuasca)
8. [5-MeO-DMT](#8-5-meo-dmt)
9. [Comparative Receptor Binding Table](#9-comparative-receptor-binding)
10. [Comparative Temporal Dynamics](#10-comparative-temporal-dynamics)
11. [Brain Effects Model: Universal Psychedelic Sequence](#11-brain-effects-model)

---

## 1. LSD (Lysergic Acid Diethylamide) {#1-lsd}

### 1.1 Pharmacokinetics

| Parameter | Value | Source |
|-----------|-------|--------|
| **Primary ROA** | Oral (sublingual absorption) | Clinical standard |
| **Bioavailability (oral)** | 71-80% | Holze et al. 2024; Dolder et al. 2017 |
| **Onset** | 30-60 min | PsychonautWiki |
| **Tmax (peak plasma)** | 1.4 h (100 ug), 1.5 h (200 ug) | Dolder et al. 2017 |
| **Peak effect duration** | 2-4 h | Dolder et al. 2017 |
| **Total duration** | 8-12 h (dose-dependent) | 8.2 +/- 2.1 h (100 ug), 11.6 +/- 1.7 h (200 ug) |
| **Half-life (initial)** | 2.6 h (range 2.2-3.4 h) | Dolder et al. 2017 |
| **Half-life (terminal)** | 8.9 +/- 5.9 h | Holze et al. 2024 |
| **Cmax (100 ug)** | 1.3 ng/mL (range 1.2-1.9) | Dolder et al. 2017 |
| **Cmax (200 ug)** | 3.1 ng/mL (range 2.6-4.0) | Dolder et al. 2017 |
| **Protein binding** | ~80% | Literature consensus |
| **Volume of distribution** | ~0.5 L/kg | Estimated from PK data |
| **Metabolic pathway** | Hepatic: CYP3A4 (major), CYP2D6 (minor) | Pharmacology reviews |
| **Active metabolites** | O-H-LSD (2-oxo-3-hydroxy-LSD) - primary inactive metabolite; nor-LSD - minor | Holze et al. 2024 |
| **Urinary excretion** | 1% as LSD, 13% as O-H-LSD in 24 h | Holze et al. 2024 |

### 1.2 Dosing (Sublingual/Oral, in micrograms)

| Level | Dose (ug) |
|-------|-----------|
| **Microdose** | 5-20 ug |
| **Threshold** | 15 ug |
| **Light** | 15-75 ug |
| **Common** | 75-150 ug |
| **Strong** | 150-300 ug |
| **Heavy** | 300+ ug |
| **LD50 (mouse, IV)** | 50-60 mg/kg (~46,000 ug/kg) |
| **LD50 (rat, IV)** | 16.5 mg/kg |
| **LD50 (rabbit, IV)** | 0.3 mg/kg |
| **Estimated human lethal** | No confirmed human lethal dose; therapeutic index >1000x |

### 1.3 Receptor Pharmacology

| Receptor | Ki (nM) | Action | Notes |
|----------|---------|--------|-------|
| **5-HT2A** | 3-7 nM (EC50 ~7.2 nM) | Partial agonist | Primary psychedelic target |
| **5-HT2C** | ~10-20 nM | Partial agonist | Contributes to visual effects |
| **5-HT2B** | ~10 nM | Agonist | Cardiac risk at chronic use |
| **5-HT1A** | ~2-5 nM | Partial agonist | Anxiolytic component |
| **5-HT1B** | ~4 nM | Agonist | |
| **5-HT5A** | ~5 nM | Agonist | |
| **5-HT6** | ~2 nM | Antagonist | |
| **5-HT7** | ~2 nM | Agonist | |
| **D1** | ~25 nM (K0.5) | Partial agonist | |
| **D2** | ~2 nM (D2High) | Partial agonist | Surprisingly high affinity |
| **D3** | ~5-10 nM | Partial agonist | |
| **Alpha-1 adrenergic** | ~10-30 nM | Agonist | Sympathomimetic effects |
| **Alpha-2 adrenergic** | ~30-80 nM | Agonist | |
| **TAAR1** | functional | Agonist | Modulates DA firing |

### 1.4 Temporal Brain Effects

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-30 min** | Absorption; initial anxiogenic arousal; sympathetic activation |
| **30-60 min** | Thalamic filter disruption begins; increased thalamocortical connectivity; initial DMN perturbation |
| **60-120 min** | Peak 5-HT2A activation; DMN integrity decreases; increased entropy across cortex; visual cortex disinhibition; claustrum connectivity disruption |
| **2-4 h (Peak)** | Maximum DMN disintegration; ego dissolution; global functional connectivity increase; cross-modal sensory integration (synesthesia); PCC and mPFC maximally suppressed |
| **4-8 h (Plateau)** | Gradual DMN reconstitution; sustained visual cortex activation; emotional processing shifts; amygdala reactivity changes |
| **8-12 h (Comedown)** | DMN reconnectivity; thalamic gating restoration; residual visual effects; emotional openness |
| **12-72 h (Afterglow)** | Increased episodic memory; increased verbal fluency; decreased cognitive flexibility; enhanced neuroplasticity gene expression |
| **1-4 weeks (Post-acute)** | Sustained increases in openness personality trait; enhanced cognitive flexibility; neuroplasticity-related gene upregulation persists |

---

## 2. Psilocybin / Psilocin {#2-psilocybin}

### 2.1 Pharmacokinetics

| Parameter | Value | Source |
|-----------|-------|--------|
| **Primary ROA** | Oral | Standard |
| **Prodrug conversion** | Psilocybin -> Psilocin (dephosphorylation by alkaline phosphatase) | Rapid first-pass |
| **Bioavailability (psilocin)** | 52.7 +/- 20% | Systematic review 2025 |
| **Onset** | 20-45 min | PsychonautWiki |
| **Tmax (psilocin)** | 1.8-4 h (variable) | Multiple clinical studies |
| **Peak effect** | 60-90 min post-onset | Griffiths et al. |
| **Total duration** | 4-6 h (dose-dependent) | Clinical studies |
| **Half-life (psilocin)** | 1.5-2.0 h (range 1.4-4 h) | Systematic review |
| **Cmax (25 mg psilocybin)** | ~15-20 ng/mL psilocin | Brown et al. 2017 |
| **Volume of distribution** | 277-1016 L | Highly variable, extensive tissue distribution |
| **Metabolic pathway** | Alkaline phosphatase (prodrug activation); then MAO-A, CYP2D6, CYP3A4 | |
| **Active metabolites** | Psilocin (active); 4-hydroxyindole-3-acetic acid (inactive); 4-hydroxytryptophol (inactive) | |
| **Urinary excretion** | Psilocin-O-glucuronide is major urinary metabolite | |

### 2.2 Dosing (Oral, Dried Psilocybe cubensis mushrooms / Pure Psilocybin)

| Level | Dried Mushrooms | Pure Psilocybin |
|-------|----------------|-----------------|
| **Microdose** | 0.1-0.5 g | 1-3 mg |
| **Threshold** | 0.25 g | 3-5 mg |
| **Light** | 0.5-1.5 g | 5-10 mg |
| **Common** | 1.5-3.5 g | 10-25 mg |
| **Strong** | 3.5-5 g | 25-40 mg |
| **Heavy ("heroic")** | 5+ g | 40-50+ mg |
| **LD50 (mouse, IV)** | - | 285 mg/kg |
| **LD50 (rat, oral)** | - | 280 mg/kg |
| **LD50 (rabbit, IV)** | - | 12.5 mg/kg |

*Note: Psilocybin content in P. cubensis averages ~0.6-0.8% dry weight; variation is significant.*

### 2.3 Receptor Pharmacology (Psilocin - Active Metabolite)

| Receptor | Ki (nM) | Action | Notes |
|----------|---------|--------|-------|
| **5-HT2A** | 120-173 nM | Partial agonist | Primary psychedelic target |
| **5-HT2C** | 79-311 nM | Partial agonist | Appetite suppression, anxiogenic |
| **5-HT2B** | ~100 nM | Agonist | |
| **5-HT1A** | 146-152 nM | Agonist | Anxiolytic, modulatory |
| **5-HT1D** | ~300 nM | Agonist | |
| **5-HT5** | ~84 nM | Agonist | |
| **5-HT6** | ~57 nM | Agonist | |
| **5-HT7** | ~39 nM | Agonist | |
| **D1** | >10,000 nM | Negligible | Minimal dopamine involvement |
| **D3** | ~6,300 nM | Weak agonist | |
| **Sigma-1** | >10,000 nM | Negligible | |

### 2.4 Temporal Brain Effects

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-20 min** | Gastrointestinal absorption; dephosphorylation to psilocin; early autonomic arousal |
| **20-45 min (Onset)** | Thalamic connectivity begins to shift; initial mPFC/ACC BOLD signal decrease; early perceptual changes |
| **45-90 min (Come-up)** | Rapid DMN disintegration; claustrum connectivity disruption; increased thalamocortical information flow; visual cortex V1/V2 disinhibition |
| **90-180 min (Peak)** | Maximum DMN hypoconnectivity; PCC and mPFC maximally suppressed; global entropy increase; cross-network connectivity increase; ego dissolution correlates with PCC disconnection |
| **3-4 h (Descent)** | Gradual DMN reconstitution; thalamic gating restoration begins; emotional processing enhanced; amygdala reactivity reduction |
| **4-6 h (Resolution)** | Near-baseline DMN; residual emotional openness; mild perceptual effects |
| **6-24 h (Afterglow)** | Enhanced neuroplasticity markers; increased cognitive flexibility; prosocial effects |
| **1-4 weeks (Post-acute)** | 5-HT2A receptor downregulation (transient); increased synaptic density; sustained mood improvements |

---

## 3. DMT (N,N-Dimethyltryptamine) {#3-dmt}

### 3.1 Pharmacokinetics

| Parameter | Smoked/Vaporized | IV Injection | IM Injection |
|-----------|-----------------|--------------|--------------|
| **Bioavailability** | ~20-40% (variable) | 100% | ~90% |
| **Onset** | 20-40 seconds | 15-30 seconds | 2-5 min |
| **Tmax** | 2-3 min | ~2 min | ~10-15 min |
| **Peak effect** | 2-8 min | 3-5 min | 10-20 min |
| **Total duration** | 5-20 min | 15-30 min | 30-60 min |
| **Half-life (initial)** | 5-6 min | 5-6 min | ~10 min |
| **Half-life (terminal)** | ~15 min | ~15 min | ~20 min |
| **Cmax (0.4 mg/kg IV)** | - | 32-204 ug/L | - |
| **Cmax (0.7 mg/kg IM)** | - | - | 14-154 ug/L |

**Metabolism:**
- Primary enzyme: **MAO-A** (widespread tissue expression - lung, gut, liver, brain)
- Secondary: CYP2D6, CYP2C19 (hepatic, minor role for IV/smoked routes)
- Primary metabolite: 3-indoleacetic acid (IAA) - inactive
- Minor metabolites: DMT-N-oxide, N-methyltryptamine (NMT)
- Key fact: IV-administered DMT is largely cleared **before reaching the liver** by MAO-A in lungs and other tissues

### 3.2 Dosing

**Smoked/Vaporized (mg):**

| Level | Dose |
|-------|------|
| **Threshold** | 2 mg |
| **Light** | 10-20 mg |
| **Common** | 20-40 mg |
| **Strong** | 40-60 mg |
| **Heavy** | 60+ mg |

**IV Injection (mg/kg):**

| Level | Dose |
|-------|------|
| **Threshold** | 0.05 mg/kg |
| **Common** | 0.2-0.3 mg/kg |
| **Strong (breakthrough)** | 0.4 mg/kg |

**LD50:** ~47 mg/kg (mouse, IP); no confirmed human lethal dose from DMT alone.

### 3.3 Receptor Pharmacology

| Receptor | Ki / EC50 (nM) | Action | Notes |
|----------|----------------|--------|-------|
| **5-HT2A** | EC50 = 38.3 nM; Ki ~127 nM | Agonist | Primary psychedelic target |
| **5-HT2C** | Ki ~334 nM | Agonist | |
| **5-HT2B** | Ki ~12 nM | Agonist | Highest affinity target |
| **5-HT1A** | EC50 >10,000 nM; Ki ~5,500 nM | Weak agonist | Minimal role |
| **5-HT7** | Ki ~10 nM | Agonist | |
| **D1** | Ki ~31 nM | Agonist | Notable affinity |
| **Sigma-1** | Ki ~14,750 nM | Agonist | Proposed role in "breakthrough" |
| **TAAR1** | Functional agonist | Agonist | Trace amine receptor |

### 3.4 Temporal Brain Effects (Smoked/IV)

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-30 sec** | Rapid onset; thalamic gating collapse; immediate EEG alpha power decrease |
| **30 sec - 2 min** | Peak 5-HT2A cortical activation; massive DMN disruption; visual cortex hyperstimulation; broadband cortical desynchronization |
| **2-5 min (Peak)** | Complete ego dissolution; immersive visual phenomena; maximal brain entropy; loss of external sensory processing; "breakthrough" state at high doses |
| **5-10 min** | Rapid DMN reconstitution; decreasing visual intensity; re-engagement with external stimuli |
| **10-20 min** | Near-baseline; residual emotional/perceptual after-effects |
| **20-60 min (Afterglow)** | Enhanced emotional sensitivity; mild afterglow; rapid return to normal function |

---

## 4. Mescaline (3,4,5-Trimethoxyphenethylamine) {#4-mescaline}

### 4.1 Pharmacokinetics

| Parameter | Value | Source |
|-----------|-------|--------|
| **Primary ROA** | Oral | Standard |
| **Bioavailability** | >53% (based on urinary recovery of unchanged drug) | Holze et al. 2025 |
| **Onset** | 30-54 min (0.5-0.9 h) | Clinical data |
| **Tmax** | 2.0 h (geometric mean) | Holze et al. 2025 |
| **Peak effect** | 2-4 h | |
| **Total duration** | 8-14 h (dose-dependent; 6 h at low, 14 h at high) | |
| **Half-life** | 3.5 h (across all doses) | Holze et al. 2025 |
| **Metabolic pathway** | Oxidative deamination (MAO and/or DAO - debated); NOT CYP2D6 | |
| **Primary metabolite** | 3,4,5-trimethoxyphenylacetic acid (TMPA) - inactive | |
| **Other metabolites** | 3,4,5-trimethoxyphenylethanol (inactive) | |
| **Urinary excretion** | 53% unchanged, 31% as TMPA in 24-30 h | |

### 4.2 Dosing (Oral, Mescaline HCl/Sulfate in mg)

| Level | Dose (mg) |
|-------|-----------|
| **Microdose** | 10-50 mg |
| **Threshold** | 50 mg |
| **Light** | 50-200 mg |
| **Common** | 200-400 mg |
| **Strong** | 400-800 mg |
| **Heavy** | 800+ mg |
| **Dose equivalence** | 500 mg mescaline ~ 100 ug LSD ~ 20 mg psilocybin |
| **LD50 (rat, oral)** | 370 mg/kg |

*Note: Peyote cactus contains ~1-6% mescaline by dry weight. San Pedro: ~0.3-2%.*

### 4.3 Receptor Pharmacology

| Receptor | Ki / EC50 (nM) | Action | Notes |
|----------|----------------|--------|-------|
| **5-HT2A** | EC50 ~10,000 nM (~10 uM) | Partial agonist | Low potency, hence high dosing |
| **5-HT2C** | ~10,000+ nM | Partial agonist | Very weak |
| **5-HT2B** | Ki ~107 nM | Agonist | Moderate |
| **5-HT1A** | Ki ~7,300 nM | Weak agonist | 5-HT1A > 5-HT2A (ratio 0.73) |
| **Alpha-2C adrenergic** | Ki ~100 nM | Agonist | Notable non-serotonergic target |
| **D1** | Negligible | - | |
| **D2** | Negligible | - | |

*Note: Mescaline is the weakest-potency classic psychedelic, requiring 200-500x the dose of LSD for equivalent effects.*

### 4.4 Temporal Brain Effects

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-45 min** | GI absorption; initial nausea (common); early sympathetic activation |
| **45-90 min (Come-up)** | Gradual perceptual shifts; thalamic gating perturbation begins; slow onset compared to tryptamines |
| **90 min - 2 h** | DMN connectivity decrease; visual cortex activation; initial color/pattern enhancement |
| **2-4 h (Peak)** | Maximum DMN disruption; full visual effects; entactogenic/emotional quality (unique to phenethylamines); sustained body awareness |
| **4-8 h (Plateau)** | Extended peak effects; emotional depth; sustained visual enhancement without the steep peak of tryptamines |
| **8-12 h (Comedown)** | Gradual normalization; thalamic gating restoration; emotional openness persists |
| **12-24 h (Afterglow)** | Enhanced mood; physical fatigue; mild perceptual sensitivity |

---

## 5. MDMA (3,4-Methylenedioxymethamphetamine) {#5-mdma}

### 5.1 Pharmacokinetics

| Parameter | Value | Source |
|-----------|-------|--------|
| **Primary ROA** | Oral | Standard |
| **Bioavailability** | ~80% (estimated) | Literature |
| **Onset** | 30-45 min | PsychonautWiki |
| **Come-up** | 15-30 min additional | |
| **Tmax** | 1.5-3.0 h | Clinical studies |
| **Peak effect** | 1.5-2.5 h | |
| **Total duration** | 3-6 h | |
| **Offset** | 1-1.5 h | |
| **Afterglow / Comedown** | 12-48 h (mood effects) | |
| **Half-life (R-MDMA)** | 5.8 +/- 2.2 h | Enantiomer-specific |
| **Half-life (S-MDMA)** | 3.6 +/- 0.9 h | Enantiomer-specific |
| **Half-life (racemic, clinical)** | 6-9 h (nonlinear, dose-dependent) | Higher at typical doses |
| **Metabolic pathway** | CYP2D6 (N-demethylation to MDA; O-demethylenation to DHMA); CYP1A2, CYP3A4 (minor) | |
| **CYP2D6 inhibition** | MDMA is a mechanism-based (irreversible) inhibitor of CYP2D6 | Self-inhibiting within 1 h |
| **Active metabolites** | MDA (3,4-methylenedioxyamphetamine); DHMA (3,4-dihydroxymethamphetamine) | |
| **Nonlinear PK** | Small dose increases -> disproportionate plasma concentration rises | CYP2D6 saturation |

### 5.2 Dosing (Oral, in mg)

| Level | Dose (mg) |
|-------|-----------|
| **Microdose** | 5-15 mg |
| **Threshold** | 20 mg |
| **Light** | 20-80 mg |
| **Common** | 80-120 mg |
| **Strong** | 120-150 mg |
| **Heavy** | 150+ mg |
| **MAPS clinical protocol** | 80-120 mg initial + optional 40-60 mg booster at 1.5-2 h | |
| **LD50 (rat, SC, male)** | 18 mg/kg |
| **LD50 (rat, SC, female)** | 42.5 mg/kg |
| **Human lethal range (estimated)** | >10-20 mg/kg (highly variable; deaths reported at 2-5 mg/kg with comorbidities) |

### 5.3 Receptor / Transporter Pharmacology

**MDMA is NOT primarily a receptor agonist -- it is a monoamine releaser and reuptake inhibitor.**

| Target | IC50 / Ki (nM) | Action | Notes |
|--------|----------------|--------|-------|
| **SERT (serotonin transporter)** | IC50 ~819-2,240 nM | Substrate releaser + reuptake inhibitor | Primary target; massive 5-HT release |
| **NET (norepinephrine transporter)** | IC50 ~375 nM | Substrate releaser | Higher affinity than SERT |
| **DAT (dopamine transporter)** | IC50 ~1,500-3,000 nM | Substrate releaser | Lowest affinity of the three |
| **5-HT2A** | Ki >5,000 nM | Negligible direct binding | Effects via released 5-HT |
| **5-HT2B** | Ki ~1,000-2,000 nM | Moderate agonist | Cardiac valve risk (chronic) |
| **5-HT1A** | Indirect agonism | Via released 5-HT | |
| **Alpha-2 adrenergic** | Ki ~2,300 nM | Agonist | |
| **D1/D2** | Very low direct binding | Via released DA | |
| **Oxytocin system** | Stimulates OXT release | Indirect | Central to therapeutic effects |
| **VMAT2** | Functional interaction | Reverses vesicular transport | Dumps vesicular 5-HT into cytoplasm |

**Selectivity ratio:** SERT/DAT ~3-5x; NET is intermediate. This serotonin-preferring profile distinguishes MDMA from amphetamine (DAT/NET-preferring).

### 5.4 Temporal Brain Effects

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-30 min** | Absorption; early sympathetic activation (HR, BP increase); initial CYP2D6 inhibition |
| **30-60 min (Come-up)** | Massive serotonin release begins; amygdala activity decreases; mPFC activation; initial euphoria and empathogenic effects |
| **60-90 min** | Peak serotonin/norepinephrine/dopamine release; amygdala maximally suppressed; prefrontal-amygdala connectivity reduced; oxytocin surge; enhanced emotional openness; reduced threat detection |
| **90-150 min (Peak)** | Maximum empathogenic effects; mPFC-hippocampus connectivity enhanced; amygdala-hippocampus connectivity increased (facilitating memory reconsolidation); BDNF expression upregulated in amygdala |
| **2.5-4 h (Offset)** | Monoamine depletion begins; gradual re-engagement of amygdala; falling oxytocin; DA/NE levels declining |
| **4-8 h (Acute comedown)** | Serotonin depletion; tryptophan hydroxylase potentially inhibited; fatigue; residual emotional openness |
| **1-3 days (Sub-acute)** | "Tuesday blues" / mid-week low; SERT downregulation; 20-40% reduction in SERT-immunoreactive fiber density (transient); low mood possible |
| **7-21 days (Recovery)** | SERT mRNA expression fluctuates (up at day 7, down at day 21); gradual normalization |
| **1-6 months** | Full SERT recovery in most brain regions; some areas (occipital cortex, hippocampus, amygdala) may show persistent changes with heavy use |

---

## 6. Ketamine {#6-ketamine}

### 6.1 Pharmacokinetics

| Parameter | IV | IM | Intranasal | Oral | Sublingual |
|-----------|----|----|-----------|------|-----------|
| **Bioavailability** | 100% | 93% | 45-50% | 17-25% | 25-50% |
| **Onset** | 15-30 sec | 3-5 min | 5-15 min | 10-30 min | 5-15 min |
| **Tmax** | 1 min | 5-15 min | 20-30 min | 30-60 min | 20-30 min |
| **Peak effect** | 1-5 min | 10-20 min | 15-30 min | 30-90 min | 15-30 min |
| **Total duration** | 15-45 min | 30-90 min | 45-90 min | 1-3 h | 45-90 min |

| Parameter | Value |
|-----------|-------|
| **Half-life** | 2-3 h |
| **Metabolic pathway** | CYP3A4 (major), CYP2B6 (major) -> norketamine; then CYP2A6, CYP2B6 -> hydroxynorketamine (HNK), dehydronorketamine (DHNK) |
| **Active metabolites** | Norketamine (1/3 to 1/5 potency of ketamine); hydroxynorketamine (HNK - proposed antidepressant action) |
| **Protein binding** | ~47% |
| **Volume of distribution** | 3-5 L/kg |
| **Enantiomers** | S-ketamine (esketamine): 2-4x more potent than R-ketamine at NMDA |

### 6.2 Dosing

**Insufflated (mg):**

| Level | Dose |
|-------|------|
| **Threshold** | 5-10 mg |
| **Light** | 15-30 mg |
| **Common** | 30-75 mg |
| **Strong** | 75-150 mg |
| **K-hole** | 100-200+ mg |

**Oral (mg):**

| Level | Dose |
|-------|------|
| **Threshold** | 50 mg |
| **Light** | 50-100 mg |
| **Common** | 100-300 mg |
| **Strong** | 300-450 mg |
| **Heavy** | 450+ mg |

**IM (mg/kg):**

| Level | Dose |
|-------|------|
| **Dissociative threshold** | 0.5-0.75 mg/kg |
| **Full dissociation** | 1-1.5 mg/kg |
| **Anesthetic induction** | 3-4 mg/kg |
| **Clinical range (therapeutic)** | 6.5-13 mg/kg |

**IV (mg/kg):**

| Level | Dose |
|-------|------|
| **Sub-anesthetic (antidepressant)** | 0.5 mg/kg over 40 min |
| **Dissociative** | 1-1.5 mg/kg |
| **Anesthetic induction** | 1-4.5 mg/kg |

**LD50:**
- Rat oral: 447 mg/kg
- Mouse oral: 617 mg/kg
- Rat IV: 59 mg/kg
- Rat IP: 148-224 mg/kg

### 6.3 Receptor Pharmacology

| Receptor | Ki (nM) | Action | Notes |
|----------|---------|--------|-------|
| **NMDA (GluN2)** | Ki ~500 nM (racemic); S-ket: 300-800 nM; R-ket: 1,700-5,000 nM | Uncompetitive antagonist (open-channel blocker) | PRIMARY mechanism |
| **D2** | Ki ~2,500-5,000 nM | Weak agonist | |
| **Sigma-1** | R-ketamine: moderate; S-ketamine: negligible | Agonist | Dissociative component |
| **Sigma-2** | Ki ~26,000 nM | Weak | |
| **Mu-opioid (MOR)** | Ki >10,000 nM (parent); metabolite HNK IC50 ~0.56 nM | Weak agonist (parent); potent (metabolite) | Opioid contribution debated |
| **Kappa-opioid (KOR)** | Ki ~85,200 nM (parent); HNK more potent | Very weak agonist | |
| **HCN1 channels** | Functional block | Antagonist | Contributes to anesthesia |
| **Nicotinic ACh** | Ki ~10,000-50,000 nM | Antagonist | |
| **5-HT3** | Ki ~15,000 nM | Antagonist | Anti-emetic action |
| **AMPA receptors** | Indirect potentiation via glutamate surge | Facilitator | Key to antidepressant effect |
| **mTOR pathway** | Downstream activation (hours) | Signaling cascade | Synaptogenesis |

### 6.4 Temporal Brain Effects

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-2 min (IV)** | NMDA blockade begins; GABAergic interneuron inhibition (disinhibition); glutamate surge in prefrontal cortex |
| **2-10 min** | Peak NMDA blockade; AMPA receptor activation from excess glutamate; thalamocortical disruption; dissociative state; frontal DMN connectivity decreases; parietal DMN connectivity increases |
| **10-30 min** | Sustained dissociation; salience network disruption; sensory gating collapse; DLPFC connectivity altered; thalamic functional reorganization |
| **30-60 min (Resolution)** | NMDA blockade waning; glutamate levels normalizing; dissociative effects decreasing; DMN begins reconstituting |
| **1-4 h (Acute post)** | Ketamine largely cleared; norketamine active; mTOR pathway activation begins; BDNF signaling; initial synaptic protein synthesis |
| **4-24 h** | Delayed glutamate changes; DMN connectivity continues to reorganize; synaptogenesis begins; antidepressant effects emerge |
| **1-7 days** | Sustained DMN reconfiguration; enhanced synaptic density in PFC; sustained antidepressant effects (peak at day 1-3); enhanced cognitive flexibility |
| **7-14 days** | Effects waning without redosing; synaptic changes beginning to reverse in some patients |

---

## 7. Ayahuasca (DMT + Beta-Carboline MAOIs) {#7-ayahuasca}

### 7.1 Pharmacokinetics

| Parameter | Value | Source |
|-----------|-------|--------|
| **Active components** | DMT (from Psychotria viridis) + harmine, harmaline, tetrahydroharmine (THH) (from Banisteriopsis caapi) | |
| **Mechanism** | Harmala alkaloids inhibit MAO-A, rendering DMT orally active | |
| **Harmine Ki for MAO-A** | ~1 nM | In vitro |
| **DMT onset** | 30-60 min | |
| **DMT Tmax** | 1.5-2.0 h | Riba et al. 2003 |
| **Harmine Tmax** | ~30 min | Earlier than DMT |
| **DMT Cmax** | 12-33 ng/mL (dose-dependent) | |
| **Harmine Cmax** | ~49-90 ng/mL | |
| **Peak subjective effects** | 1.5-2.0 h (coincides with DMT Tmax) | |
| **Total duration** | 4-6 h | |
| **DMT half-life (with MAOI)** | ~260 min (~4.3 h) vs 5-6 min without | Dramatically extended by MAO inhibition |
| **Harmine half-life** | ~116 min (~1.9 h) | |
| **Metabolic interaction** | Bidirectional: harmine reduces DMT metabolism; DMT alters harmine PK | Complex PK interaction |

### 7.2 Dosing

**Typical Ayahuasca Ceremony:**

| Component | Dose | Notes |
|-----------|------|-------|
| **DMT (in brew)** | 25-40 mg (avg ~27 mg) | Range: 8.8-42 mg per serving |
| **Harmine** | 50-200 mg | Typical: 100-150 mg in brew |
| **Harmaline** | 20-80 mg | Variable |
| **THH** | 30-100 mg | Less potent MAOI |
| **Total brew volume** | 50-200 mL per dose | Highly variable between traditions |

**Pharmahuasca (Pharmaceutical Protocol):**

| Component | Dose |
|-----------|------|
| **Harmaline** | 70-150 mg (oral, capsule) |
| **Harmine** | 50-100 mg |
| **DMT (taken 15-20 min after MAOI)** | 30-50 mg |

### 7.3 Receptor Pharmacology

Same as DMT (Section 3.3), with the addition of:

| Target | Ki (nM) | Action | Notes |
|--------|---------|--------|-------|
| **Harmine at MAO-A** | ~1 nM | Reversible inhibitor | Extremely potent |
| **Harmaline at MAO-A** | ~2-5 nM | Reversible inhibitor | |
| **THH at SERT** | Ki ~1,000 nM | Weak reuptake inhibitor | Extends serotonin effects |
| **THH at MAO-A** | Ki ~100 nM | Weak inhibitor | |
| **Harmine at 5-HT2A** | Ki ~300-400 nM | Agonist | May contribute to visionary quality |
| **Harmine at DYRK1A** | Ki ~80 nM | Inhibitor | Potential neurogenesis role |

### 7.4 Temporal Brain Effects

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-15 min** | Harmala alkaloids absorb first; MAO-A inhibition begins systemically |
| **15-30 min** | DMT begins absorbing (protected from MAO-A degradation); nausea onset common (5-HT3 peripheral activation); harmine peaks |
| **30-60 min** | DMT plasma levels rising; gradual perceptual onset; purging may occur; thalamic gating perturbation begins |
| **60-90 min** | Visionary phase begins; DMN disruption accelerating; visual cortex activation; emotional processing shifts |
| **90-120 min (Peak)** | DMT Cmax; maximum visionary intensity; DMN maximally disrupted; thalamocortical connectivity reorganized; deep emotional/autobiographical processing; increased amygdala-prefrontal connectivity |
| **2-3 h** | Sustained plateau; often second wave of effects; emotional processing continues; decreased gamma oscillations |
| **3-5 h (Resolution)** | DMT levels declining; gradual visual reduction; emotional integration phase; DMN reconstituting |
| **5-6 h** | Near-baseline; residual emotional effects; physical recovery |
| **6-48 h (Afterglow)** | Enhanced mood; increased cognitive flexibility; prosocial effects; potential for emotional volatility |
| **Days to weeks** | Reported increases in mindfulness, empathy; decreased anxiety/depression scores; enhanced convergent thinking up to 4 weeks |

---

## 8. 5-MeO-DMT (5-Methoxy-N,N-Dimethyltryptamine) {#8-5-meo-dmt}

### 8.1 Pharmacokinetics

| Parameter | Smoked/Vaporized | Insufflated | Sublingual |
|-----------|-----------------|-------------|-----------|
| **Bioavailability** | High (avoids first-pass) | Moderate | Low-moderate |
| **Onset** | 8 sec - 1 min | 3-5 min | 5-15 min |
| **Tmax** | 2-3 min | 5-10 min | ~15-20 min |
| **Peak effect** | 2-3 min | 5-15 min | 15-30 min |
| **Total duration** | 20-60 min | 30-60 min | 40-90 min |

| Parameter | Value |
|-----------|-------|
| **Half-life (sublingual)** | 28 min |
| **Oral bioavailability** | Not orally active without MAOI | MAO-A degrades it completely |
| **With MAOI (oral)** | Active at 10-25 mg (with 70-150 mg harmaline) | DANGEROUS combination |
| **Metabolic pathway** | MAO-A (primary - deamination/inactivation); CYP2D6 (O-demethylation to bufotenine - active) |
| **Active metabolite** | Bufotenine (5-HO-DMT) - via CYP2D6 | Psychoactive |
| **Inactive metabolite** | 5-HIAA (via MAO-A deamination) | |
| **CYP2D6 polymorphism impact** | CYP2D6.10: 40x lower efficiency for bufotenine production | Pharmacogenomic significance |

### 8.2 Dosing

**Smoked/Vaporized (mg):**

| Level | Dose |
|-------|------|
| **Threshold** | 1 mg |
| **Light** | 3-6 mg |
| **Common** | 6-12 mg |
| **Strong** | 12-20 mg |
| **Heavy** | 20+ mg |

**Insufflated (mg):**

| Level | Dose |
|-------|------|
| **Threshold** | 3-5 mg |
| **Light** | 5-10 mg |
| **Common** | 10-20 mg |
| **Strong** | 20-30 mg |

**IV (Shulgin):** 2-3 mg

**LD50:**
- Sheep: 1 mg/kg (extremely sensitive)
- Mouse: 48-278 mg/kg (route-dependent)
- Cat: 15 mg/kg

### 8.3 Receptor Pharmacology

| Receptor | Ki (nM) | Action | Notes |
|----------|---------|--------|-------|
| **5-HT1A** | 1.9-3.0 nM | Potent agonist | PRIMARY target (unlike classic psychedelics) |
| **5-HT2A** | EC50 = 1.8-3.87 nM (Ki much weaker) | Agonist | Secondary; 300-1000x weaker affinity than 5-HT1A |
| **5-HT2C** | Ki ~30-1,060 nM (variable) | Agonist | |
| **5-HT2B** | Ki ~200 nM | Agonist | |
| **5-HT7** | Ki ~20 nM | Agonist | |
| **D1** | Negligible | - | |
| **D2** | Negligible | - | |
| **Sigma-1** | Ki ~2,500 nM | Agonist | |
| **TAAR1** | Functional agonist | Agonist | |

**Critical distinction from other psychedelics:** 5-MeO-DMT is primarily a **5-HT1A agonist** with secondary 5-HT2A activity, whereas LSD, psilocin, and DMT are primarily 5-HT2A agonists. This produces a qualitatively different experience (non-visual, somatic, ego-dissolving without geometric patterns).

### 8.4 Temporal Brain Effects

| Time Post-Dose | Brain Changes |
|---------------|---------------|
| **0-30 sec** | Rapid absorption; immediate 5-HT1A activation throughout brainstem and cortex |
| **30 sec - 2 min** | Overwhelming somatic experience; cortical EEG suppression (different from DMT which shows desynchronization); brainstem serotonergic activation; potential "white-out" at high doses |
| **2-5 min (Peak)** | Maximal ego dissolution (often more complete than DMT); 5-HT1A-mediated cortical-thalamic suppression; minimal geometric visual content; somatic waves; autonomic instability possible |
| **5-15 min** | Rapid decline; re-engagement with external world; emotional release common |
| **15-40 min** | Residual effects; emotional processing; physical sensations |
| **40-90 min (Afterglow)** | Enhanced emotional sensitivity; sense of interconnection; rapid return to cognitive baseline |
| **Days to weeks** | Reported reductions in anxiety and depression; enhanced life satisfaction; potential for psychological difficulty if experience not integrated |

---

## 9. Comparative Receptor Binding Table {#9-comparative-receptor-binding}

### Ki / EC50 Values in nM (lower = higher affinity)

| Receptor | LSD | Psilocin | DMT | Mescaline | 5-MeO-DMT | MDMA | Ketamine |
|----------|-----|----------|-----|-----------|-----------|------|----------|
| **5-HT2A** | 3-7 | 120-173 | ~127 (EC50=38) | ~10,000 | ~1,000 (EC50=1.8) | >5,000 (indirect) | N/A |
| **5-HT2C** | 10-20 | 79-311 | ~334 | >10,000 | 30-1,060 | N/A | N/A |
| **5-HT2B** | ~10 | ~100 | ~12 | ~107 | ~200 | ~1,500 | N/A |
| **5-HT1A** | 2-5 | 146-152 | ~5,500 | ~7,300 | 1.9-3.0 | Indirect | N/A |
| **D1** | ~25 | >10,000 | ~31 | >10,000 | >10,000 | Indirect | N/A |
| **D2** | 2 (D2High) | >10,000 | N/A | >10,000 | >10,000 | Indirect | ~3,000 |
| **SERT** | N/A | N/A | N/A | N/A | N/A | IC50=819-2,240 | N/A |
| **NET** | N/A | N/A | N/A | N/A | N/A | IC50=375 | N/A |
| **DAT** | N/A | N/A | N/A | N/A | N/A | IC50=1,500-3,000 | N/A |
| **NMDA** | N/A | N/A | N/A | N/A | N/A | N/A | 300-5,000 |
| **Sigma-1** | N/A | N/A | ~14,750 | N/A | ~2,500 | N/A | Moderate (R-ket) |

---

## 10. Comparative Temporal Dynamics {#10-comparative-temporal-dynamics}

### Duration Summary (All values in minutes unless otherwise noted)

| Substance | Route | Onset | Tmax | Peak Duration | Total Duration | Afterglow |
|-----------|-------|-------|------|---------------|----------------|-----------|
| **LSD** | Oral | 30-60 | 90 | 120-240 | 480-720 | 12-72 h |
| **Psilocybin** | Oral | 20-45 | 60-120 | 60-120 | 240-360 | 6-24 h |
| **DMT** | Smoked | 0.3-0.7 | 2-3 | 5-8 | 5-20 | 20-60 |
| **DMT** | IV | 0.3-0.5 | 2 | 3-5 | 15-30 | 20-60 |
| **Mescaline** | Oral | 30-90 | 120 | 120-360 | 480-840 | 12-24 h |
| **MDMA** | Oral | 30-45 | 90-150 | 90-150 | 180-360 | 12-48 h |
| **Ketamine** | IV | 0.25-0.5 | 1 | 5-15 | 15-45 | 1-4 h |
| **Ketamine** | Insufflated | 5-15 | 20-30 | 15-30 | 45-90 | 1-4 h |
| **Ketamine** | Oral | 10-30 | 30-60 | 30-90 | 60-180 | 2-6 h |
| **Ayahuasca** | Oral | 30-60 | 90-120 | 60-120 | 240-360 | 6-48 h |
| **5-MeO-DMT** | Smoked | 0.1-1 | 2-3 | 5-10 | 20-60 | 40-90 |

### Half-Life Summary

| Substance | Primary Half-Life | Terminal Half-Life |
|-----------|------------------|-------------------|
| **LSD** | 2.6 h | 8.9 h |
| **Psilocin** | 1.5-2.0 h | ~3-4 h |
| **DMT** | 5-6 min (initial) | 15 min (terminal) |
| **Mescaline** | 3.5 h | - |
| **MDMA** | 3.6-5.8 h (enantiomer-dependent) | 6-9 h (nonlinear) |
| **Ketamine** | 2-3 h | - |
| **DMT (in ayahuasca)** | ~4.3 h (MAO inhibited) | - |
| **5-MeO-DMT** | 28 min (sublingual) | - |

---

## 11. Brain Effects Model: Universal Psychedelic Sequence {#11-brain-effects-model}

### 11.1 Serotonergic Psychedelics (LSD, Psilocybin, DMT, Mescaline, 5-MeO-DMT, Ayahuasca)

**Phase 1: Onset (receptor engagement)**
1. 5-HT2A receptors activated on layer V pyramidal neurons in prefrontal cortex
2. Increased glutamate release (asynchronous, desynchronized)
3. Thalamic gating begins to shift (increased thalamocortical connectivity)
4. Claustrum connectivity disrupted (proposed "switch" for conscious binding)
5. Alpha oscillation power decreases (EEG signature of onset)

**Phase 2: Ascent (network reorganization)**
1. Default Mode Network (DMN) integrity decreasing (PCC, mPFC, angular gyrus)
2. Salience Network perturbation
3. Visual cortex (V1, V2) becoming disinhibited via feedback from higher areas
4. Increased global functional connectivity entropy
5. Cross-modal integration increases (basis for synesthesia)
6. Amygdala reactivity shifting (decreased for fear stimuli)

**Phase 3: Peak (maximal disruption)**
1. DMN maximally disintegrated (PCC disconnection correlates with ego dissolution)
2. mPFC/ACC maximally suppressed (correlates with subjective intensity)
3. Thalamic filter fully open (sensory flood)
4. Maximum brain entropy (entropic brain hypothesis)
5. Between-network connectivity maximized (normally segregated networks interact)
6. Within-network connectivity minimized (network integrity lost)
7. Energy landscape flattened (easier transitions between brain states)

**Phase 4: Plateau/Descent (gradual reconstitution)**
1. DMN slowly reconstituting
2. Thalamic gating gradually restoring
3. Alpha oscillations returning
4. Emotional processing enhanced (therapeutic window)
5. Visual effects decreasing
6. Ego/self-referential processing returning

**Phase 5: Afterglow (neuroplastic window)**
1. DMN reconnected but potentially reconfigured
2. Neuroplasticity markers upregulated (synaptic protein synthesis)
3. Enhanced cognitive flexibility
4. Emotional openness persists
5. 5-HT2A receptor downregulation (partial, contributes to tolerance)

### 11.2 MDMA (Entactogen - distinct mechanism)

**Phase 1: Monoamine Release Cascade**
1. SERT reversal -> massive synaptic 5-HT increase
2. NET reversal -> norepinephrine release
3. DAT reversal -> moderate dopamine release
4. VMAT2 disruption -> vesicular dump
5. CYP2D6 self-inhibition (within 1 h)

**Phase 2: Peak Empathogenic State**
1. Amygdala suppressed (via 5-HT1A and oxytocin)
2. mPFC activated
3. Oxytocin release (via hypothalamus)
4. mPFC-amygdala connectivity reduced (reduced threat response)
5. Amygdala-hippocampus connectivity increased (memory reconsolidation)

**Phase 3: Depletion and Recovery**
1. 5-HT stores depleted
2. Tryptophan hydroxylase potentially oxidized
3. SERT internalization
4. Gradual normalization over 1-4 weeks

### 11.3 Ketamine (Dissociative - distinct mechanism)

**Phase 1: NMDA Blockade**
1. Open-channel NMDA receptor block (preferentially on GABAergic interneurons)
2. Disinhibition of pyramidal neurons
3. Glutamate surge in prefrontal cortex
4. AMPA receptor activation (from excess glutamate)

**Phase 2: Dissociative State**
1. Thalamocortical disruption (via different mechanism than psychedelics)
2. Frontal DMN connectivity decreased; parietal increased
3. Salience network disrupted
4. Sensory gating collapse (but qualitatively different from serotonergic psychedelics)

**Phase 3: Neuroplastic Cascade (hours to days)**
1. AMPA stimulation -> BDNF release
2. mTOR pathway activation (within hours)
3. Synaptic protein synthesis
4. Synaptogenesis (new dendritic spines in PFC)
5. Sustained DMN reconfiguration (correlates with antidepressant effect)
6. Effects peak day 1-3, wane by day 7-14

---

## APPENDIX A: Key Metabolic Enzymes Summary

| Enzyme | Substrates | Clinical Relevance |
|--------|-----------|-------------------|
| **MAO-A** | DMT, 5-MeO-DMT, psilocin (minor), mescaline (debated) | Ayahuasca MAOI interaction; 5-MeO-DMT + MAOI = DANGEROUS |
| **CYP2D6** | MDMA (major), 5-MeO-DMT (O-demethylation), psilocin (major), DMT (minor) | MDMA self-inhibits CYP2D6; pharmacogenomic polymorphisms affect 5-MeO-DMT metabolism |
| **CYP3A4** | LSD (major), psilocin (minor), ketamine (major) | Drug interactions with CYP3A4 inhibitors |
| **CYP2B6** | Ketamine (major) | |
| **CYP2C19** | DMT (minor) | |
| **Alkaline phosphatase** | Psilocybin -> psilocin | Prodrug activation |

## APPENDIX B: Dose Equivalence (Approximate)

Based on Holze et al. 2023 clinical cross-over study:

| Substance | Equivalent Dose | Notes |
|-----------|----------------|-------|
| **LSD** | 100 ug | Reference |
| **Psilocybin** | 20 mg | |
| **Mescaline** | 500 mg | |
| **DMT (smoked)** | 30-40 mg | Much shorter duration |
| **5-MeO-DMT (smoked)** | 10-15 mg | Qualitatively very different |

---

## SOURCES

### Primary Clinical Pharmacokinetics
- [Dolder et al. 2017 - LSD Pharmacokinetics and Pharmacodynamics](https://pmc.ncbi.nlm.nih.gov/articles/PMC5591798/)
- [Holze et al. 2024 - LSD Oral PK and Urinary Recovery](https://bpspubs.onlinelibrary.wiley.com/doi/10.1111/bcp.15887)
- [Dolder et al. 2016 - LSD Concentration-Effect Relationship](https://pmc.ncbi.nlm.nih.gov/articles/PMC4772267/)
- [Psilocybin Pharmacokinetics Systematic Review 2025](https://pmc.ncbi.nlm.nih.gov/articles/PMC12030428/)
- [Clinical Pharmacokinetics of Psilocin - Springer 2024](https://link.springer.com/article/10.1007/s40262-024-01454-4)
- [Psilocin In Vitro and In Vivo Metabolism - Frontiers 2024](https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2024.1391689/full)
- [DMT Pharmacokinetics in Humans - PMC 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC10122081/)
- [Mescaline PK, PD, and Urinary Recovery - Springer 2025](https://link.springer.com/article/10.1007/s40262-025-01544-x)
- [Mescaline Acute Dose-Dependent Effects - Nature 2024](https://www.nature.com/articles/s41398-024-03116-2)
- [MDMA Population PK Model - PMC 2025](https://pmc.ncbi.nlm.nih.gov/articles/PMC11812931/)
- [MDMA Nonlinear Pharmacokinetics - PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC2014905/)
- [Ketamine Pharmacology Update - PMC 2019](https://pmc.ncbi.nlm.nih.gov/articles/PMC6493357/)
- [Ketamine StatPearls](https://www.ncbi.nlm.nih.gov/books/NBK470357/)
- [5-MeO-DMT Clinical Pharmacology Review - PMC 2022](https://pmc.ncbi.nlm.nih.gov/articles/PMC9314805/)
- [5-MeO-DMT Metabolism and Pharmacokinetics - PMC 2011](https://pmc.ncbi.nlm.nih.gov/articles/PMC3028383/)

### Receptor Binding Data
- [Ray 2010 - Psychedelics and the Human Receptorome (NIMH-PDSP Data)](https://pmc.ncbi.nlm.nih.gov/articles/PMC2814854/)
- [MDMA and Human Monoamine Transporters](https://link.springer.com/article/10.1007/s00213-005-0174-5)
- [Ketamine NMDA Receptors and Beyond](https://pmc.ncbi.nlm.nih.gov/articles/PMC5148235/)
- [Mescaline Behavioral Pharmacology - Serotonin Receptors](https://www.biorxiv.org/content/10.1101/2024.08.28.610032v1.full)

### Brain Imaging and Temporal Dynamics
- [Carhart-Harris et al. 2012 - Neural Correlates of Psilocybin (fMRI)](https://pmc.ncbi.nlm.nih.gov/articles/PMC3277566/)
- [Default Mode Network Modulation by Psychedelics - Systematic Review](https://pmc.ncbi.nlm.nih.gov/articles/PMC10032309/)
- [Psilocybin Thalamic Functional Organization - PMC 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC10749714/)
- [Psilocybin Claustrum Connectivity](https://www.sciencedirect.com/science/article/pii/S1053811920304663)
- [Ketamine DMN Connectivity and Glutamate](https://www.nature.com/articles/s41398-023-02346-0)
- [MDMA Altered Brain Activity Post-Therapy](https://pmc.ncbi.nlm.nih.gov/articles/PMC9879604/)
- [Neuroplasticity and Psychedelics Review 2022](https://www.nature.com/articles/s41386-022-01389-z)

### Dosing References
- [PsychonautWiki - LSD](https://psychonautwiki.org/wiki/LSD)
- [PsychonautWiki - DMT](https://psychonautwiki.org/wiki/DMT)
- [PsychonautWiki - 5-MeO-DMT](https://psychonautwiki.org/wiki/5-MeO-DMT)
- [PsychonautWiki - MDMA](https://psychonautwiki.org/wiki/MDMA)
- [PsychonautWiki - Ketamine](https://psychonautwiki.org/wiki/Ketamine)
- [PsychonautWiki - Mescaline](https://psychonautwiki.org/wiki/Mescaline)
- [Erowid LD50 Database](https://www.erowid.org/psychoactives/health/psychoactives_ld50s.shtml)

### Toxicology
- [Hofmann vs. Paracelsus - Psychedelic Toxicology Review](https://pmc.ncbi.nlm.nih.gov/articles/PMC9963058/)
- [MDMA Sex Differences in Acute Toxicity](https://www.sciencedirect.com/science/article/abs/pii/S0041008X08000720)
- [Ketamine Toxicity - StatPearls](https://www.ncbi.nlm.nih.gov/books/NBK541087/)
- [5-MeO-DMT Nonlinear PK in Mice](https://pmc.ncbi.nlm.nih.gov/articles/PMC3127237/)

### Clinical Trial Protocols
- [Ayahuasca DMT/Harmine Factorial Dose-Escalation Study](https://www.sciencedirect.com/science/article/pii/S0753332225001027)
- [DMT IV Acute Effects RCT](https://www.nature.com/articles/s41398-023-02477-4)
- [Comparative Effects: Mescaline vs LSD vs Psilocybin](https://www.nature.com/articles/s41386-023-01607-2)
- [DMT Continuous Infusion Dose-Response Study](https://www.nature.com/articles/s41386-024-02041-8)
