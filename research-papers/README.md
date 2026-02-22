# AI in Healthcare — Research Papers & Resources

## Overview

This section compiles the most important research papers, journals, conferences, open-source tools, datasets, and educational resources for AI in healthcare.

---

## Must-Read Papers (All-Time Top 50)

### Foundation Papers — Medical Imaging
| # | Paper | Authors | Journal | Year | Impact |
|---|-------|---------|---------|------|--------|
| 1 | Dermatologist-level classification of skin cancer with deep neural networks | Esteva et al. | Nature | 2017 | First AI vs dermatologist comparison |
| 2 | CheXNet: Radiologist-level pneumonia detection on chest X-rays | Rajpurkar et al. | arXiv | 2017 | Landmark radiology AI |
| 3 | Development and validation of a deep learning algorithm for detection of diabetic retinopathy | Gulshan et al. | JAMA | 2016 | Google's retinal AI |
| 4 | International evaluation of an AI system for breast cancer screening | McKinney et al. | Nature | 2020 | AI reduces false positives |
| 5 | nnU-Net: Self-adapting framework for U-Net-based medical image segmentation | Isensee et al. | Nature Methods | 2021 | Universal segmentation |
| 6 | Attention U-Net: Learning where to look for the pancreas | Oktay et al. | MIDL | 2018 | Attention in medical segmentation |
| 7 | RETFound: A foundation model for generalizable disease detection from retinal images | Zhou et al. | Nature | 2023 | Retinal foundation model |

### Foundation Papers — Clinical AI
| # | Paper | Authors | Journal | Year | Impact |
|---|-------|---------|---------|------|--------|
| 8 | Scalable and accurate deep learning with EHR data | Rajkomar et al. | npj Digital Medicine | 2018 | Google EHR AI |
| 9 | High-performance medicine: convergence of human and AI | Topol | Nature Medicine | 2019 | Seminal review |
| 10 | Deep Patient: unsupervised representation to predict patient future | Miotto et al. | Scientific Reports | 2016 | EHR deep learning |
| 11 | Cardiologist-level arrhythmia detection from ambulatory ECG | Hannun et al. | Nature Medicine | 2019 | Deep learning ECG |
| 12 | Dissecting racial bias in a clinical algorithm | Obermeyer et al. | Science | 2019 | AI bias landmark |
| 13 | ClinicalBERT: Modeling clinical notes and predicting readmission | Huang et al. | CHIL | 2020 | NLP for clinical notes |

### Foundation Papers — Drug Discovery
| # | Paper | Authors | Journal | Year | Impact |
|---|-------|---------|---------|------|--------|
| 14 | AlphaFold 2: Highly accurate protein structure prediction | Jumper et al. | Nature | 2021 | Nobel Prize 2024 |
| 15 | A deep learning approach to antibiotic discovery | Stokes et al. | Cell | 2020 | Halicin discovery |
| 16 | De novo design of protein structure and function with RFdiffusion | Watson et al. | Nature | 2023 | Protein design revolution |
| 17 | Molecular generation with diffusion models | Various | Multiple | 2023-24 | New paradigm in drug design |

### Foundation Papers — Genomics & Precision Medicine
| # | Paper | Authors | Journal | Year | Impact |
|---|-------|---------|---------|------|--------|
| 18 | A universal SNP and small-indel variant caller using deep neural networks | Poplin et al. | Nature Biotechnology | 2018 | DeepVariant |
| 19 | Deep learning for genomics | Zou et al. | Nature Genetics | 2019 | Review |
| 20 | Clinically applicable deep learning for diagnosis and referral in retinal disease | De Fauw et al. | Nature Medicine | 2018 | DeepMind retinal AI |

### Recent Breakthrough Papers (2024-2025)
| # | Paper | Authors | Journal | Year | Impact |
|---|-------|---------|---------|------|--------|
| 21 | Med-PaLM 2: Towards expert-level medical question answering | Google | Nature | 2024 | Medical LLM benchmark |
| 22 | AMIE: Conversational diagnostic AI | Google DeepMind | arXiv | 2024 | Outperformed physicians |
| 23 | AlphaFold 3: Structure prediction of biomolecular complexes | DeepMind | Nature | 2024 | Beyond proteins |
| 24 | BiomedCLIP: Multimodal biomedical foundation model | Microsoft | NeurIPS | 2024 | Biomedical vision-language |
| 25 | Generalist medical AI | Google DeepMind | Nature | 2024 | Multi-task medical AI |
| 26 | Foundation models for pathology | Various | Nature Medicine | 2024 | CONCH, UNI, Virchow |
| 27 | Large language models in medicine | Multiple | NEJM/Nature | 2024 | Comprehensive reviews |
| 28 | AI for multi-cancer early detection (Galleri) | GRAIL | Various | 2024 | MCED clinical data |
| 29 | SAM for medical imaging | Multiple adaptations | Various | 2024 | Medical segmentation |
| 30 | Autonomous surgical robots | Johns Hopkins/STAR | STM | 2024 | Autonomous suturing |

