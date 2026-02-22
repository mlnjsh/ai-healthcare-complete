<div align="center">

# AI in Healthcare — The Complete Resource

### The most comprehensive open-source guide to AI transforming medicine

**From radiology AI reading scans in seconds to AI-designed drugs entering clinical trials — this repository maps the entire landscape of artificial intelligence in healthcare.**

[![Sections](https://img.shields.io/badge/Sections-13-blue?style=for-the-badge)]()
[![Tools & Companies](https://img.shields.io/badge/Tools%20%26%20Companies-200+-green?style=for-the-badge)]()
[![Research Papers](https://img.shields.io/badge/Research%20Papers-100+-orange?style=for-the-badge)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Updated-Feb%202025-brightgreen?style=for-the-badge)]()

<br>

```
                    +--------------------------+
                    |    AI in Healthcare      |
                    |    Complete Resource      |
                    +------------+-------------+
                                 |
          +----------+-----------+-----------+----------+
          |          |           |           |          |
     +----v----+ +---v---+ +----v----+ +----v----+ +---v---+
     |  Imaging | |Surgery| |  Drug   | |  EHR &  | | Mental|
     |    AI    | |Robots | |Discovery| |  NLP    | | Health|
     +---------+ +-------+ +---------+ +---------+ +-------+
          |          |           |           |          |
     +----v----+ +---v---+ +----v----+ +----v----+ +---v---+
     |Wearables| |Oncology| |Hospital| |Diagnostics| |Agentic|
     |  & IoT  | |  AI   | |  Ops   | |  & Lab  | |  AI   |
     +---------+ +-------+ +--------+ +---------+ +-------+
```

</div>

---

## Why This Repository?

> **4.3 million** people die annually from conditions AI can help detect earlier. **$2.6 billion** is spent developing a single drug that AI could reduce to **$300 million**. Radiologists face burnout reading **50+ scans per hour** while AI can flag critical findings in **seconds**.

This repository is a **one-stop reference** for anyone working at the intersection of AI and healthcare — whether you're a researcher, clinician, developer, entrepreneur, or student. Every section contains:

- **Real companies** with funding data and product details
- **Research papers** linked to Nature, JAMA, arXiv, Cell
- **Open-source tools** with GitHub repositories
- **Market data** and growth projections
- **Future opportunities** for builders

---

## The Market at a Glance

<div align="center">

| Metric | Value |
|:------:|:-----:|
| **Global AI Healthcare Market (2024)** | **$22.5 Billion** |
| **Projected Market (2030)** | **$187.9 Billion** |
| **Growth Rate (CAGR)** | **38.4%** |
| **FDA-Cleared AI Devices** | **900+** |
| **AI Healthcare Startups** | **3,500+** |
| **Clinical Trials Using AI** | **1,200+** |

</div>

---

## Navigate by Section

<div align="center">

| | Section | Highlights | Explore |
|:---:|---------|------------|:-------:|
| 01 | **[Medical Imaging AI](#-medical-imaging-ai)** | 12+ FDA-cleared companies, 94-99% accuracy, radiology + pathology + ophthalmology | **[Read More](medical-imaging/)** |
| 02 | **[Surgery & Robotics](#-surgery--robotics)** | Da Vinci 5, Hugo RAS, 5 levels of surgical autonomy, $150B+ market leader | **[Read More](surgery-robotics/)** |
| 03 | **[Chemotherapy & Oncology](#-chemotherapy--oncology-ai)** | Precision dosing, tumor genomics, 20-30% better outcomes | **[Read More](chemotherapy-oncology/)** |
| 04 | **[Electronic Health Records](#-electronic-health-records)** | Ambient scribes, clinical NLP, medical LLMs, FHIR interoperability | **[Read More](electronic-health-records/)** |
| 05 | **[Agentic AI in Medicine](#-agentic-ai-in-medicine)** | Autonomous clinical agents, Med-PaLM, AMIE, LLM frameworks | **[Read More](agentic-ai-medicine/)** |
| 06 | **[Hospital Operations](#-hospital-operations)** | 15-30% cost savings, OR optimization, predictive staffing | **[Read More](hospital-operations/)** |
| 07 | **[Drug Discovery](#-drug-discovery--development)** | 10 years to 3 years, AlphaFold, generative chemistry, $11B market | **[Read More](drug-discovery/)** |
| 08 | **[Diagnostics & Lab AI](#-diagnostics--lab-ai)** | Liquid biopsy, genomic analysis, autonomous diagnostics | **[Read More](diagnostics/)** |
| 09 | **[Mental Health AI](#-mental-health-ai)** | CBT chatbots, voice biomarkers, 5M+ users on single platforms | **[Read More](mental-health/)** |
| 10 | **[Wearables & IoT](#-wearables--remote-monitoring)** | AFib detection, CGM, remote patient monitoring, $120B by 2030 | **[Read More](wearables-iot/)** |
| 11 | **[Research Papers](#-research-papers)** | 100+ landmark papers, AlphaFold to Med-PaLM, all with DOIs | **[Read More](research-papers/)** |
| 12 | **[Resources & Links](#-resources--links)** | YouTube, blogs, courses, datasets, communities, conferences | **[Read More](resources/)** |
| 13 | **[Future Automations](#-future-automations)** | Opportunity map for builders — what CAN be automated next | **[Read More](future-automations/)** |

</div>

---

## Medical Imaging AI

> **The most mature area of healthcare AI.** AI now matches or exceeds radiologist performance in specific diagnostic tasks across 10+ medical specialties.

### What AI Can Detect Today

| Application | Accuracy | FDA Cleared? | Clinical Impact |
|-------------|:--------:|:------------:|-----------------|
| Chest X-ray (pneumonia, TB, nodules) | 94-97% | Yes | Triage in seconds vs hours |
| Mammography screening | 88-94% AUC | Yes | 20% fewer false positives |
| CT lung screening | 95%+ | Yes | Early-stage cancer detection |
| Brain MRI (tumors, stroke, Alzheimer's) | 90-96% | Yes | Golden-hour stroke alerts |
| Retinal imaging (DR, glaucoma) | 87-97% | Yes | First FDA autonomous AI (IDx-DR) |
| Digital pathology (cancer grading) | 92-99% | Yes | Consistent, reproducible diagnosis |
| Cardiac echo analysis | 93-96% | Yes | AI-guided by non-specialists |
| Fracture detection | 92-97% | Yes | Reduced missed fractures |

### Top Companies

| Company | Specialty | Why They Stand Out | Status |
|---------|----------|-------------------|--------|
| **[Viz.ai](https://viz.ai)** | Stroke detection | Alerts specialists in <6 minutes, saves brain tissue | $250M+ raised |
| **[Aidoc](https://aidoc.com)** | Full-body CT triage | Always-on AI across entire radiology workflow | $250M+ raised |
| **[Tempus](https://tempus.com)** | Cancer genomics + imaging | Largest clinical + molecular dataset in oncology | IPO 2024 |
| **[PathAI](https://pathai.com)** | Digital pathology | Partners with Bristol-Myers, Roche, Novartis | $400M+ raised |
| **[Paige AI](https://paige.ai)** | Cancer pathology | First-ever FDA-cleared AI for pathology | $200M+ raised |
| **[Qure.ai](https://qure.ai)** | Chest X-ray, head CT | Deployed across 85+ countries, strong in LMICs | $65M+ raised |
| **[Lunit](https://lunit.io)** | Mammography, chest X-ray | South Korea's AI imaging leader | Public (KOSDAQ) |
| **[Caption Health](https://captionhealth.com)** | Ultrasound guidance | Enables non-experts to perform cardiac ultrasound | Acquired by GE |

<details>
<summary><b>See more: Google Health, Butterfly Network, HeartFlow, Zebra Medical...</b></summary>

| Company | Focus | Status |
|---------|-------|--------|
| **Google Health** | Retinal screening, mammography, dermatology | Alphabet (DeepMind research) |
| **Butterfly Network** | Handheld ultrasound + AI | Public (NYSE: BFLY) |
| **HeartFlow** | Non-invasive coronary artery analysis | IPO 2024 |
| **Zebra Medical** | Multi-organ imaging (12+ FDA clearances) | Acquired by Nanox |

</details>

**[Full medical imaging deep-dive with 33+ companies, 20+ papers, 13 datasets](medical-imaging/)**

---

## Surgery & Robotics

> **From da Vinci to autonomous suturing** — AI is transforming every phase of surgery from planning to real-time guidance to post-op analytics.

### The Path to Autonomous Surgery

```
Level 0          Level 1          Level 2          Level 3          Level 4          Level 5
No autonomy  --> Robot-assisted -> Task autonomy -> Conditional  --> High autonomy -> Full autonomy
                 (Da Vinci,        (auto-suturing,  (robot does       (most            (no surgeon
Traditional       Hugo RAS)         auto-cutting)    procedure,        situations       needed)
surgery                                              surgeon           handled)
                                                     supervises)
                 [== TODAY ==]     [= EMERGING =]   [= RESEARCH =]   [== 5-10 YR ==]  [== FUTURE ==]
```

### Key Players

| Company | Product | What Makes Them Special | Market Position |
|---------|---------|------------------------|----------------|
| **[Intuitive Surgical](https://intuitivesurgical.com)** | Da Vinci 5 | 9M+ procedures performed worldwide | Public ($150B+ market cap) |
| **[Medtronic](https://medtronic.com)** | Hugo RAS | Modular, open-console approach | Commercializing globally |
| **[Stryker](https://stryker.com)** | Mako SmartRobotics | Dominant in joint replacement | Market leader (ortho) |
| **[Johnson & Johnson](https://jnjmedtech.com)** | OTTAVA | Full digital surgery ecosystem | In development |
| **[CMR Surgical](https://cmrsurgical.com)** | Versius | Small, modular, cost-effective | $1.6B+ raised |
| **[Theator](https://theator.io)** | Surgical intelligence | AI video analysis of every procedure | $30M+ raised |
| **[Activ Surgical](https://activsurgical.com)** | ActivSight | Real-time tissue visualization | $50M+ raised |

**[Full surgery & robotics deep-dive with 13 companies, research papers, YouTube channels](surgery-robotics/)**

---

## Chemotherapy & Oncology AI

> **AI is making cancer treatment personal.** From predicting which drug cocktail will work for YOUR tumor to optimizing radiation down to the millimeter.

### How AI Changes Cancer Care

| Stage of Cancer Care | AI Application | Real-World Impact |
|---------------------|---------------|-------------------|
| **Early Detection** | Multi-cancer blood tests | GRAIL's Galleri detects 50+ cancer types from blood |
| **Tumor Profiling** | Genomic + proteomic analysis | Match patients to targeted therapies |
| **Treatment Selection** | Drug sensitivity prediction | 20-30% better treatment outcomes |
| **Radiation Planning** | AI dose optimization | Reduce planning time from days to hours |
| **Response Monitoring** | Tumor tracking over time | Faster adaptation when treatment fails |
| **Clinical Trials** | AI patient-trial matching | 3x enrollment improvement |

### Leading Companies

| Company | Superpower | Scale |
|---------|-----------|-------|
| **[Tempus](https://tempus.com)** | Largest clinical + molecular dataset in oncology | IPO 2024, 600K+ patients profiled |
| **[Foundation Medicine](https://foundationmedicine.com)** | Comprehensive genomic profiling (FoundationOne CDx) | Part of Roche |
| **[Guardant Health](https://guardanthealth.com)** | Liquid biopsy for cancer detection | Public, Guardant360 CDx |
| **[GRAIL](https://grail.com)** | Multi-cancer early detection from blood (Galleri) | Part of Illumina |
| **[Owkin](https://owkin.com)** | Federated learning across hospital data | $300M+ raised (France) |

**[Full oncology AI deep-dive with 23 companies, clinical platforms, treatment pipelines](chemotherapy-oncology/)**

---

## Electronic Health Records

> **80% of clinical data is trapped in unstructured notes.** AI is finally unlocking it — from ambient scribes that write notes during patient visits to LLMs that reason over medical records.

### The EHR AI Stack

```
  +-----------------------------------------------------------+
  |                    CLINICIAN INTERFACE                      |
  |  Ambient scribes | Voice AI | Clinical copilots            |
  +-----------------------------------------------------------+
  |                    AI INTELLIGENCE LAYER                    |
  |  NLP extraction | Predictive models | Clinical reasoning   |
  +-----------------------------------------------------------+
  |                    DATA INFRASTRUCTURE                      |
  |  FHIR | SNOMED | LOINC | OMOP | HL7                       |
  +-----------------------------------------------------------+
  |                    EHR PLATFORMS                            |
  |  Epic | Oracle Health | MEDITECH | athenahealth             |
  +-----------------------------------------------------------+
```

### Companies Transforming EHR

| Company | Product | Impact |
|---------|---------|--------|
| **[Nuance](https://nuance.com/healthcare/ambient-clinical-intelligence.html)** (Microsoft) | DAX Copilot | Ambient documentation — listens and writes notes automatically |
| **[Abridge](https://abridge.com)** | AI Medical Scribe | Real-time structured note generation from conversations |
| **[Suki AI](https://suki.ai)** | Voice Assistant | 72% reduction in documentation time |
| **[Epic Systems](https://epic.com)** | Cognitive Computing | Embedded AI in the #1 EHR serving 305M+ patients |
| **[Oracle Health](https://oracle.com/health/)** | AI Platform | Cloud-native EHR with integrated AI |
| **[Glass Health](https://glass.health)** | AI Diagnosis | Differential diagnosis generation from notes |

**[Full EHR deep-dive with medical LLMs, NLP tools, data standards, open-source tools](electronic-health-records/)**

---

## Agentic AI in Medicine

> **The newest frontier.** Unlike traditional AI that answers questions, agentic AI systems can *reason*, *plan*, *take actions*, and *learn* — autonomously handling complex clinical workflows.

### Current AI Agents in Medicine

| Agent | Developer | What It Can Do | Status |
|-------|-----------|---------------|--------|
| **AMIE** | Google | Take patient history, generate differential diagnosis | Research |
| **Med-PaLM 2** | Google | Answer medical questions at expert level | Research |
| **GPT-4 Medical** | OpenAI | Pass medical board exams, clinical reasoning | Available |
| **Med-Gemini** | Google | Multimodal reasoning (images + text + labs) | Research |
| **TrialGPT** | NIH | Automatically match patients to clinical trials | Open-source |
| **PathChat** | HMS/MIT | Pathology image consultation agent | Research |

### Companies Building Healthcare Agents

| Company | What They're Building |
|---------|----------------------|
| **[Hippocratic AI](https://hippocratic.ai)** | Safety-focused LLM for healthcare ($120M raised) |
| **[Notable Health](https://notablehealth.com)** | Intelligent workflow automation for health systems |
| **[AKASA](https://akasa.com)** | Revenue cycle automation with AI agents |
| **[Infinitus](https://infinitus.ai)** | AI phone agents handling insurance calls |
| **[K Health](https://khealth.com)** | AI-powered primary care diagnosis |

**[Full agentic AI deep-dive with LLM frameworks (LangChain, AutoGen, CrewAI), research papers](agentic-ai-medicine/)**

---

## Hospital Operations

> **AI is saving hospitals 15-30% on operational costs** — predicting patient volume, optimizing OR schedules, automating billing, and preventing readmissions.

| Operational Area | AI Delivers | Typical ROI |
|-----------------|-------------|:-----------:|
| Patient scheduling | Predict no-shows, fill cancellations | 20-30% fewer gaps |
| Bed management | Predict discharges, optimize flow | 10-15% more capacity |
| Staffing | Match staff to predicted demand | 15-25% cost savings |
| Supply chain | Predict demand, auto-reorder | 20-30% less waste |
| Revenue cycle | Auto-coding, denial prediction | 5-15% revenue lift |
| Emergency dept | Predict arrivals, smart triage | 20-40% less waiting |
| OR utilization | Scheduling + turnover optimization | 15-25% more cases |

### Key Players: [Qventus](https://qventus.com) | [LeanTaaS](https://leantaas.com) | [Care.ai](https://care.ai) | [Cedar](https://cedar.com) | [Palantir](https://palantir.com)

**[Full hospital operations deep-dive with 29 companies, case studies, ROI data](hospital-operations/)**

---

## Drug Discovery & Development

> **AI is compressing 10-15 years of drug development into 3-5 years** — and the first AI-designed drugs are already in human clinical trials.

### The AI Drug Discovery Revolution

```
TRADITIONAL PIPELINE                    AI-ACCELERATED PIPELINE
=====================                   =======================

Target ID         3-5 years             Target ID         1-2 years
Hit Discovery     2-3 years     --->    Hit Discovery     3-6 months
Lead Optimization 2-3 years             Lead Optimization 6-12 months
Preclinical       1-2 years             Preclinical       6-12 months
Clinical Trials   6-10 years            Clinical Trials   3-5 years
                  ___________                             ___________
Total:            12-17 years           Total:            5-8 years
Cost:             $2.6 Billion          Cost:             ~$1 Billion
```

### AI Drug Candidates Already in Human Trials

| Molecule | Company | Disease | Stage | Significance |
|----------|---------|---------|:-----:|-------------|
| INS018_055 | [Insilico Medicine](https://insilico.com) | Pulmonary fibrosis | Phase II | First fully AI-designed drug in Phase II |
| DSP-1181 | [Exscientia](https://exscientia.ai) / Sumitomo | OCD | Phase I | First AI-designed molecule to enter trials |
| REC-994 | [Recursion](https://recursion.com) | Cerebral cavernous malformation | Phase II | AI-matched repurposed drug |
| BEN-2293 | BenevolentAI | Atopic dermatitis | Phase II | Knowledge-graph discovered target |

### Breakthrough Tools

| Tool | What It Does | Impact |
|------|-------------|--------|
| **[AlphaFold](https://github.com/google-deepmind/alphafold)** | Predicts 3D protein structure | Nobel Prize 2024, 200M+ structures predicted |
| **[RFdiffusion](https://github.com/RosettaCommons/RFdiffusion)** | Designs entirely new proteins | De novo protein generation |
| **[DiffDock](https://github.com/gcorso/DiffDock)** | Predicts how drugs bind to targets | Faster virtual screening |
| **[RDKit](https://github.com/rdkit/rdkit)** | Open-source cheminformatics | Industry standard toolkit |

**[Full drug discovery deep-dive with 21 companies, open-source tools, clinical trial data](drug-discovery/)**

---

## Diagnostics & Lab AI

> **From blood draws to genomic sequencing** — AI is making diagnostics faster, cheaper, and more accessible worldwide.

| Diagnostic Area | AI Capability | Key Companies |
|----------------|--------------|---------------|
| Blood analysis | Automated CBC, morphology classification | [Sight Diagnostics](https://sightdx.com), [Scopio Labs](https://scopiolabs.com) |
| Liquid biopsy | Detect 50+ cancers from a single blood draw | [GRAIL](https://grail.com) (Galleri), [Guardant Health](https://guardanthealth.com) |
| Genomics | Variant calling + interpretation at scale | [Illumina](https://illumina.com) DRAGEN, [Invitae](https://invitae.com) |
| Heart sounds | AI stethoscope detecting murmurs | [Eko Health](https://ekohealth.com) (FDA-cleared) |
| Symptom assessment | AI-powered differential diagnosis | [Ada Health](https://ada.com), [Glass Health](https://glass.health) |
| Point-of-care ECG | Personal arrhythmia detection | [AliveCor](https://alivecor.com) (KardiaMobile) |
| Proteomics | 7,000+ protein biomarker panels | [SomaLogic](https://somalogic.com) |

**[Full diagnostics deep-dive with 39 companies, open-source datasets (MIMIC, Synthea), research papers](diagnostics/)**

---

## Mental Health AI

> **1 billion people worldwide suffer from mental health disorders, but there's a global shortage of 4.3 million mental health workers.** AI is scaling access to care.

| Approach | What AI Does | Leading Platform | Users |
|----------|-------------|-----------------|:-----:|
| CBT chatbots | Deliver therapy conversations 24/7 | [Woebot](https://woebothealth.com) (FDA Breakthrough) | 1.5M+ |
| AI companions | Emotional support and coaching | [Wysa](https://wysa.com) | 5M+ |
| Treatment matching | Match patients to optimal therapy | [Spring Health](https://springhealth.com) | 10M+ covered |
| Voice biomarkers | Detect depression from voice patterns | [Kintsugi](https://kintsugihealth.com) | B2B partnerships |
| Session documentation | AI notes for therapists | [Eleos Health](https://eleoshealth.com) | 50K+ providers |
| Mindfulness + AI | Personalized meditation and wellness | [Headspace](https://headspace.com) | 100M+ |

**[Full mental health AI deep-dive with 30+ companies, ethical frameworks, clinical evidence](mental-health/)**

---

## Wearables & Remote Monitoring

> **Healthcare is moving from the hospital to the wrist.** Smartwatches detect AFib, CGMs predict hypoglycemia, and AI turns continuous sensor data into clinical insights.

| Device | AI Superpower | Impact |
|--------|-------------|--------|
| **[Apple Watch](https://apple.com/apple-watch-series-10/health/)** | AFib detection, fall detection, sleep apnea | 100M+ users, FDA-cleared ECG |
| **[Dexcom G7](https://dexcom.com)** | Predictive glucose alerts | Gold standard CGM for diabetes |
| **[AliveCor KardiaMobile](https://alivecor.com)** | 6-lead personal ECG with AI | FDA-cleared arrhythmia detection |
| **[Oura Ring](https://ouraring.com)** | Sleep, HRV, temperature, SpO2 | Leading health ring |
| **[WHOOP](https://whoop.com)** | Strain, recovery, sleep optimization | Performance monitoring |
| **[iRhythm Zio](https://irhythmtech.com)** | 14-day continuous ECG with AI | Clinical-grade cardiac monitoring |
| **[SWORD Health](https://swordhealth.com)** | AI-guided physical therapy | Digital MSK care |

**[Full wearables deep-dive with all devices, RPM platforms, smart hospital IoT, research papers](wearables-iot/)**

---

## Research Papers

> **100+ landmark papers** that shaped the field — from the 2017 skin cancer paper that started it all to AlphaFold's Nobel Prize in 2024.

### Papers That Changed Everything

| Paper | Year | Why It Matters |
|-------|:----:|---------------|
| Dermatologist-level skin cancer classification (Esteva et al.) | 2017 | Proved AI can match specialists — sparked the field |
| CheXNet: Radiologist-level pneumonia detection | 2017 | First chest X-ray AI to match radiologists |
| AlphaFold: Protein structure prediction | 2021 | **Nobel Prize 2024** — predicted 200M+ protein structures |
| Med-PaLM: Expert-level medical question answering | 2023 | First AI to pass medical licensing exams at expert level |
| A Deep Learning Approach to Antibiotic Discovery | 2020 | AI discovered halicin — a novel antibiotic |

**[Full collection: 100+ papers organized by topic with all DOIs and links](research-papers/)**

---

## Resources & Links

> **Stay current** with the best YouTube channels, blogs, newsletters, datasets, courses, and communities in healthcare AI.

| Category | Top Picks |
|----------|----------|
| **YouTube** | [Two Minute Papers](https://youtube.com/@TwoMinutePapers), [Stanford HAI](https://youtube.com/@StanfordHAI), [3Blue1Brown](https://youtube.com/@3blue1brown) |
| **Courses** | [AI for Medicine (Andrew Ng)](https://coursera.org/specializations/ai-for-medicine) on Coursera |
| **Datasets** | [MIMIC-IV](https://physionet.org/content/mimiciv/2.2/), [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/), [BraTS](https://www.synapse.org/brats) |
| **Open-Source** | [MONAI](https://github.com/Project-MONAI/MONAI), [nnU-Net](https://github.com/MIC-DKFZ/nnUNet), [AlphaFold](https://github.com/google-deepmind/alphafold) |
| **Communities** | [r/MachineLearning](https://reddit.com/r/MachineLearning/), [MONAI Discord](https://github.com/Project-MONAI/MONAI), [OHDSI](https://ohdsi.org) |
| **Regulatory** | [FDA AI/ML Devices](https://fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices), [EU AI Act](https://artificialintelligenceact.eu), [WHO AI Guidance](https://who.int/publications/i/item/9789240029200) |

**[Full resources directory with 100+ links organized by category](resources/)**

---

## Future Automations

> **What CAN be built next?** An opportunity map for developers, researchers, and entrepreneurs — organized by barrier-to-entry and impact potential.

| Opportunity | Barrier | Why Now |
|------------|:-------:|---------|
| AI clinical note generation | Low | LLMs are ready, clinician burnout is critical |
| AI-powered patient intake | Low | Automate forms, insurance verification, scheduling |
| Clinical trial matching | Medium | NLP + EHR integration, massive unmet need |
| AI diagnostic copilot | Medium | Foundation models + FDA pathways maturing |
| Autonomous lab analysis | High | Regulatory complexity, but huge efficiency gains |
| Closed-loop drug discovery | High | AI designs, robots synthesize, AI tests, AI iterates |
| Digital twin of patient | Very High | Requires multi-modal data integration at scale |

**[Full opportunity map with build guides, regulatory info, datasets to get started](future-automations/)**

---

## Key Sources & References

<div align="center">

| Source | Description |
|--------|------------|
| **[FDA AI/ML Medical Devices](https://fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices)** | Complete database of cleared AI devices |
| **[WHO AI for Health](https://who.int/health-topics/artificial-intelligence)** | Global AI health policy and guidance |
| **[Stanford HAI](https://hai.stanford.edu)** | Leading AI research and policy institute |
| **[Nature Medicine](https://nature.com/nm/)** | Top medical AI research journal |
| **[NEJM](https://nejm.org)** | Premier medical journal covering AI studies |
| **[Coalition for Health AI](https://coalitionforhealthai.org)** | Industry standards for responsible health AI |

</div>

---

## Contributing

This is a **living document** — the healthcare AI landscape moves fast, and we want to keep up. Contributions welcome:

- **Found a missing company or tool?** Open a PR
- **Know a paper we should include?** Open an issue
- **Spotted an error?** Let us know

---

## License

MIT License — See [LICENSE](LICENSE) for details.

---

<div align="center">

**Built and maintained by [Milan Amrut Joshi](https://github.com/mlnjsh)**

*Professor of Data Science, Northwestern University*

If you found this useful, consider giving it a star!

</div>
