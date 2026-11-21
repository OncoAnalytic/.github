![OncoAnalytic: AI-Guided Patient Stratification](onco-cover.png)

At OncoAnalytic, we develop AI-guided patient stratification that turns molecular and clinical test results into ranked, patient-specific drug regimens. Our platform, OncoAgent, is a multi-agent AI system that coordinates medical models and general-purpose LLMs through multiple rounds of analysis and cross-review. Our own biology-based prompting guides the agents toward drug combinations that address resistance mechanisms with minimal toxicity.

We have prepared reports for patients using results from clinical laboratories and medical centers, covering tumor DNA and RNA sequencing, liquid biopsy, proteomics, immunomics and pharmacogenomics, and treating physicians used them prospectively when choosing therapies. We believe patient treatments are consistently needlessly toxic; in glioblastoma, mild non-cancer drugs can be very impactful, and this is likely the case in other tumor types as well.

"I met my match - her name was [Flo](https://github.com/FlowAnalytic)."

Our strategy is derived from fundamental research. We connect genomics with cell function, because clinical live-cell imaging provides information that can never be obtained by sequencing. [FlowAnalytic](https://github.com/FlowAnalytic), our quantitative live-cell imaging software, builds on more than 20 years of work in quantitative microscopy. It measures microtubule, actin and focal-adhesion dynamics, cell division and migration in patient-derived cells and organoids during drug exposure, revealing drug-response and resistance phenotypes. Tim Mitchison provided examples of the need for imaging to dissect the immune response.

[FlowAnalytic](https://github.com/FlowAnalytic) measures movement across cellular and subcellular systems:

- **Cells and organoids:** live cells and patient-derived cancer organoids, including drug responses, cell division, and wound healing.
- **Cytoskeleton:** microtubule polymerization, shortening, and pausing; actin flows; and focal-adhesion dynamics involving vinculin and paxillin.
- **Axonal transport:** movement of mitochondria, lysosomes, and extracellular vesicles, including motile fraction, anterograde and retrograde velocities, run lengths, and pauses.
- **Nuclear dynamics:** transcription-factor and nucleoporin dynamics, nuclear-envelope bending and contraction, and nuclear import and export.
- **Chromatin and signaling:** histone reorganization after drug treatment and live-cell surface-receptor activity.

The same tracking technology also runs inside CO₂ incubators to measure drug effects on patient cells in a hospital setting.

RIT1, a RAS-related GTPase, is essential for timely progression through mitosis and proper chromosome segregation, suggesting targeting of RIT1 in cancer. PAK1 is an effector of RIT1, and RIT1 directly interacts with the Rho GTPases Cdc42 and Rac1. We reported new measurements of PAK-inhibited cells expressing constitutively active Rac1(Q61L) that demonstrated a molecular machinery, not previously described in the literature, based on contractility in the lamella of migrating cells, which can be exploited in the clinic. Our computational analysis measured for the first time a retrograde F-actin network and a contractile meshwork of overlapping anterograde and retrograde flows in the lamella. In addition, we detected a third, occasionally appearing, fast retrograde flow in the thin area of remaining lamellipodia in PAK-inhibited cells. RIT1 is distributed in the cytoplasm as cells enter mitosis and progress through metaphase, but rapidly translocates to the plasma membrane during anaphase. In contrast, the pathogenic RIT1 SGL variant is not displaced from the membrane, as the McCormick lab demonstrated with images. Image analysis of F-actin and microtubule polymerization dynamics in patient cells can dissect the molecular mechanisms of cellular organization in the presence of pathogenic levels of RIT1 and tailor RAS-targeting therapies to the individual. The 3D diffusion of RIT1 between the plasma membrane and the cytoplasm during mitosis can serve as a biomarker of drug efficacy, similarly to the 3D localization of the androgen receptor.

When prostate tumors escape the capsule, they form micro-metastatic lesions in the retroperitoneal lymph nodes. We derived a prostate cancer organoid from such a micro-metastasis, for which whole-genome sequencing showed homozygous mutations in PTEN and BRCA2 as well as a mutated KIF4B. In our organoid culture, these drug-naïve tumors formed slow-proliferating tumors with driver mutations: homozygous PTEN (exon 2, c.G194>C, p.C65S) and BRCA2 (exon 14, c.T7397>C, p.V2466A). A heterozygous mutation we identified in KIF4B (exon 1, c.G1739>T, p.R580L) likely contributes to errors during chromosome segregation. We also detected an androgen receptor deletion, which we have shown to be associated with smaller tumor cells and more aggressive disease. These are examples in which image analysis in living cells can validate the mechanisms suggested by sequencing data and thus inform therapy.

Cell therapy is becoming the forefront of precision medicine, and it is critical to anticipate the mechanisms of action of engineered immune cells. Natural killer cells and cytotoxic T cells employ different mechanisms to kill their targets, for instance by secreting cytotoxic lysosomes using the microtubule cytoskeleton for trafficking and release. They also induce a plethora of effects in the target cells, the best studied of which lead to apoptosis and ferroptosis, a recently identified, potent, caspase-independent mechanism of programmed cell death. The exact pathways activated during therapy can be pinpointed by measuring its effects on the target proteins in patient-derived living cells ex vivo.

We are building a functional workflow that tests the combinations OncoAgent proposes on a patient's own cells within hours of surgery and selects the most effective one from the cells' dynamics. The same measurements apply to patient-derived neurons in ALS and Alzheimer's disease.

"Deep down in my heart - I knew that [Flo](https://github.com/FlowAnalytic) was good to go."

We welcome collaborations with pharmaceutical companies, clinicians and research partners, and we are ready to test OncoAgent for physicians' patients.

- [Contact us](mailto:alexandre.matov@gmail.com)
