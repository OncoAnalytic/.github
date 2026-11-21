![OncoAnalytic: AI-Guided Patient Stratification](onco-cover.png)

## OncoAnalytic and OncoAgent

At OncoAnalytic, we develop AI-guided patient stratification that turns molecular and clinical test results into ranked, patient-specific drug regimens. Our platform, OncoAgent, is a multi-agent orchestration AI with six agents - two medical models and four general-purpose LLMs - that work through multiple rounds of analysis and cross-review. Our own biology-based prompting guides the agents toward drug combinations that address resistance mechanisms with minimal toxicity. When no raw sequencing data is used, an analysis takes about six minutes.

## Patient reports and clinical experience

We have prepared reports for 35 patients using results from clinical laboratories and medical centers, covering tumor DNA and RNA sequencing, liquid biopsy, proteomics, immunomics and pharmacogenomics, and treating physicians used them prospectively when choosing therapies. For a glioblastoma patient, OncoAgent identified a Crohn's disease drug. In the words of the treating physician: "she had an amazing shrinkage of the tumor, which even the surgeon was confused by because he has never... usually these patients need another surgery right after radiation, and she is responding because actually Alex found a drug that is a Crohn's disease drug, not a cancer drug at all, and she responded" ([recording, minutes 25–26](https://drive.google.com/file/d/1zQQ08ErRbUZDmnRYHrnVgZdGq0ohBdGD/view)). We believe patient treatments are consistently needlessly toxic; in glioblastoma, mild non-cancer drugs can be very impactful, and this is likely the case in other tumor types as well.

"I met my match - her name was [Flo](https://github.com/FlowAnalytic)."

## Connecting genomics with cell function

Our strategy is derived from fundamental research. We connect genomics with cell function, because clinical live-cell imaging provides information that can never be obtained by sequencing. [FlowAnalytic](https://github.com/FlowAnalytic), our quantitative live-cell imaging software, builds on more than 20 years of work in quantitative microscopy. It measures microtubule, actin and focal-adhesion dynamics, cell division and migration in patient-derived cells and organoids during drug exposure, revealing drug-response and resistance phenotypes. Tim Mitchison provided examples of the need for imaging (Fig. 1C–E) to dissect the immune response in "So many ways to naturally kill a cancer cell" (BMC Biology).

## RIT1, cell organization and treatment response

RIT1 (Wes et al., 1996), a RAS-related GTPase, is essential for timely progression through mitosis and proper chromosome segregation (Cuevas-Navarro et al., 2021), suggesting targeting of RIT1 in cancer. PAK1 is an effector of RIT1, and RIT1 directly interacts with the Rho GTPases Cdc42 and Rac1 (Meyer zum Büschenfelde et al., 2018). We reported new measurements of PAK-inhibited cells expressing constitutively active Rac1(Q61L) that demonstrated a molecular machinery, not previously described in the literature, based on contractility in the lamella of migrating cells, which can be exploited in the clinic (Matov, 2025). Our computational analysis measured for the first time a retrograde F-actin network and a contractile meshwork of overlapping anterograde and retrograde flows in the lamella. In addition, we detected a third, occasionally appearing, fast retrograde flow in the thin area of remaining lamellipodia in PAK-inhibited cells (Matov, 2025). RIT1 is distributed in the cytoplasm as cells enter mitosis and progress through metaphase, but rapidly translocates to the plasma membrane during anaphase (Cuevas-Navarro et al., 2021). In contrast, the pathogenic RIT1 SGL variant is not displaced from the membrane, as the McCormick lab demonstrated with images (Fig. S2A) in "The RAS GTPase RIT1 compromises mitotic fidelity through spindle assembly checkpoint suppression" (Current Biology). Image analysis of F-actin and microtubule polymerization dynamics in patient cells can dissect the molecular mechanisms of cellular organization in the presence of pathogenic levels of RIT1 and tailor RAS-targeting therapies to the individual. The 3D diffusion of RIT1 between the plasma membrane and the cytoplasm during mitosis can serve as a biomarker of drug efficacy, similarly to the 3D localization of the androgen receptor (AR) (Matov, 2024b).

## Patient-derived prostate cancer organoids

When prostate tumors escape the capsule, they form micro-metastatic lesions in the retroperitoneal lymph nodes (Brassetti et al., 2019; McLaughlin et al., 1976). We derived a prostate cancer organoid from such a micro-metastasis, for which whole-genome sequencing showed homozygous mutations in PTEN and BRCA2 as well as a mutated KIF4B (Matov, 2024g). In our organoid culture, these drug-naïve tumors formed slow-proliferating tumors with driver mutations: homozygous PTEN (exon 2, c.G194>C, p.C65S) and BRCA2 (exon 14, c.T7397>C, p.V2466A) (Matov, 2025b). A heterozygous mutation we identified in KIF4B (exon 1, c.G1739>T, p.R580L) likely contributes to errors during chromosome segregation (Mazumdar et al., 2004). We also detected an AR deletion, which we have shown to be associated with smaller tumor cells and more aggressive disease (Matov, 2024c; Matov, 2024e). These are examples in which image analysis in living cells can validate the mechanisms suggested by sequencing data and thus inform therapy.

## Cell therapy and functional measurements

Cell therapy (Gage, 1998) is becoming the forefront of precision medicine, and it is critical to anticipate the mechanisms of action of engineered immune cells (Dekkers et al., 2023; Irvine et al., 2022; Lim and June, 2017). Natural killer cells and cytotoxic T cells employ different mechanisms to kill their targets (Deng et al., 2015; Mitchison, 2021; Pardoll, 2003; Pardoll and Topalian, 1998), for instance by secreting cytotoxic lysosomes using the microtubule cytoskeleton for trafficking and release. They also induce a plethora of effects in the target cells, the best studied of which lead to apoptosis and ferroptosis (Dixon et al., 2012; Viswanathan et al., 2017), a recently identified, potent, caspase-independent mechanism of programmed cell death. The exact pathways activated during therapy can be pinpointed by measuring its effects on the target proteins in patient-derived living cells ex vivo.

## The workflow we are building

We are building a functional workflow that tests the combinations OncoAgent proposes on a patient's own cells within hours of surgery and selects the most effective one from the cells' dynamics. The same measurements apply to patient-derived neurons in ALS and Alzheimer's disease. Our approach is grounded in 16 papers - original research publications, not reviews - written between May 2024 and March 2025 and based on hypotheses conceived while not employed by any company or university, including "Quantitative Cell Division and Migration in Medicine" and "Real-Time Image Analysis Software Suitable for Resource-Constrained Computing" ([lab page](https://www.researchgate.net/lab/OncoAnalytic-Corporation-Alex-Matov)). These papers contain many images of organoids forming prostate physiology and discuss what we don't yet know about its regulation and how to overcome drug resistance.

"Deep down in my heart - I knew that [Flo](https://github.com/FlowAnalytic) was good to go."

## Collaborate with us

We welcome collaborations with pharmaceutical companies, clinicians and research partners, and we are ready to test OncoAgent for physicians' patients.

- [Contact us](mailto:alexandre.matov@gmail.com)
