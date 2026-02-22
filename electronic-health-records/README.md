# AI in Electronic Health Records (EHR)

## Overview

AI in EHR systems transforms how clinical data is captured, analyzed, and used for decision-making. From automating documentation to predicting patient deterioration, AI is embedded across the entire EHR workflow — reducing clinician burnout and improving patient outcomes.

**Market Size:** Clinical AI/EHR intelligence — $4.5B (2024) → projected $18.7B by 2030

---

## Key Applications

### 1. Clinical Documentation AI (Ambient AI)

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Ambient clinical intelligence | AI listens to patient-doctor conversations, auto-generates notes | Nuance DAX Copilot, Abridge, Suki | 50-70% reduction in documentation time |
| Medical transcription | Convert dictated notes to structured text | Nuance Dragon Medical, 3M M*Modal | 95%+ accuracy |
| Clinical note generation | Generate structured SOAP notes from conversations | Abridge, Nabla, DeepScribe | Reduces burnout |
| Coding assistance | Auto-suggest ICD-10, CPT codes | 3M CodeFinder, Nym Health, AGS Health | 30-40% faster coding |
| Prior authorization automation | Auto-generate prior auth requests | Olive AI, Cohere Health | Reduces denials |

### 2. Clinical Decision Support (CDS)

| Application | Description | Key Players | Status |
|------------|-------------|-------------|--------|
| Sepsis prediction | Early warning 4-12 hours before onset | Epic Sepsis Model, CLEW Medical | Deployed (varied results) |
| Patient deterioration | Predict ICU transfer, cardiac arrest | Dascena, PeraHealth (Rothman Index) | Clinical use |
| Readmission prediction | 30-day readmission risk scoring | Jvion, Health Catalyst | CMS-incentivized |
| Drug interaction checking | AI-enhanced interaction analysis | FDB (First Databank), Medi-Span | Standard in EHRs |
| Diagnostic assistance | Suggest differential diagnoses | Isabel Healthcare, Glass Health, DXplain | Clinical support |
| Treatment recommendations | Evidence-based treatment suggestions | UpToDate (Wolters Kluwer), DynaMed | Clinical use |

### 3. Population Health AI

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Risk stratification | Identify high-risk patients | Jvion, Arcadia, Health Catalyst | 15-30% cost reduction |
| Care gap identification | Find patients missing preventive care | Innovaccer, Lightbeam Health | Improved quality metrics |
| Social determinants (SDOH) | Analyze social factors affecting health | Socially Determined, UniteUs | Better outcomes targeting |
| Chronic disease management | Predict disease progression | Livongo (Teladoc), Glooko | Improved A1C, BP control |

### 4. Revenue Cycle Management AI

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Claims denial prediction | Predict which claims will be denied | Waystar, Change Healthcare | 25% fewer denials |
| Auto-coding | AI-suggested medical codes | Nym Health, AGS Health, 3M | Faster, more accurate |
| Charge capture | Identify missed charges | AKASA, Olive AI | 5-10% revenue recovery |
| Payment prediction | Predict patient payment behavior | Cedar, Collectly | Better collection rates |

### 5. Natural Language Processing (NLP) for EHR

| Application | Description | Key Players | Impact |
|------------|-------------|-------------|--------|
| Unstructured data extraction | Extract info from clinical notes | Amazon Comprehend Medical, Google | Unlock 80% of EHR data |
| Clinical trial matching | Match patients to trials from EHR data | Tempus, Deep 6 AI, TriNetX | 50% faster enrollment |
| Named entity recognition | Identify medications, conditions, procedures | MedSpaCy, SciSpaCy, cTAKES | Research tool |
| Sentiment analysis | Detect patient distress in notes | Research stage | Mental health applications |
| Summarization | Condense long patient histories | Google Med-PaLM, Epic AI | Reduce information overload |

---

## Major EHR Vendors & AI Integration

