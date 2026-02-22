# AI in Drug Discovery & Development

## Overview

AI is reshaping pharmaceutical R&D by accelerating every stage of the drug discovery pipeline — from target identification to clinical trials. Traditional drug development takes 10-15 years and costs $2.6B on average. AI promises to cut timelines by 30-50% and costs by up to 60%.

**Market Size:** AI in drug discovery — $2.5B (2024) → projected $11.2B by 2030 (CAGR 28%)

---

## Drug Discovery Pipeline & AI Applications

### Traditional vs AI-Accelerated Pipeline

```
Stage              Traditional    AI-Accelerated    AI Impact
──────────────────────────────────────────────────────────────
Target ID          3-5 years      1-2 years         Knowledge graphs, multi-omics
Hit Discovery      2-3 years      3-6 months        Virtual screening, generative models
Lead Optimization  2-3 years      6-12 months       Molecular optimization, ADMET prediction
Preclinical        1-2 years      6-12 months       Toxicity prediction, animal model reduction
Clinical Trials    6-10 years     3-5 years         Patient selection, trial design, biomarkers
Regulatory         1-2 years      6-12 months       Automated documentation, real-world evidence
──────────────────────────────────────────────────────────────
Total              12-17 years    5-8 years
Cost               $2.6B          ~$1B (estimated)
```

---

## Key Applications

### 1. Target Identification & Validation

| Application | Description | Key Players |
|------------|-------------|-------------|
| Knowledge graph mining | Identify novel drug targets from literature/omics | BenevolentAI, Causaly, Healx |
| Multi-omics integration | Combine genomics, proteomics, metabolomics | Recursion, Insitro, Valo Health |
| Protein structure prediction | Predict 3D protein structure for target druggability | DeepMind (AlphaFold), Meta (ESMFold) |
| Genetic target discovery | CRISPR + AI screen for targets | Recursion, Cellarity |
| Disease mechanism mapping | AI models of disease pathways | BenevolentAI, Exscientia |

### 2. Molecule Generation & Design

| Application | Description | Key Players |
|------------|-------------|-------------|
| De novo molecule design | Generate novel drug-like molecules | Insilico Medicine, Exscientia, Generate Biomedicines |
| Molecular optimization | Optimize lead compounds for potency/selectivity | Schrödinger, Relay Therapeutics |
| Protein design | Design novel therapeutic proteins | Generate Biomedicines, Absci, David Baker lab |
| Antibody design | AI-designed therapeutic antibodies | Absci, BigHat Biosciences, Nabla Bio |
| PROTAC design | Design protein degraders | Arvinas + AI partners |

### 3. Virtual Screening

| Application | Description | Key Players |
|------------|-------------|-------------|
| Structure-based screening | Dock molecules against protein targets | Schrödinger, OpenEye (Cadence) |
| Ligand-based screening | Find similar molecules to known actives | Atomwise, Chemify |
| Ultra-large library screening | Screen billions of virtual molecules | Enamine REAL + AI, Recursion |
| Fragment-based design | AI-guided fragment growing/linking | Exscientia, Astex (Otsuka) |

### 4. ADMET Prediction

| Property | AI Predicts | Accuracy |
|----------|------------|----------|
| Absorption | Oral bioavailability, permeability | 75-85% |
| Distribution | Protein binding, tissue distribution | 70-80% |
| Metabolism | CYP450 interactions, metabolic stability | 80-90% |
| Excretion | Clearance, half-life | 70-80% |
| Toxicity | hERG, hepatotoxicity, mutagenicity | 80-90% |

### 5. Clinical Trial Optimization

| Application | Description | Key Players |
|------------|-------------|-------------|
| Patient recruitment | AI-matched trial enrollment | Deep 6 AI, TriNetX, Unlearn.AI |
| Trial design | Synthetic control arms, adaptive designs | Unlearn.AI, Medidata (Dassault) |
| Endpoint prediction | Predict trial success probability | Insilico Medicine, Owkin |
| Biomarker discovery | Identify predictive/prognostic biomarkers | Tempus, Foundation Medicine |
| Real-world evidence | Generate evidence from real-world data | Flatiron (Roche), Aetion, Veradigm |

---

## Top Companies

### AI-First Drug Discovery
| Company | Founded | Funding | Pipeline Stage | Key Focus |
|---------|---------|---------|---------------|-----------|
| Recursion | 2013 | $800M+ (IPO) | Phase II | Phenomics, rare disease |
| Insilico Medicine | 2014 | $400M+ | Phase II | Generative chemistry, IPF |
| Exscientia | 2012 | $500M+ (IPO) | Phase I/II | Precision medicine, oncology |
| Insitro | 2018 | $700M+ | Preclinical | ML + biology, metabolic disease |
| Generate Biomedicines | 2019 | $400M+ | Preclinical | Generative protein design |
| Absci | 2011 | $300M+ (IPO) | Preclinical | AI antibody design |
| BenevolentAI | 2013 | $400M+ (IPO) | Phase II | Knowledge graph, inflammation |
| Relay Therapeutics | 2016 | $700M+ (IPO) | Phase II | Motion-based drug design |
| Schrödinger | 1990 | $300M+ (IPO) | Platform | Physics-based + ML |
| Isomorphic Labs | 2021 | DeepMind spin-off | Preclinical | AlphaFold for drug design |

