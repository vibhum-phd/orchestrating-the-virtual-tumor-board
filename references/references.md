# References

All entries below were independently verified against a primary scholarly source (journal publisher page, PubMed/PMC, arXiv abstract page, ACL Anthology, or NeurIPS proceedings) before being added here. Author lists reflect the verified primary source, not the AI-generated draft where the two differed — see `citation-audit/Citation_Integrity_Audit.pdf` for the full correction log on the 7 references that came from the AI-generated paper.

## Foundational Multidisciplinary Tumor Board (MDT) Literature

- **Tumour boards and their quality of structures, processes, and team performance in multidisciplinary cancer care: a systematic review**
  2026 systematic review, published in a Springer/BMC journal
  [Paper](https://link.springer.com/article/10.1186/s12913-026-14447-9)
  Synthesizes 97 studies on MDT structure and process quality — the baseline "why tumor boards matter" evidence this repo's AI systems are trying to replicate/augment.

- **Process quality of decision-making in multidisciplinary cancer team meetings: a structured observational study**
  Published in *PMC* (observational study)
  [Paper (PMC5693525)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5693525/)
  Directly measures the process quality of real human MDT meetings — a useful benchmark for what an AI-orchestrated virtual board should be measured against.

- **Higher number of multidisciplinary tumor board meetings per case leads to improved clinical outcome**
  *BMC Cancer*, 2020
  [Paper](https://bmccancer.biomedcentral.com/articles/10.1186/s12885-020-06809-1)
  Matched-pair analysis (454 patients, 66 tumor types) linking MDT frequency to overall survival — establishes the clinical stakes of scaling tumor board access, which VTBs and AI orchestration aim to address.

- **The impact of tumor board on cancer care: evidence from an umbrella review**
  [Paper (PMC6995197)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6995197/)
  Umbrella review of 5 reviews (147 underlying studies) on how tumor board discussion changes diagnosis, treatment, and survival outcomes.

- **Virtual multi-institutional tumor board: a strategy for personalized diagnoses and management of rare CNS tumors**
  Rogers, Wall, Acquaye-Mallory, et al. — *Journal of Neuro-Oncology*, 2024
  [Paper (DOI: 10.1007/s11060-024-04613-6)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11023967/)
  A non-AI virtual (human-to-human, telecommunication-based) tumor board for rare CNS tumors — the direct institutional predecessor of the AI-orchestrated systems below.

## Foundational Multi-Agent AI Frameworks

- **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework**
  Wu, Bansal, Zhang, Wu, Zhang, Zhu, Li, Jiang, Zhang, Wang — Microsoft Research, COLM 2024
  [Paper (arXiv:2308.08155)](https://arxiv.org/abs/2308.08155)
  The general-purpose multi-agent conversation framework most tumor-board-style clinical systems (including several below) are built on top of.

- **MedAgents: Large Language Models as Collaborators for Zero-shot Medical Reasoning**
  Tang, Zou, Zhang, Li, Zhao, Zhang, Cohan, Gerstein — Findings of ACL 2024
  [Paper (arXiv:2311.10537)](https://arxiv.org/abs/2311.10537)
  Introduces role-playing, multi-round LLM agent collaboration for medical QA — the direct conceptual ancestor of "tumor-board-style" LLM agent debate.

- **MDAgents: An Adaptive Collaboration of LLMs for Medical Decision-Making**
  Kim, Park, Jeong, Chan, Xu, McDuff, Lee, Ghassemi, Breazeal, Park — NeurIPS 2024
  [Paper (arXiv:2404.15155)](https://arxiv.org/abs/2404.15155)
  Dynamically assigns solo vs. group (MDT-style) LLM collaboration structure based on case complexity — directly emulates real-world tiered clinical decision-making.

## Evaluation and Benchmarks

- **AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments**
  Schmidgall, Ziaei, Harris, Reis, Jopling, Moor — 2024
  [Paper (arXiv:2405.07960)](https://arxiv.org/abs/2405.07960)
  Interactive, multi-agent (doctor/patient/measurement/moderator) benchmark across 9 specialties — the most relevant existing benchmark methodology for evaluating a multi-agent virtual tumor board.

- **MTBBench: A Multimodal Sequential Clinical Decision-Making Benchmark in Oncology**
  2025
  [Paper (arXiv:2511.20490)](https://arxiv.org/pdf/2511.20490)
  A sequential, oncology-specific clinical decision-making benchmark — directly measures the kind of longitudinal reasoning a virtual tumor board must perform.

## Applications: AI-Orchestrated Virtual Tumor Boards & Multi-Agent Oncology Systems

- **Virtual oncology collaborative tumor board using multiple artificial intelligence agents**
  Wang, Mullick Chowdhury, Nazha — *Journal of Clinical Oncology* 43, 1563 (2025 ASCO Annual Meeting abstract)
  [Paper (DOI: 10.1200/JCO.2025.43.16_suppl.1563)](https://ascopubs.org/doi/10.1200/JCO.2025.43.16_suppl.1563)
  Three-agent (Coordinator, PDF Viewer, Reviewer) AutoGen-based system for answering guideline-based questions like a tumor board would — 88% answer accuracy.

- **Tumor Board–Inspired Multiagent Artificial Intelligence System for Interpreting Oncology Guidelines**
  *JCO Clinical Cancer Informatics*, January 2026
  [Paper (DOI: 10.1200/CCI-25-00286)](https://ascopubs.org/doi/10.1200/CCI-25-00286)
  Full peer-reviewed follow-up to the abstract above: 94% guideline-selection accuracy and 90% answer accuracy across 34 ASCO guidelines, outperforming GPT-4o, Claude 3.7, Gemini 2.5, and DeepSeek-R1.

- **Development, Evaluation, and Deployment of a Multi-Agent System for Thoracic Tumor Board**
  Ellis-Caleo, Keyes, Ambers, Bekheet, Yim, Kotecha, Shah, Neal — Stanford Medicine, 2026
  [Paper (arXiv:2604.12161)](https://arxiv.org/abs/2604.12161)
  Reports a real clinical deployment (not just a benchmark) of AI chart-summarization for a live thoracic tumor board, with post-deployment monitoring.

- **VISTA Architect: A graph database-oriented health AI system demonstrated in multidisciplinary tumor boards**
  Stanford Medicine, 2026
  [Paper (arXiv:2606.22692)](https://arxiv.org/abs/2606.22692)
  96.4% accuracy on tumor-board-salient variables across 1,180 patients; reduced case-prep time to ~2.2 minutes — a graph-database backend for agentic tumor board preparation.

- **TumorBoard: Evidence-Grounded Multi-Agent Decision Support for Longitudinal Neuro-Oncology**
  2026
  [Paper (arXiv:2608.03190)](https://arxiv.org/abs/2608.03190)
  Specialist agents (radiology, neuropathology, molecular diagnosis, guidelines, therapy planning) plus an adversarial critic and a safety governor — directly addresses the accountability/deferral concerns raised in this repo's own AI paper.

- **Artificial intelligence-driven virtual tumor board enhances precision care in myelodysplastic syndromes**
  medRxiv preprint, 2026
  [Paper](https://www.medrxiv.org/content/10.64898/2026.03.26.26349088.full.pdf)
  Compares 4 general-purpose LLMs against a rule-bound, guideline-grounded multi-agent "Virtual MDS Panel" across 30 cases, rated by 9 blinded international experts.

- **Simulating a virtual tumor board with large language models: a pilot study in NSCLC patients receiving immunotherapy**
  Ismayilov, Altundag, Akcali — *Immunotherapy*, 2025
  [Paper (DOI: 10.1080/1750743X.2025.2580272, PMID: 41190886)](https://pubmed.ncbi.nlm.nih.gov/41190886/)
  Pilot clinical study simulating a full tumor board discussion with LLMs for immunotherapy decisions in non-small-cell lung cancer.

- **EvoMDT: a self-evolving multi-agent system for structured clinical decision-making in multi-cancer**
  Liu, Hu, Huang, Niu, Zhang, Ma, Lin, Huat, Kwon, Gao, Sun, Ying, Qiang — *npj Digital Medicine* 9(1), 124 (2026)
  [Paper (DOI: 10.1038/s41746-025-02304-8)](https://doi.org/10.1038/s41746-025-02304-8)
  One of the 7 references from this repo's AI-generated paper — full author list and venue restored per the Lab 1 citation audit (the AI's draft dropped 12 of 13 authors and omitted the venue/DOI entirely).

## Corrected References From the AI-Generated Paper (Audited in Lab 1)

- **Enhancing Adoption and Utility of Virtual Tumor Boards: Impact on Community and Rural Oncology Practices**
  Powell et al. — *JCO Oncology Practice* 17(6), e809–e816 (2021)
  [Paper (DOI: 10.1200/OP.20.00480, PMID: 33031011)](https://doi.org/10.1200/OP.20.00480)
  Fully verified (Code A) in the Lab 1 audit — all authors, year, journal, and identifier matched exactly.

- **The Emergence of Virtual Tumor Boards in Neuro-Oncology: Opportunities and Challenges**
  Ekhator, Kesari, Tadipatri, Fonkem, Grewal — *Cureus* 14(6):e25682 (2022)
  [Paper (DOI: 10.7759/cureus.25682, PMID: 35677741)](https://doi.org/10.7759/cureus.25682)
  Fully verified (Code A) in the Lab 1 audit.

- **National Cancer Grid Virtual Tumor Boards of Head and Neck Cancers: An Innovative Approach to Multidisciplinary Care**
  Thiagarajan, Poojari, Tuljapurkar, et al. — *JCO Global Oncology* 9:e2200348 (2023)
  [Paper (DOI: 10.1200/GO.22.00348, PMID: 36706349)](https://doi.org/10.1200/GO.22.00348)
  Fully verified (Code A) in the Lab 1 audit; demonstrates VTBs scaled nationally in India.

- **The Fidelity of Artificial Intelligence to Multidisciplinary Tumor Board Recommendations for Patients with Gastric Cancer: A Retrospective Study**
  Park, Chae — *Journal of Gastrointestinal Cancer* 55(1):365–372 (2024, epub 2023)
  [Paper (DOI: 10.1007/s12029-023-00967-8, PMID: 37702851)](https://doi.org/10.1007/s12029-023-00967-8)
  Fully verified (Code A) in the Lab 1 audit.

- **Artificial intelligence in multidisciplinary tumor boards enhancing decision making and clinical outcomes in oncology**
  Wang, Q., Ding, G., Wang, J., Tang, Y., Feng, Y., et al. — *iScience*, 2025
  [Paper (DOI: 10.1016/j.isci.2025.114082)](https://doi.org/10.1016/j.isci.2025.114082)
  Real paper (Code B in the Lab 1 audit): the AI's draft listed only 1 of 6 authors and omitted the year, journal, and DOI entirely. Full authorship and venue restored here.

- **Multidisciplinary tumor board decisions and artificial intelligence-generated recommendations in general surgery: a retrospective observational study**
  Deniz, A.Z., et al. — *Updates in Surgery*, 2026 (PMID 42377710)
  [Paper (DOI: 10.1007/s13304-026-02749-w)](https://doi.org/10.1007/s13304-026-02749-w)
  Real paper (Code B in the Lab 1 audit): the AI's draft listed only 1 of 8 authors and omitted the year, journal, and DOI entirely. Full authorship and venue restored here.