### Big EHR AI Features
| Vendor | Market Share (US) | AI Features |
|--------|------------------|-------------|
| Epic Systems | ~38% | Cognitive Computing, Sepsis Model, Hey Epic!, AI-generated summaries, ambient documentation partnership with Nuance |
| Oracle Health (Cerner) | ~22% | Oracle AI, Clinical AI, Autonomous coding |
| MEDITECH | ~16% | Google Cloud AI integration, Ambient Scribe |
| Veradigm (Allscripts) | ~5% | AI analytics, population health |
| athenahealth | ~5% | AI denial management, document classification |
| eClinicalWorks | ~5% | healow AI assistant |

### AI-Native EHR/Clinical Platforms
| Company | Focus | Notable |
|---------|-------|---------|
| Abridge | Ambient clinical intelligence | Raised $200M+, partners with Epic |
| Suki | AI voice assistant for doctors | 70% reduction in note-taking time |
| Nabla | AI copilot for clinicians | European leader in ambient AI |
| DeepScribe | Ambient AI scribe | Deployed across 150+ specialties |
| Glass Health | AI diagnostic/treatment support | LLM-powered differential diagnosis |
| Elation Health | AI-native primary care EHR | Built-in AI documentation |
| Canvas Medical | API-first EHR with AI | Developer-friendly health record |

---

## LLMs in EHR — The New Frontier

### Medical LLMs
| Model | Developer | Capability | Status |
|-------|-----------|-----------|--------|
| Med-PaLM 2 | Google | Medical question answering, 86.5% on USMLE | Research |
| GPT-4 (medical fine-tuned) | OpenAI | Clinical note generation, coding | Via partners |
| Meditron | EPFL | Open-source medical LLM | Open source |
| BioMistral | Various | Biomedical text understanding | Open source |
| ClinicalBERT | MIT | EHR text embeddings | Open source |
| GatorTron | UF Health | Large clinical language model | Research |
| Nuance DAX Copilot | Microsoft/Nuance | Ambient clinical documentation | Production |

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
| HL7 FHIR | Modern API for health data exchange | Mandated in US (21st Century Cures) |
| SNOMED CT | Clinical terminology | International standard |
| ICD-10/ICD-11 | Disease classification | Global (ICD-11 adopted 2022) |
| LOINC | Lab and observation codes | Global standard |
| CPT | Procedure codes | US standard |
| RxNorm | Medication terminology | US standard |
| DICOM | Medical imaging standard | Global standard |

### Interoperability Initiatives
- **TEFCA** — Trusted Exchange Framework (US national health data exchange)
- **SMART on FHIR** — Apps framework for EHR integration
- **CDS Hooks** — Clinical decision support integration standard
- **Bulk FHIR** — Population-level data access
- **International Patient Summary** — Cross-border patient records

---

## Research Papers (Must-Read)

### Foundational
1. **"Scalable and accurate deep learning for EHR"** — Rajkomar et al. (2018) — Google/UCSF
2. **"Deep Patient: An unsupervised representation of EHR data"** — Miotto et al. (2016) — Nature Scientific Reports
3. **"ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission"** — Huang et al. (2020)
4. **"GatorTron: A Large Clinical Language Model"** — Yang et al. (2022)
5. **"Foresight: Generative Pretrained Transformer for EHR"** — Li et al.

### Recent (2024-2025)
1. **"Med-PaLM 2: Towards Expert-Level Medical Question Answering"** — Google (2024)
2. **"LLMs for Clinical Note Generation"** — Nuance/Microsoft publications
3. **"Large language models in medicine"** — NEJM review articles (2024)
4. **"Ambient AI clinical documentation"** — Abridge, Nuance validation studies
5. **"AI bias in EHR-based prediction models"** — Obermeyer et al. follow-ups

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
| OMOP CDM | Common data model for observational research | OHDSI.org |
| MIMIC-III/IV | Critical care EHR dataset for research | PhysioNet |
| eICU | Multi-center ICU dataset | PhysioNet |
| MedSpaCy | Medical NLP toolkit (Python) | GitHub |
| cTAKES | Clinical Text Analysis Knowledge Extraction | Apache |
| Synthea | Synthetic patient data generator | GitHub |
| HAPI FHIR | Open-source FHIR server (Java) | GitHub |
| OpenMRS | Open-source medical record system | OpenMRS.org |
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
