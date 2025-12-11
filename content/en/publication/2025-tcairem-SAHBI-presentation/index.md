---
title: "Presentation : MEDfl: A Collaborative Framework for Federated Learning in Medicine  "
date: 2025-11-14
image:
  focal_point: 'top'

type: book

authors:
  - Ouael Nedjem Eddine SAHBI
  - Hithem lamri
  - Martin Vallières

categories: Presentations
where: T-CAIREM
---

![T-CAIREM](tcairem.png)

## Date

2025-11-14

## Authors

- [Ouael Nedjem Eddine SAHBI]({{< relref "/authors/ouael-nedjem-eddine-sahbi" >}})
- [Hithem lamri]({{< relref "/authors/hithem-lamri" >}})
- [Bessam abdulrazak](https://www.usherbrooke.ca/recherche/fr/specialistes/details/bessam.abdulrazak)
- [Martin Vallières]({{< relref "/authors/martin-vallieres" >}})

## Summary

  **1. Context and Problem**

 Medical institutions hold vast amounts of valuable clinical data critical for training artificial intelligence (AI) models. However, strict regulations such as **GDPR** and **HIPAA** prevent the free sharing of patient data across hospitals, limiting the diversity and scale of datasets available for AI training.

Beyond these regulatory and data-related challenges, there is also a growing **need for tools that foster collaboration between researchers from different disciplines**, such as computer scientists and medical experts. Despite the potential of AI in healthcare, interdisciplinary collaboration remains complex due to the lack of integrated and user-friendly platforms capable of bridging the gap between technical and clinical domains.


  **2. Proposed Solution: MEDfl**

We propose MEDfl, a federated learning (FL) framework that enables collaborative research AI modeling across multiple hospitals without moving sensitive data outside institutional boundaries.
Each site retains full control over its datasets, while only encrypted model updates are exchanged with a central coordinating server.

MEDfl integrates several complementary technologies:
  - Transfer Learning (TL) to improve performance in data-scarce environments.
  - Differential Privacy (DP) to prevent potential re-identification of patients.
  - Secure Aggregation to further protect shared information during model updates.

Beyond these privacy and performance aspects, MEDfl also tackles the **collaboration challenge between computer scientists and medical researchers.**
 
It combines:
  - **A user-friendly interface** that allows researchers to design and launch federated learning experiments without deep programming knowledge.
  - **Automated code generation** that translates configurations defined in the interface into executable federated learning pipelines.
  - **An integrated code package** that provides ready-to-use modules for communication, orchestration, and result analysis.

Together, these components make MEDfl a **complete ecosystem** for secure, efficient, and interdisciplinary research collaboration in medical AI.

  
  **3. Implementation and Validation**

The first version of the MEDfl package is already available on PyPI (https://pypi.org/project/MEDfl/) , supporting both simulation and real-world deployment.
 We provide YouTube tutorials (https://www.youtube.com/playlist?list=PLEPy2VhC4-D7Y4lkGMRpHG8ydVZQonkMJ)  and open-source repositories for the Python package (https://github.com/MEDomicsLab/MEDfl) and the desktop application (https://github.com/MEDomicsLab/MEDomics/tree/dev_medfl_sqllite).

A proof of concept has been validated through simulation scenarios comparing:
  - Centralized vs. federated training
  - Different network architectures
  - Various aggregation functions
  - Transfer learning activation/deactivation

Results:

Using **FedAvg**, models with **transfer learning** achieved faster and stronger performance **(AUC 0.85–0.9)** compared to models without it **(AUC 0.75–0.78)**, confirming the benefit of combining **federated learning (FL)** and **transfer learning (TL)** for faster convergence and improved adaptation across heterogeneous clients. These experiments were conducted on a **publicly available binary classification dataset on diabetes** from **Kaggle**, which contains **100,000 instances**, each representing an individual with several clinical attributes. The objective is to **predict the presence or absence of diabetes**, providing a realistic benchmark to assess the robustness and generalization of federated models under strict privacy constraints.

  **4. System Features**

  - Lightweight clients connected via VPN and WebSockets.
  - Real-time dashboards for monitoring training and performance.
  - Automatic result storage ensures reproducibility and compliance.
  - Designed for both local simulation and multi-institutional deployment.

  **5. Expected Outcomes**

MEDfl aims to:
  - Preserve data privacy without hindering multi-institutional medical research.
  - Empower computer scientists to easily configure, run, and compare FL pipelines.
  - Simplify collaboration between medical and technical researchers through accessible, no-code tools.



## Presentation
<iframe src="./TCAIREM_Ouael_SAHBI_MEDfl.pdf" width="100%" height="600px" style="border: none; background: transparent;"></iframe>

## Poster
<iframe src="./Poster_MEDfl_T-cairem.pdf" width="100%" height="600px" style="border: none; background: transparent;"></iframe>

## Links

- [Event Details](https://tcairem.utoronto.ca/2025-t-cairem-conference-evolution-generative-ai)
- [T-CAIREM website](https://tcairem.utoronto.ca/)