---

## Top Journals for Healthcare AI

### Tier 1 — Highest Impact
| Journal | Impact Factor | Focus |
|---------|--------------|-------|
| Nature Medicine | ~87 | Medical research including AI |
| The Lancet Digital Health | ~36 | Digital health and AI |
| NEJM (New England Journal of Medicine) | ~176 | Medicine (occasional AI) |
| Nature | ~64 | Breakthrough AI papers |
| Science | ~56 | Breakthrough AI papers |
| JAMA (Journal of the American Medical Association) | ~120 | Medicine with AI focus growing |
| Nature Biotechnology | ~46 | Biotech AI applications |
| Cell | ~64 | Biological AI applications |

### Tier 2 — AI/ML Focused Journals
| Journal | Focus |
|---------|-------|
| npj Digital Medicine | Digital health AI research |
| NEJM AI | Dedicated AI in medicine journal (new) |
| Nature Machine Intelligence | ML/AI methods |
| JAMA Network Open | Open access clinical AI |
| Medical Image Analysis | Medical imaging AI |
| Radiology: Artificial Intelligence | Radiology AI |
| Journal of Biomedical Informatics | Health informatics |
| JAMIA (Journal of AMIA) | Biomedical informatics |
| Artificial Intelligence in Medicine | AI healthcare methods |
| IEEE Journal of Biomedical and Health Informatics | Biomedical engineering AI |

---

## Top Conferences

| Conference | Focus | Frequency |
|-----------|-------|-----------|
| MICCAI | Medical image computing | Annual |
| CHIL (Conference on Health, Inference, and Learning) | Clinical ML | Annual |
| ML4H (Machine Learning for Health) | ML healthcare workshop | Annual (NeurIPS) |
| AMIA Annual Symposium | Biomedical informatics | Annual |
| HIMSS | Health information technology | Annual |
| RSNA AI Showcase | Radiology AI | Annual |
| NeurIPS (health tracks) | ML/AI with health sessions | Annual |
| ICML (health tracks) | ML with health sessions | Annual |
| AAAI Health Intelligence Workshop | AI health applications | Annual |
| IEEE EMBC | Biomedical engineering | Annual |
| ISBI | Biomedical imaging | Annual |

---

## Open-Source Datasets

### Clinical / EHR Datasets
| Dataset | Description | Size | Access |
|---------|-------------|------|--------|
| MIMIC-III | ICU patient data (Beth Israel) | 46K+ patients | PhysioNet (credentialed) |
| MIMIC-IV | Updated ICU data + ED data | 300K+ patients | PhysioNet (credentialed) |
| eICU | Multi-center ICU data | 200K+ stays | PhysioNet (credentialed) |
| MIMIC-CXR | Chest X-rays with reports | 377K images | PhysioNet (credentialed) |
| CheXpert | Chest X-ray classification | 224K images | Stanford (application) |
| PhysioNet Challenge datasets | Various clinical challenges | Varies | PhysioNet (open) |

### Imaging Datasets
| Dataset | Modality | Size | Task |
|---------|----------|------|------|
| NIH ChestX-ray14 | Chest X-ray | 112K images | Multi-label classification |
| BraTS | Brain MRI | 2000+ scans | Glioma segmentation |
| ISIC Archive | Dermoscopy | 70K+ images | Skin lesion classification |
| Camelyon16/17 | Pathology (WSI) | 400+ slides | Metastasis detection |
| TotalSegmentator | CT | 1200+ scans | 117 structures |
| LUNA16 | Lung CT | 888 scans | Nodule detection |
| EyePACS | Fundus photos | 88K images | Diabetic retinopathy |
| RSNA datasets | Various radiology | Varies | Annual challenges |
| DeepLesion | CT | 32K lesions | Universal lesion detection |
| ACDC | Cardiac MRI | 150 patients | Cardiac segmentation |