### Big Pharma AI Investments
| Pharma Company | AI Strategy | Key Partners |
|---------------|-------------|-------------|
| Roche/Genentech | In-house AI + partnerships | Recursion, Flatiron, Foundation Medicine |
| Novartis | Microsoft partnership, in-house AI | Microsoft, Isomorphic Labs |
| Pfizer | AI-powered clinical development | Various AI partners |
| AstraZeneca | AI across R&D pipeline | BenevolentAI, Absci |
| Merck | AI drug discovery platform | Atomwise, Iktos |
| Sanofi | AI factory with multiple partners | Exscientia, Insilico, Owkin |
| GSK | In-house AI unit | Various academic partners |
| Amgen | denovo protein design | Generate Biomedicines |
| Eli Lilly | AI clinical trials | Various |
| Bristol-Myers Squibb | AI target discovery | Various |

---

## Breakthrough Models & Tools

### Foundation Models for Drug Discovery
| Model | Developer | Capability |
|-------|-----------|-----------|
| AlphaFold 2/3 | DeepMind | Protein structure prediction (Nobel Prize 2024) |
| ESMFold / ESM-2 | Meta FAIR | Protein language model |
| RFdiffusion | David Baker lab | Protein design via diffusion |
| MolBERT / ChemBERTa | Various | Molecular property prediction |
| DiffDock | MIT | Molecular docking with diffusion |
| REINVENT | AstraZeneca | Generative molecular design |
| Uni-Mol | Various | Universal molecular representation |
| DrugGPT | Various | Generative drug design |

### Open-Source Tools
| Tool | Purpose | Developer |
|------|---------|-----------|
| RDKit | Cheminformatics toolkit | Open source |
| DeepChem | Deep learning for chemistry | Open source |
| OpenMM | Molecular dynamics simulation | Stanford |
| AutoDock Vina | Molecular docking | Scripps |
| REINVENT | Generative molecular design | AstraZeneca (open-sourced) |
| TorchDrug | ML for drug discovery | Mila |
| PyMOL | Molecular visualization | Schrödinger (open source) |
| Open Babel | Chemical format conversion | Open source |

---

## AI Drug Candidates in Clinical Trials

### Molecules Discovered/Designed by AI (Selected)
| Molecule | Company | Indication | Stage | Year AI-Designed |
|----------|---------|-----------|-------|-----------------|
| INS018_055 | Insilico Medicine | Idiopathic pulmonary fibrosis | Phase II | 2021 |
| DSP-1181 | Exscientia/Sumitomo | OCD | Phase I (completed) | 2019 |
| EXS4318 | Exscientia | Inflammation | Phase I | 2022 |
| REC-994 | Recursion | Cerebral cavernous malformation | Phase II | 2020 |
| BEN-2293 | BenevolentAI | Atopic dermatitis | Phase II | 2021 |
| ISM001-055 | Insilico Medicine | COVID-19 | Phase I | 2020 |

---

## Research Papers (Must-Read)

### Foundational
1. **"AlphaFold 2: Protein structure prediction at atomic accuracy"** — Jumper et al. (2021) — Nature
2. **"Highly accurate protein structure prediction with AlphaFold"** — DeepMind — Nature
3. **"A Deep Learning Approach to Antibiotic Discovery"** — Stokes et al. (2020) — Cell (Halicin discovery)
4. **"De novo design of protein structure and function with RFdiffusion"** — Watson et al. (2023) — Nature
5. **"Autonomous scientific research by AI"** — Coscientist paper (2023) — Nature

### Recent (2024-2025)
1. **"AlphaFold 3: Accurate structure prediction of biomolecular complexes"** — DeepMind (2024)
2. **"Generative AI for molecular design"** — Multiple review papers (2024)
3. **"AI-designed antibodies enter clinical trials"** — Absci, BigHat publications (2024)
4. **"Foundation models for drug discovery"** — Review papers (2024)
5. **"Clinical outcomes of AI-discovered drugs"** — Insilico, Exscientia updates (2024-2025)

---

## Challenges

1. **Data quality** — Biological assay data is noisy and inconsistent
2. **Generalization** — Models trained on known chemistry struggle with novel scaffolds
3. **Validation cost** — Wet lab validation remains expensive and slow
4. **Regulatory uncertainty** — FDA pathways for AI-discovered drugs still evolving
5. **Explainability** — Hard to explain why AI selected a particular molecule
6. **Biology complexity** — In vivo behavior hard to predict from in silico
7. **IP questions** — Can you patent an AI-designed molecule?
8. **Clinical translation** — <10% of Phase I candidates reach market

---

## Future Directions

1. **Self-driving labs** — Fully automated hypothesis-experiment-analysis loops
2. **Foundation models for biology** — Universal biological foundation models
3. **Closed-loop drug design** — AI designs → robot synthesizes → AI tests → AI iterates
4. **Polypharmacology AI** — Design drugs that hit multiple targets simultaneously
5. **AI for rare diseases** — Make rare disease drug development economically viable
6. **Digital biology** — Complete in-silico modeling of human physiology
7. **Personalized drug design** — Patient-specific drug candidates
8. **RNA therapeutics AI** — AI-designed mRNA, siRNA, ASO drugs

---

*Sources: Nature Reviews Drug Discovery, Drug Discovery Today, PharmaProjects, company pipelines*
*Updated: February 2025*
