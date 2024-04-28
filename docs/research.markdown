<!-- ---
layout: minimal
title: Research
permalink: /research/
nav_order: 1
--- -->

## Research Projects

Some short descriptions of my work for research projects at UW.

---

### Detecting hardware aging in CPUs

Sep-23 ... (ongoing)
{: .fs-3 }

(Collaboration with University of Michigan) With the UW Systems Lab and UW Security & Privacy Research Lab, I'm experimenting with workflows for detecting gate-level hardware aging in an open-source RISC-V CPU.

SystemVerilog, Verilog, Python, C++
{: .text-grey-dk-000 .fs-3 }

---

### GPU power efficiency

Sep-23 ... (ongoing)
{: .fs-3 }

(Collaboration with Microsoft Azure Systems Research) With the UW Systems Lab, I'm exploring ways to improve power efficiency in GPU-related deep learning inference operations. This work isn't public at the moment.

---

### Carbon-aware data centers

Mar-23 ... Sep-23
{: .fs-3 }

Working with the UW Systems Lab, I helped identify development bottenecks and challenges for incorporating carbon-awareness into data center operations. I also helped craft a proposal for adopting an agile approach with optimizations centered on the operator's end, and suggested interfaces for emission reduction. This work was published in HotCarbon'23 - see the [paper](https://dl.acm.org/doi/abs/10.1145/3604930.3605722) for details.

For follow-up work, I explored the effects of incorporating carbon as an optimization goal when scheduling machine learning inference workloads. I used an ILP solver and trace data from data center workloads, hardware benchmarks, and public energy grids to simulate impact alongside cost and energy. The results will hopefully motivate future research in the UW Systems Lab.

Python, Gurobi, Ray
{: .text-grey-dk-000 .fs-3 }

---

### Privacy enforcement in software services

Mar-22 ... Jun-23
{: .fs-3 }

I wrote my undergraduate thesis on technical privacy enforcement mechanisms for software services. I took a systematization-of-knowledge approach and systematized ~200 research papers. This involved assessing techniques and mechanisms in terms of common privacy requirements synthesized from privacy policies and privacy legislation. I'm currently working on getting a shortened version of this added to ArXiv.

---

### Dark patterns in election advertisements

Sep-21 ... Mar-22
{: .fs-3 }

Alongside peers in the UW Security & Privacy Research Lab, I explored potential dark patterns in advertising around the 2020 U.S. elections. Specifically, I used NLP topic modeling techniques over OCR text for ~1.4 million ads collected in the months surrounding the elections. I also helped develop and apply a codebook for categorizing ads. This work was published in IMC'21 - see the [paper](https://dl.acm.org/doi/abs/10.1145/3487552.3487850) for details.

Python, NLTK, Stanza, Sklearn, Gensim, GSDMM
{: .text-grey-dk-000 .fs-3 }

(Collaboration with UW NLP Group) For follow-up work, I developed a prototype web extension for detecting native advertisements and determining if their content was potentially harmful or misleading. It interfaced with an intent model being developed in the NLP Group.

React, Webpack, Typescript
{: .text-grey-dk-000 .fs-3 }

---

### Misinformation spread on Facebook
Mar-21 ... Aug-21
{: .fs-3 }

(Collaboration with Facebook Research and Social Science One) With colleagues in the UW Security & Privacy Research Lab, I studied a private dataset of URL sharing information on Facebook from 2017-2019 to investigate misinformation spread on the platform. I wrote SQL queries over ~700 bilion rows (trillions of data points) and performed data analysis with differential privacy. This work was published in FOCI'21 - see the [paper](https://dl.acm.org/doi/10.1145/3473604.3474561) for details.

Amazon Athena SQL, Python, Pandas, Seaborn
{: .text-grey-dk-000 .fs-3 }