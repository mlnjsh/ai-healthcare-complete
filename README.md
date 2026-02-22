# AI in Healthcare — The Complete Resource

> The most comprehensive open-source collection of AI in healthcare — covering medical imaging, robotic surgery, chemotherapy automation, EHR intelligence, AI agents, drug discovery, diagnostics, hospital operations, 200+ tools, 100+ research papers, and future automation opportunities.

[![Sections](https://img.shields.io/badge/Sections-13-blue)]()
[![Tools](https://img.shields.io/badge/Tools%20%26%20Companies-200+-green)]()
[![Papers](https://img.shields.io/badge/Research%20Papers-100+-orange)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Table of Contents

| # | Section | What It Covers | File |
|---|---------|---------------|------|
| 1 | [Medical Imaging AI](#1-medical-imaging-ai) | Radiology, pathology, ophthalmology, dermatology AI | [medical-imaging/](medical-imaging/) |
| 2 | [Surgery & Robotics](#2-surgery--robotics) | Robotic surgery, surgical AI, autonomous procedures | [surgery-robotics/](surgery-robotics/) |
| 3 | [Chemotherapy & Oncology AI](#3-chemotherapy--oncology-ai) | Treatment planning, dose optimization, tumor analysis | [chemotherapy-oncology/](chemotherapy-oncology/) |
| 4 | [Electronic Health Records (EHR)](#4-electronic-health-records) | Clinical NLP, predictive analytics, interoperability | [electronic-health-records/](electronic-health-records/) |
| 5 | [Agentic AI in Medicine](#5-agentic-ai-in-medicine) | Autonomous AI agents, clinical decision support | [agentic-ai-medicine/](agentic-ai-medicine/) |
| 6 | [Hospital Operations](#6-hospital-operations) | Scheduling, staffing, supply chain, revenue cycle | [hospital-operations/](hospital-operations/) |
| 7 | [Drug Discovery & Development](#7-drug-discovery--development) | Molecule design, clinical trials, repurposing | [drug-discovery/](drug-discovery/) |
| 8 | [Diagnostics & Lab AI](#8-diagnostics--lab-ai) | Point-of-care, genomics, lab automation | [diagnostics/](diagnostics/) |
| 9 | [Mental Health AI](#9-mental-health-ai) | Therapy bots, mood tracking, crisis detection | [mental-health/](mental-health/) |
| 10 | [Wearables & IoT](#10-wearables--remote-monitoring) | Remote monitoring, vital signs AI, edge computing | [wearables-iot/](wearables-iot/) |
| 11 | [Research Papers](#11-research-papers) | 100+ landmark papers organized by topic | [research-papers/](research-papers/) |
| 12 | [Resources & Links](#12-resources--links) | YouTube channels, blogs, courses, datasets, conferences | [resources/](resources/) |
| 13 | [Future Automations](#13-future-automations) | What CAN be automated — opportunity map for builders | [future-automations/](future-automations/) |

---

## 1. Medical Imaging AI

**The most mature area of healthcare AI.** AI now matches or exceeds radiologist performance in specific tasks.

### Key Applications
| Application | What AI Does | Accuracy | FDA Cleared? |
|-------------|-------------|----------|-------------|
| Chest X-ray analysis | Detect pneumonia, TB, lung nodules, cardiomegaly | 94-97% | Yes (multiple) |
| Mammography screening | Detect breast cancer, reduce false positives | 88-94% AUC | Yes |
| CT lung screening | Detect pulmonary nodules, measure growth | 95%+ sensitivity | Yes |
| Brain MRI analysis | Detect tumors, stroke, Alzheimer's biomarkers | 90-96% | Yes |
| Retinal imaging | Detect diabetic retinopathy, glaucoma, AMD | 87-97% | Yes |
| Skin lesion analysis | Classify melanoma vs benign lesions | 91-95% | Yes |
| Pathology (whole slide) | Detect cancer in tissue slides | 92-99% | Yes |
| Cardiac echo analysis | Measure ejection fraction, valve disease | 93-96% | Yes |
| Fracture detection | Detect bone fractures in X-rays | 92-97% | Yes |
| Dental X-rays | Detect cavities, periodontal disease | 90-95% | Yes |

### Top Companies
| Company | Focus | Notable | Funding/Status |
|---------|-------|---------|---------------|
| **Viz.ai** | Stroke detection | <6 min alert to specialist | $250M+ raised |
| **Aidoc** | Full-body CT triage | Always-on radiology AI | $250M+ raised |
| **Tempus** | Cancer genomics + imaging | Largest clinical database | IPO 2024 |
| **PathAI** | Digital pathology | Partners with top pharma | $400M+ raised |
| **Paige AI** | Cancer pathology | First FDA-cleared AI pathology | $200M+ raised |
| **Zebra Medical** | Multi-organ imaging | 12+ FDA clearances | Acquired by Nanox |
| **Qure.ai** | Chest X-ray, head CT | Strong in India, Africa | $65M+ raised |
| **Lunit** | Mammography, chest X-ray | South Korea leader | Public (KOSDAQ) |
| **HeartFlow** | Coronary artery analysis | Non-invasive FFR from CT | IPO 2024 |
| **Caption Health** | Ultrasound guidance | AI-guided echo | Acquired by GE |
| **Google Health** | Retinal, mammography, dermatology | DeepMind research | Alphabet |
| **Butterfly Network** | Handheld ultrasound + AI | Point-of-care imaging | Public (NYSE) |

**[Full details →](medical-imaging/README.md)**

---

## 2. Surgery & Robotics

**AI is transforming surgery** from pre-operative planning to intra-operative guidance to post-operative monitoring.

### Levels of Surgical Automation
| Level | Description | Current State |
|-------|-------------|--------------|
| **Level 0** | No autonomy — surgeon in full control | Traditional surgery |
| **Level 1** | Robot assistance — surgeon controls robot | **Da Vinci, Hugo RAS** |
| **Level 2** | Task autonomy — robot performs specific subtasks | **Emerging (suturing, cutting)** |
| **Level 3** | Conditional autonomy — robot does procedure, surgeon supervises | **Research stage** |
| **Level 4** | High autonomy — robot handles most situations | **Future (5-10 years)** |
| **Level 5** | Full autonomy — no surgeon needed | **Distant future** |

### Top Surgical AI Companies
| Company | Product | Type | Status |
|---------|---------|------|--------|
| **Intuitive Surgical** | Da Vinci 5 | Robotic surgery platform | Public ($150B+) |
| **Medtronic** | Hugo RAS | Robotic-assisted surgery | Commercializing |
| **Johnson & Johnson** | OTTAVA | Digital surgery platform | Development |
| **Stryker** | Mako SmartRobotics | Orthopedic robot | Market leader |
| **Zimmer Biomet** | ROSA Robot | Knee/spine surgery | Growing |
| **CMR Surgical** | Versius | Modular surgical robot | $1.6B+ raised |
| **Vicarious Surgical** | Miniature robot | Single-incision surgery | Public |
| **Proximie** | AR surgical platform | Remote surgery assistance | $80M+ raised |
| **Activ Surgical** | ActivSight | Intraoperative imaging AI | $50M+ raised |
| **Theator** | Surgical intelligence | Video analysis of surgery | $30M+ raised |

**[Full details →](surgery-robotics/README.md)**

---

## 3. Chemotherapy & Oncology AI

**AI is personalizing cancer treatment** — from tumor genomics to optimal drug combinations to radiation planning.

### AI Applications in Oncology
| Application | What AI Does | Impact |
|-------------|-------------|--------|
| Tumor detection & staging | Identify tumors, classify grade/stage | Earlier detection |
| Treatment planning | Select optimal chemo regimen | 20-30% better outcomes |
| Radiation dose optimization | Calculate precise radiation delivery | Reduce side effects |
| Drug sensitivity prediction | Predict which drugs a tumor responds to | Personalized therapy |
| Treatment response monitoring | Track tumor changes over time | Faster adaptation |
| Toxicity prediction | Predict adverse drug reactions | Reduce hospitalizations |
| Clinical trial matching | Match patients to relevant trials | Increased enrollment |
| Survival prediction | Estimate prognosis from multi-modal data | Better care planning |

### Top Oncology AI Companies
| Company | Focus | Notable |
|---------|-------|---------|
| **Tempus** | Genomic profiling + AI | Largest clinical dataset, IPO 2024 |
| **Foundation Medicine** (Roche) | Tumor genomics | FoundationOne CDx |
| **Flatiron Health** (Roche) | Oncology EHR + analytics | Real-world evidence |
| **Varian** (Siemens) | Radiation therapy AI | AI treatment planning |
| **Elekta** | Radiation therapy | Unity MR-linac + AI |
| **SOPHiA Genetics** | Genomic data analysis | Multi-modal AI platform |
| **Immunai** | Immune system profiling | Single-cell AI |
| **Owkin** | Federated learning oncology | France-based, $300M+ |
| **Concerto HealthAI** | Real-world oncology data | Treatment insights |
| **Predictive Oncology** | Drug sensitivity | Lab + AI combination |

**[Full details →](chemotherapy-oncology/README.md)**

---

## 4. Electronic Health Records

**EHR systems hold 80% of clinical data** — AI is finally making it useful.

### AI Applications in EHR
| Application | What AI Does | Tools |
|-------------|-------------|-------|
| Clinical NLP | Extract info from unstructured notes | AWS Comprehend Medical, Google HCNLP |
| Predictive analytics | Predict readmission, deterioration, sepsis | Epic Sepsis Model, CLEW |
| Clinical decision support | Alert physicians to drug interactions, guidelines | Epic CDS, Cerner AI |
| Automated coding | Generate ICD/CPT codes from notes | 3M, Nuance DAX |
| Note generation | Auto-generate clinical notes from conversation | Nuance DAX, Abridge, Nabla |
| Prior authorization | Automate insurance pre-approval | Olive AI, Cohere Health |
| Population health | Identify at-risk patient cohorts | Health Catalyst, Innovaccer |
| Interoperability | Map data across systems (FHIR, HL7) | Rhino Health, 1upHealth |

### Top EHR AI Companies
| Company | Product | Focus |
|---------|---------|-------|
| **Epic Systems** | Cognitive Computing | Embedded AI in #1 EHR |
| **Oracle Health** (Cerner) | AI Platform | Cloud-based EHR AI |
| **Nuance** (Microsoft) | DAX Copilot | Ambient clinical documentation |
| **Abridge** | AI Medical Scribe | Real-time note generation |
| **Nabla** | Copilot for Clinicians | European clinical AI |
| **Suki AI** | Voice Assistant | AI for clinical documentation |
| **Health Catalyst** | DOS Platform | Healthcare analytics |
| **Innovaccer** | Health Cloud | Patient data unification |
| **Google Cloud Healthcare** | Healthcare API | FHIR + AI integration |

**[Full details →](electronic-health-records/README.md)**

---

## 5. Agentic AI in Medicine

**The newest frontier** — autonomous AI agents that can reason, plan, and take actions in clinical settings.

### Current Medical AI Agents
| Agent/System | Developer | Capability | Status |
|-------------|-----------|-----------|--------|
| Med-PaLM 2 | Google | Medical Q&A, expert-level answers | Research |
| AMIE | Google | Diagnostic dialogue, history-taking | Research |
| GPT-4 Medical | OpenAI | Clinical reasoning, board exam passing | Available |
| BiomedGPT | Microsoft | Multi-task biomedical AI | Open-source |
| Med-Gemini | Google | Multimodal medical reasoning | Research |
| ClinicalAgent | Various | Autonomous clinical workflow | Emerging |
| PathChat | HMS/MIT | Pathology consultation agent | Research |
| RadAgent | Research | Autonomous radiology reporting | Prototype |
| PharmAgent | Research | Drug interaction checking agent | Prototype |
| TrialGPT | NIH | Clinical trial matching agent | Open-source |

**[Full details →](agentic-ai-medicine/README.md)**

---

## 6. Hospital Operations

**AI saving hospitals 15-30% on operational costs** through optimization of workflows, staffing, and supply chains.

### Operational AI Applications
| Area | AI Application | Typical ROI |
|------|---------------|------------|
| Patient scheduling | Predict no-shows, optimize slots | 20-30% reduction in gaps |
| Bed management | Predict discharges, optimize assignment | 10-15% more capacity |
| Staffing | Predict patient volume, auto-schedule | 15-25% labor cost savings |
| Supply chain | Predict demand, auto-reorder | 20-30% inventory reduction |
| Revenue cycle | Auto-coding, denial prediction | 5-15% revenue increase |
| Emergency dept | Predict arrivals, triage priority | 20-40% wait time reduction |
| OR utilization | Schedule optimization, turnover prediction | 15-25% more cases |
| Readmission prevention | Identify high-risk patients | 10-20% reduction |

**[Full details →](hospital-operations/README.md)**

---

## 7. Drug Discovery & Development

**AI reducing drug development from 10-15 years to 3-5 years** and from $2.6B to potentially $300M per drug.

### AI in Drug Discovery Pipeline
| Stage | AI Application | Time Savings |
|-------|---------------|-------------|
| Target identification | Protein structure prediction, pathway analysis | 1-2 years → months |
| Molecule design | Generative chemistry, virtual screening | 2-3 years → weeks |
| Preclinical testing | Toxicity prediction, ADMET modeling | 1-2 years → months |
| Clinical trial design | Patient selection, endpoint prediction | 20-30% faster |
| Clinical trial execution | Site selection, enrollment prediction | 15-25% faster |
| Regulatory submission | Document generation, safety analysis | Months → weeks |

### Top Drug Discovery AI Companies
| Company | Focus | Funding | Notable |
|---------|-------|---------|---------|
| **Recursion** | Full-stack drug discovery | Public ($2B+) | OS-level biology platform |
| **Insilico Medicine** | End-to-end AI drug design | $400M+ | First AI-designed drug in Phase 2 |
| **Exscientia** | Precision medicine | Public | AI-designed molecules in clinic |
| **Isomorphic Labs** (DeepMind) | Protein-based drug design | Alphabet | AlphaFold technology |
| **Relay Therapeutics** | Motion-based drug design | Public | AI + structural biology |
| **Schrödinger** | Physics-based drug design | Public ($3B+) | Molecular simulation |
| **BenevolentAI** | Drug repurposing + discovery | Public (London) | COVID drug candidates |
| **Atomwise** | Structure-based drug design | $175M+ | Virtual screening |
| **XtalPi** | AI + quantum physics | $700M+ | Crystal structure prediction |
| **Generate Biomedicines** | Generative protein design | $370M+ | De novo protein generation |

**[Full details →](drug-discovery/README.md)**

---

## 8. Diagnostics & Lab AI

| Application | AI Capability | Companies |
|-------------|------------|-----------|
| Blood work analysis | Auto-interpret CBC, metabolic panels | Sight Diagnostics, SigTuple |
| Genomic analysis | Variant calling, interpretation | Illumina DRAGEN, Deep Genomics |
| Liquid biopsy | Detect cancer from blood draw | GRAIL, Guardant Health |
| Microbiology | Pathogen identification, resistance prediction | Accelerate Diagnostics, BioMérieux |
| Point-of-care testing | AI-enabled rapid diagnostics | Butterfly Network, Healthy.io |

**[Full details →](diagnostics/README.md)**

---

## 9. Mental Health AI

| Application | What AI Does | Companies |
|-------------|-------------|-----------|
| Therapy chatbots | CBT-based conversational therapy | Woebot, Wysa, Youper |
| Mood tracking | NLP analysis of speech/text patterns | Ginger, Mindstrong |
| Crisis detection | Identify suicidal ideation signals | Crisis Text Line AI |
| Treatment matching | Match patients to therapists/treatments | Spring Health, Cerebral |
| Digital therapeutics | FDA-cleared AI treatments | Pear Therapeutics, Freespira |

**[Full details →](mental-health/README.md)**

---

## 10. Wearables & Remote Monitoring

| Device/Platform | AI Capability | Company |
|----------------|--------------|---------|
| Apple Watch | Afib detection, fall detection, SpO2 | Apple |
| Fitbit/Pixel Watch | Heart rate anomaly, stress, sleep staging | Google |
| Dexcom G7 | Continuous glucose monitoring + AI | Dexcom |
| Oura Ring | Sleep analysis, temperature tracking | Oura |
| BioButton | Continuous vital signs monitoring | BioIntelliSense |
| Current Health | Hospital-at-home monitoring | Best Buy Health |
| Biofourmis | AI-powered remote therapeutics | Biofourmis |
| Livongo | Chronic condition management | Teladoc Health |

**[Full details →](wearables-iot/README.md)**

---

## 11. Research Papers

100+ landmark papers organized by topic. **[Full collection →](research-papers/README.md)**

### Most-Cited AI Healthcare Papers
| Paper | Year | Citations | Topic |
|-------|------|----------|-------|
| Dermatologist-level classification of skin cancer (Esteva et al.) | 2017 | 12,000+ | Dermatology AI |
| CheXNet: Radiologist-level pneumonia detection (Rajpurkar et al.) | 2017 | 5,000+ | Chest X-ray |
| Highly accurate protein structure prediction (Jumper/AlphaFold) | 2021 | 20,000+ | Drug discovery |
| A foundation model for generalist medical AI (Med-PaLM) | 2023 | 2,000+ | Medical LLMs |
| Development and validation of a deep learning algorithm for diabetic retinopathy | 2016 | 8,000+ | Ophthalmology |

---

## 12. Resources & Links

YouTube channels, blogs, courses, conferences, and datasets.
**[Full resources →](resources/README.md)**

---

## 13. Future Automations

**What CAN be built?** An opportunity map for developers, researchers, and entrepreneurs.
**[Full guide →](future-automations/README.md)**

---

## Quick Stats: AI in Healthcare

```
Global AI in Healthcare Market (2024):     $22.5 Billion
Projected Market Size (2030):              $187.9 Billion
CAGR (2024-2030):                          38.4%
FDA-Cleared AI/ML Medical Devices:         900+
AI Healthcare Startups:                    3,500+
Clinical Trials Using AI (2024):           1,200+
Lives Impacted by Healthcare AI:           Billions
```

---

## Contributing

This is a living document. If you know a tool, paper, or company we missed — open a PR!

## License

MIT License — See [LICENSE](LICENSE) for details.

---

*Maintained by [Milan Amrut Joshi](https://github.com/mlnjsh) — Professor of Data Science, Northwestern University*
