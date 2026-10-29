# Anant Gupta

**AI Engineer & Researcher · Trustworthy medical AI · Biometrics**
Gurugram, India · Prospective Fall 2027 research master's / PhD applicant

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-profile-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=8EUDt24AAAAJ)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-anantgp-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anantgp)
<!-- Add your email badge here: [![Email](https://img.shields.io/badge/Email-contact-D14836?logo=gmail&logoColor=white)](mailto:YOUR_EMAIL) -->

I build and evaluate AI systems for healthcare and biometrics, with a focus on outputs that can be traced, audited and honestly reported. Long term, I want to work on trustworthy medical AI for neurological disease, including neural-signal decoding to help non-speaking people communicate.

---

## Highlights

- 🥇 **1st place, StepUP 2026** (IJCB 2026 biometric footstep recognition), 8.00% EER. Second author of the challenge summary paper.
- 🥉 **3rd place, IJCB-AFMFR 2026** Limited Data Track (face recognition with synthetic training data).
- 📄 **Springer publication**, ICICCT 2025 (LNNS vol. 1664).
- 🏥 **Production clinical LLM work**: discharge-summary pipeline for a healthcare client, validated on a 669-test suite.
- Co-author on **six IJCB 2026 competition papers** across footstep, face, sclera, ear, morphing-attack and liveness detection, plus one Springer paper.

---

## Research interests

| Area | Topics |
|---|---|
| **Healthcare AI** | Clinical information extraction, terminology grounding (SNOMED CT, UMLS, MedDRA), evidence traceability, medical AI evaluation |
| **Biometrics** | Footstep recognition, face and ear recognition, sclera segmentation, morphing-attack detection |
| **Interoperability & multimodal ML** | FHIR R4, structured clinical records, speech and audio models |

---

## Selected research and projects

### StepUP 2026 · Footstep biometrics · 🥇 1st place
Spatiotemporal CNN with score fusion for paired pressure footsteps. 8.00% EER on the competition evaluation.
[Paper (arXiv:2607.13905)](https://arxiv.org/abs/2607.13905) · [Team code](https://github.com/AnantG5/STEP-UP)
<sub>Competition data and model checkpoints are not included in the repository.</sub>

### Clinical LLM engineering · Discharge summaries
Llama 3.1 70B with chain-of-thought and few-shot prompting to draft clinical discharge summaries for a healthcare client, validated on a 669-test suite. Stack: GCP, Whisper, MedGemma, SNOMED CT / UMLS / MedDRA.
<sub>Client code, data and identifying details are confidential.</sub>

### MediLipi · Clinical evidence mapping · *manuscript in preparation*
Reference-constrained transformation of clinical-conversation information into auditable evidence for a **frozen population Bayesian network**. The mapping does not discover causal structure. Research code is private.

### Cross-Border IPS AI Agent · HL7 AI Challenge 2026
Team prototype that turns **synthetic** clinical reports into terminology-mapped FHIR R4 International Patient Summary bundles with supporting evidence. Evaluated on synthetic data only, not clinically validated.
[Repository](https://github.com/AnantGp/crossroad-fhir-link)

### BioDCASE · Cross-domain audio classification
Mosquito-species recognition across recording domains. I reviewed the literature, designed the spectrogram structure, developed the approach and contributed code. Reported baseline figures are not a final team score.
[Repository](https://github.com/AnantGp/mosquito123)

### Medivaanii · Medical report and voice MVP
Research prototype for report reading and multilingual voice interaction. Uses external services and is **not clinically validated**; the repository documents its privacy limitations.
[Repository](https://github.com/AnantGp/medvaani)

---

## Publications and competition papers

7 papers: 1 published (Springer) and 6 IJCB 2026 competition papers. Each is listed at its current status.

**Published**
1. **Analytical Approach of False Products and Complaint System Development Using Blockchain Technology.** Gupta, A., Pavan Sai, A. and Dubey, S.K. *ICICCT 2025*, Lecture Notes in Networks and Systems vol. 1664, Springer, 2026.
   [DOI](https://doi.org/10.1007/978-3-032-08600-6_1) · [Springer](https://link.springer.com/chapter/10.1007/978-3-032-08600-6_1)

**Accepted at IJCB 2026 (preprints available)**

2. **The 2nd International StepUP Competition for Biometric Footstep Recognition: From Steps to Strides.** Second author. 🥇 Team placed **1st**, best EER 8.00%.
   [arXiv:2607.13905](https://arxiv.org/abs/2607.13905)
3. **Competition on Adapting Foundation Models for Face Recognition Using Synthetic Training Data (IJCB-AFMFR 2026).** Co-author (competition participant). 🥉 Team placed **3rd** in the Limited Data Track.
   [arXiv:2607.24422](https://arxiv.org/abs/2607.24422) · [PDF](https://publications.idiap.ch/attachments/papers/2026/OtroshiShahreza_IJCB-2_2026.pdf)

**IJCB 2026 competition papers (presented; final proceedings pending)**

4. **Every Frame You Take: The Video-based Morphing Attack Detection Challenge (V-MAD).** Co-author. Quality-aware dual-branch late fusion: EfficientNet-B0 artifact branch plus ArcFace identity branch with OFIQ frame filtering.
   [PDF](https://publications.idiap.ch/attachments/papers/2026/N.Di%20Domenico%20L.%20Pellegrini%20S.%20M.%20La%20Cava%20et%20al.%20Every%20Frame%20You%20Take%20The%20%20%20Video-based%20Morphing%20Attack%20Detection%20Challenge.%20IJCB-Challegen%20Report%202026..pdf)
5. **Label-Efficient Sclera Segmentation with Foundation Models: SSBC 2026.** Co-author. SAM-LoRA and DINOv2 team entries.
   [PDF](https://lmi.fe.uni-lj.si/wp-content/uploads/2026/09/IJCB_SSBC_2026.pdf)
6. **The Unconstrained Ear Recognition Challenge 2026: Size Matters (UERC).** Co-author. ConvNeXt + ArcFace entry.
   [Author record](https://www.croris.hr/crosbi/publikacija/prilog-skup/964273)
7. **LivDet-Face 2026: Face Liveness Detection Competition.** Co-author (team CosmicFace).
   [Competition report](https://face2026.livdet.org/files/livdet-face-2026-report.pdf)

**In preparation**
- MediLipi: reference-constrained clinical evidence mapping for a frozen population Bayesian network.

---

## Background

**B.Tech., Computer Science and Engineering**, Amity University Uttar Pradesh (Noida), 2025
**AI Engineer**, ArogyaPandit Private Limited, Gurugram

`Python` `PyTorch` `LLMs` `Whisper` `Google Cloud` `FHIR R4` `SNOMED CT` `UMLS` `MedDRA` `Bayesian networks`
