# AI in Electronic Health Records (EHR)

## Overview

AI in EHR systems transforms how clinical data is captured, analyzed, and used for decision-making. From automating documentation to predicting patient deterioration, AI is embedded across the entire EHR workflow — reducing clinician burnout and improving patient outcomes.

**Market Size:** Clinical AI/EHR intelligence — $4.5B (2024) → projected $18.7B by 2030

---

## Key Applications

### 1. Clinical Documentation AI (Ambient AI)

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Ambient clinical intelligence | AI listens to patient-doctor conversations, auto-generates notes | [Nuance DAX Copilot](https://nuance.com/healthcare/ambient-clinical-intelligence.html), [Abridge](https://abridge.com), [Suki](https://suki.ai) | 50-70% reduction in documentation time |
| Medical transcription | Convert dictated notes to structured text | Nuance Dragon Medical, [3M M*Modal](https://3m.com/3M/en_US/health-information-systems-us/) | 95%+ accuracy |
| Clinical note generation | Generate structured SOAP notes from conversations | [Abridge](https://abridge.com), [Nabla](https://nabla.com), [DeepScribe](https://deepscribe.ai) | Reduces burnout |
| Coding assistance | Auto-suggest ICD-10, CPT codes | 3M CodeFinder, [Nym Health](https://nymhealth.com), AGS Health | 30-40% faster coding |
| Prior authorization automation | Auto-generate prior auth requests | [Olive AI](https://oliveai.com), [Cohere Health](https://coherehealth.com) | Reduces denials |

### 2. Clinical Decision Support (CDS)

| Application | Description | Key Players | Status |
|------------|-------------|-------------|--------|
| Sepsis prediction | Early warning 4-12 hours before onset | Epic Sepsis Model, CLEW Medical | Deployed (varied results) |
| Patient deterioration | Predict ICU transfer, cardiac arrest | Dascena, PeraHealth (Rothman Index) | Clinical use |
| Readmission prediction | 30-day readmission risk scoring | [Jvion](https://jvion.com), [Health Catalyst](https://healthcatalyst.com) | CMS-incentivized |
| Drug interaction checking | AI-enhanced interaction analysis | FDB (First Databank), Medi-Span | Standard in EHRs |
| Diagnostic assistance | Suggest differential diagnoses | [Isabel Healthcare](https://isabelhealthcare.com), [Glass Health](https://glass.health), DXplain | Clinical support |
| Treatment recommendations | Evidence-based treatment suggestions | UpToDate (Wolters Kluwer), DynaMed | Clinical use |

### 3. Population Health AI

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Risk stratification | Identify high-risk patients | [Jvion](https://jvion.com), Arcadia, [Health Catalyst](https://healthcatalyst.com) | 15-30% cost reduction |
| Care gap identification | Find patients missing preventive care | [Innovaccer](https://innovaccer.com), Lightbeam Health | Improved quality metrics |
| Social determinants (SDOH) | Analyze social factors affecting health | Socially Determined, UniteUs | Better outcomes targeting |
| Chronic disease management | Predict disease progression | [Livongo (Teladoc)](https://teladochealth.com), Glooko | Improved A1C, BP control |

### 4. Revenue Cycle Management AI

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Claims denial prediction | Predict which claims will be denied | [Waystar](https://waystar.com), Change Healthcare | 25% fewer denials |
| Auto-coding | AI-suggested medical codes | [Nym Health](https://nymhealth.com), AGS Health, [3M](https://3m.com/3M/en_US/health-information-systems-us/) | Faster, more accurate |
| Charge capture | Identify missed charges | [AKASA](https://akasa.com), [Olive AI](https://oliveai.com) | 5-10% revenue recovery |
| Payment prediction | Predict patient payment behavior | [Cedar](https://cedar.com), Collectly | Better collection rates |

### 5. Natural Language Processing (NLP) for EHR

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Unstructured data extraction | Extract info from clinical notes | Amazon Comprehend Medical, Google | Unlock 80% of EHR data |
| Clinical trial matching | Match patients to trials from EHR data | Tempus, Deep 6 AI, TriNetX | 50% faster enrollment |
| Named entity recognition | Identify medications, conditions, procedures | [MedSpaCy](https://github.com/medspacy/medspacy), [SciSpaCy](https://github.com/allenai/scispacy), [cTAKES](https://ctakes.apache.org) | Research tool |
| Sentiment analysis | Detect patient distress in notes | Research stage | Mental health applications |
| Summarization | Condense long patient histories | Google [Med-PaLM](https://arxiv.org/abs/2305.09617), Epic AI | Reduce information overload |

---

## Major EHR Vendors & AI Integration

### Big EHR AI Features
| Vendor | Market Share (US) | AI Features |
|--------|------------------|-------------|
| [Epic Systems](https://epic.com) | ~38% | Cognitive Computing, Sepsis Model, Hey Epic!, AI-generated summaries, ambient documentation partnership with Nuance |
| [Oracle Health (Cerner)](https://oracle.com/health/) | ~22% | Oracle AI, Clinical AI, Autonomous coding |
| [MEDITECH](https://meditech.com) | ~16% | Google Cloud AI integration, Ambient Scribe |
| Veradigm (Allscripts) | ~5% | AI analytics, population health |
| [athenahealth](https://athenahealth.com) | ~5% | AI denial management, document classification |
| [eClinicalWorks](https://eclinicalworks.com) | ~5% | healow AI assistant |

### AI-Native EHR/Clinical Platforms
| Company | Focus | Notable |
|---------|-------|---------|
| [Abridge](https://abridge.com) | Ambient clinical intelligence | Raised $200M+, partners with Epic |
| [Suki](https://suki.ai) | AI voice assistant for doctors | 70% reduction in note-taking time |
| [Nabla](https://nabla.com) | AI copilot for clinicians | European leader in ambient AI |
| [DeepScribe](https://deepscribe.ai) | Ambient AI scribe | Deployed across 150+ specialties |
| [Glass Health](https://glass.health) | AI diagnostic/treatment support | LLM-powered differential diagnosis |
| [Elation Health](https://elationhealth.com) | AI-native primary care EHR | Built-in AI documentation |
| [Canvas Medical](https://canvasmedical.com) | API-first EHR with AI | Developer-friendly health record |

---

## LLMs in EHR — The New Frontier

### Medical LLMs
| Model | Developer | Capability | Status |
|-------|-----------|-----------|--------|
| [Med-PaLM 2](https://arxiv.org/abs/2305.09617) | Google | Medical question answering, 86.5% on USMLE | Research |
| GPT-4 (medical fine-tuned) | OpenAI | Clinical note generation, coding | Via partners |
| [Meditron](https://arxiv.org/abs/2311.16079) ([GitHub](https://github.com/epfLLM/meditron)) | EPFL | Open-source medical LLM | Open source |
| [BioMistral](https://arxiv.org/abs/2402.10373) | Various | Biomedical text understanding | Open source |
| [ClinicalBERT](https://arxiv.org/abs/1904.05342) | MIT | EHR text embeddings | Open source |
| [GatorTron](https://arxiv.org/abs/2203.03540) | UF Health | Large clinical language model | Research |
| [Nuance DAX Copilot](https://nuance.com/healthcare/ambient-clinical-intelligence.html) | Microsoft/Nuance | Ambient clinical documentation | Production |

### LLM Use Cases in EHR
1. **Patient message triage** — Auto-draft responses to patient portal messages
2. **Chart summarization** — Condense long patient histories for handoffs
3. **Discharge summaries** — Auto-generate discharge instructions
4. **Referral letter writing** — Draft specialist referral letters
5. **Prior auth letters** — Generate medical necessity documentation
6. **Clinical question answering** — Answer clinician questions from patient data

---

## Key Standards & Interoperability

### Data Standards
| Standard | Purpose | Adoption |
|----------|---------|----------|
| [HL7 FHIR](https://hl7.org/fhir/) | Modern API for health data exchange | Mandated in US (21st Century Cures) |
| [SNOMED CT](https://snomed.org) | Clinical terminology | International standard |
| ICD-10/ICD-11 | Disease classification | Global (ICD-11 adopted 2022) |
| [LOINC](https://loinc.org) | Lab and observation codes | Global standard |
| CPT | Procedure codes | US standard |
| RxNorm | Medication terminology | US standard |
| DICOM | Medical imaging standard | Global standard |

### Interoperability Initiatives
- **[TEFCA](https://healthit.gov/topic/interoperability/trusted-exchange-framework-and-common-agreement-tefca)** — Trusted Exchange Framework (US national health data exchange)
- **[SMART on FHIR](https://smarthealthit.org)** — Apps framework for EHR integration
- **CDS Hooks** — Clinical decision support integration standard
- **Bulk FHIR** — Population-level data access
- **International Patient Summary** — Cross-border patient records

---

## Research Papers (Must-Read)

### Foundational
1. **["Scalable and accurate deep learning for EHR"](https://nature.com/articles/s41746-018-0029-1)** — Rajkomar et al. (2018) — Google/UCSF
2. **["Deep Patient: An unsupervised representation of EHR data"](https://nature.com/articles/srep26094)** — Miotto et al. (2016) — Nature Scientific Reports
3. **["ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission"](https://arxiv.org/abs/1904.05342)** — Huang et al. (2020)
4. **["GatorTron: A Large Clinical Language Model"](https://arxiv.org/abs/2203.03540)** — Yang et al. (2022)
5. **"Foresight: Generative Pretrained Transformer for EHR"** — Li et al.

### Recent (2024-2025)
1. **["Med-PaLM 2: Towards Expert-Level Medical Question Answering"](https://arxiv.org/abs/2305.09617)** — Google (2024)
2. **"LLMs for Clinical Note Generation"** — Nuance/Microsoft publications
3. **"Large language models in medicine"** — NEJM review articles (2024)
4. **"Ambient AI clinical documentation"** — [Abridge](https://abridge.com), [Nuance](https://nuance.com/healthcare/ambient-clinical-intelligence.html) validation studies
5. **["AI bias in EHR-based prediction models"](https://doi.org/10.1126/science.aax2342)** — Obermeyer et al. follow-ups

---

## Challenges

1. **Data quality** — EHR data is messy, incomplete, and inconsistently coded
2. **Interoperability** — Systems don't talk to each other well
3. **Bias** — Models trained on biased historical data perpetuate disparities
4. **Alert fatigue** — Too many AI alerts lead clinicians to ignore them all
5. **Privacy (HIPAA)** — Strict limits on using patient data for AI training
6. **Clinician trust** — Doctors skeptical of AI recommendations
7. **Validation** — Models degrade when deployed at new sites
8. **Vendor lock-in** — EHR vendors control data access
9. **Documentation burden** — AI may create more (lower quality) notes

---

## Open-Source Tools & Frameworks

| Tool | Purpose | Link |
|------|---------|------|
| OMOP CDM | Common data model for observational research | [OHDSI.org](https://ohdsi.org) |
| MIMIC-III | Critical care EHR dataset for research | [PhysioNet](https://physionet.org/content/mimiciii/1.4/) |
| MIMIC-IV | Critical care EHR dataset (updated) | [PhysioNet](https://physionet.org/content/mimiciv/2.2/) |
| eICU | Multi-center ICU dataset | [PhysioNet](https://physionet.org/content/eicu-crd/2.0/) |
| MedSpaCy | Medical NLP toolkit (Python) | [GitHub](https://github.com/medspacy/medspacy) |
| cTAKES | Clinical Text Analysis Knowledge Extraction | [Apache](https://ctakes.apache.org) |
| Synthea | Synthetic patient data generator | [GitHub](https://github.com/synthetichealth/synthea) |
| HAPI FHIR | Open-source FHIR server (Java) | [GitHub](https://github.com/hapifhir/hapi-fhir) |
| OpenMRS | Open-source medical record system | [OpenMRS.org](https://openmrs.org) |
| SciSpaCy | Scientific/biomedical NLP toolkit | [GitHub](https://github.com/allenai/scispacy) |
| LinuxForHealth | FHIR server and health data tools | GitHub |

---

## Future Directions

1. **Autonomous coding** — AI handles 90%+ of medical coding automatically
2. **Predictive health timelines** — AI-generated patient health forecasts
3. **Conversational EHR** — Talk to your EHR like talking to a colleague
4. **Zero-click documentation** — Ambient AI captures everything automatically
5. **Cross-institutional AI** — Models trained across hospital systems (federated)
6. **Patient-facing AI** — Patients interact with AI summaries of their records
7. **Continuous learning CDS** — Decision support that improves from outcomes
8. **EHR-integrated genomics** — Genomic data seamlessly in clinical workflow

---

*Sources: AMIA, JAMIA, NEJM, Epic/Cerner documentation, KLAS Research*
*Updated: February 2025*
