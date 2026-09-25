# Datasets

| Dataset | Source | Description | Link |
| --- | --- | --- | --- |
| MedQA (USMLE) | Jin et al., 2021 | Multiple-choice US medical licensing exam questions; the core benchmark used by MedAgents, MDAgents, and AgentClinic-MedQA to test multi-agent clinical reasoning | [GitHub](https://github.com/jind11/MedQA) |
| PubMedQA | Jin et al., 2019 | Biomedical research question-answering dataset built from PubMed abstracts; used as one of the nine MedAgents evaluation benchmarks | [GitHub](https://pubmedqa.github.io/) |
| MIMIC-IV | Johnson et al., PhysioNet | De-identified real-world ICU/EHR data; underlies the AgentClinic-MIMIC-IV case suite used to test multi-agent clinical agents on real clinical narratives (requires PhysioNet credentialed access) | [PhysioNet](https://physionet.org/content/mimiciv/2.2/) |
| AgentClinic benchmark suite (MedQA / NEJM / MIMIC-IV extensions) | Schmidgall et al., 2024 | Interactive multi-agent clinical simulation cases (dialogue-only and multimodal) spanning 9 specialties and 7 languages, purpose-built for evaluating multi-agent clinical decision systems | [GitHub](https://github.com/SamuelSchmidgall/AgentClinic) |

## Note on oncology-specific patient-level datasets

No open, de-identified dataset of real multidisciplinary tumor board deliberations or recommendations was found during this search — most of the applied virtual-tumor-board papers above (JCO CCI 2026, VISTA Architect, TumorBoard neuro-oncology) evaluate against institution-held clinical guideline sets or internal patient cohorts (e.g. Stanford's thoracic tumor board records) that are not publicly released. The datasets listed above are the closest open, verifiable substitutes for benchmarking multi-agent clinical reasoning in this domain.