### Genomics Datasets
| Dataset | Description | Access |
|---------|-------------|--------|
| TCGA (The Cancer Genome Atlas) | Pan-cancer genomic data | NCI GDC |
| gnomAD | Population genetic variation | Open |
| ClinVar | Clinically relevant variants | NCBI (open) |
| UK Biobank | 500K participants, multi-omics | Application |
| GTEx | Gene expression across tissues | Open |

---

## Open-Source Tools & Frameworks

### Medical Imaging
| Tool | Purpose | Language |
|------|---------|----------|
| MONAI | Medical image AI framework | Python (PyTorch) |
| nnU-Net | Self-adapting segmentation | Python (PyTorch) |
| TorchIO | Medical image preprocessing | Python (PyTorch) |
| SimpleITK | Image processing | Python/C++ |
| 3D Slicer | Medical image visualization | C++/Python |
| ITK-SNAP | Image segmentation | C++ |
| OpenSlide | Whole slide image reading | C/Python |

### Clinical NLP
| Tool | Purpose | Language |
|------|---------|----------|
| MedSpaCy | Medical NLP toolkit | Python |
| SciSpaCy | Biomedical NLP | Python |
| cTAKES | Clinical text extraction | Java |
| MetaMap | Biomedical concept recognition | Java |
| Stanza (biomedical) | Neural NLP pipeline | Python |
| ClinicalBERT | Clinical text embeddings | Python (HuggingFace) |
| GatorTron | Large clinical LM | Python |

### Drug Discovery
| Tool | Purpose | Language |
|------|---------|----------|
| RDKit | Cheminformatics | Python/C++ |
| DeepChem | Deep learning for chemistry | Python |
| Open Babel | Chemical format conversion | C++/Python |
| AutoDock Vina | Molecular docking | C++ |
| OpenMM | Molecular dynamics | Python/C++ |
| TorchDrug | ML for drug discovery | Python |
| DGL-LifeSci | Graph neural networks for molecules | Python |

### EHR / Clinical
| Tool | Purpose | Language |
|------|---------|----------|
| HAPI FHIR | FHIR server implementation | Java |
| OMOP CDM | Common data model | SQL/R/Python |
| Synthea | Synthetic patient generator | Java |
| OpenMRS | Open-source medical records | Java |
| OHDSI tools | Observational health analytics | R/SQL |

---

## Learning Resources

### Online Courses
| Course | Platform | Focus |
|--------|----------|-------|
| AI for Medicine Specialization | Coursera (Andrew Ng) | Medical imaging, EHR, treatment |
| Deep Learning for Healthcare | MIT OCW | Clinical deep learning |
| Biomedical Data Science | Stanford Online | Health data analysis |
| Machine Learning for Healthcare | Georgia Tech | Clinical ML methods |
| AI in Healthcare | Google (Coursera) | Google Health approaches |

### Textbooks
| Book | Authors | Topics |
|------|---------|--------|
| Deep Medicine | Eric Topol | AI transforming healthcare |
| The Patient Will See You Now | Eric Topol | Digital health revolution |
| Artificial Intelligence in Healthcare | Adam Bohr, Kaveh Memarzadeh | Comprehensive AI healthcare |
| Machine Learning for Healthcare | Multiple | Technical ML for health |
| Deep Learning for Medical Image Analysis | Zhou et al. | Medical imaging deep learning |

### YouTube Channels
| Channel | Content Type |
|---------|-------------|
| Two Minute Papers | AI research summaries |
| Stanford HAI | Healthcare AI talks |
| Google Health | Product demos, research |
| NVIDIA Healthcare | Clara platform, MONAI tutorials |
| MIT CSAIL | Health AI research talks |
| RSNA (official) | Radiology AI presentations |
| Andrew Ng (deeplearning.ai) | AI for Medicine course content |

---

## Key Organizations & Initiatives

| Organization | Focus |
|-------------|-------|
| Stanford HAI | AI research and policy |
| MIT CSAIL (Clinical ML) | Clinical machine learning |
| Google Health | Commercial health AI |
| Microsoft Health AI | Azure health AI solutions |
| NIH AIM-AHEAD | AI/ML equity in health |
| WHO AI for Health | Global health AI guidance |
| FDA Digital Health CoE | Medical AI regulation |
| Coalition for Health AI (CHAI) | Standards for health AI |
| OHDSI | Observational health data science |
| AMIA | Biomedical informatics community |

---

*This resource list is continuously updated. Contributions welcome.*
*Updated: February 2025*
