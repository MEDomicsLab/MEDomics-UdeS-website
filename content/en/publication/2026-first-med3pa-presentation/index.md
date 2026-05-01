---
title: "Presentation : Kaféfak Presentation - First Publication Award"
date: 2026-04-29
image:
  focal_point: 'top'

type: book

authors:
  - Olivier Lefebvre

categories: Presentations
where: UDS - Faculté des sciences
---

![Certificat](certificat.png)

## Date

2026-04-29

## Authors

- [Olivier Lefebvre]({{< relref "/authors/olivier-lefebvre" >}})

## Summary
Olivier Lefebvre received the First Publication Award from the Faculty of Science, which highlights publications that distinguished themselves both within their field and among all entries submitted for the competition. The award was presented during the Kaféfak conference, where he was invited to give a three‑minute presentation to make his research accessible to a broad audience. A 200$ prize accompanies the award.


## Abstract

**Objectives**
Artificial Intelligence models are increasingly used in health care, yet global performance metrics can mask variations in reliability across individual patients or subgroups with shared attributes, called patient profiles. This study introduces predictive performance precision analysis in medicine (MED3pa), a method that identifies when models are less reliable, allowing clinicians to better assess model limitations.

**Materials and Methods**
We propose a framework that estimates predictive confidence using 3 combined approaches: individualized (IPC), aggregated (APC), and mixed predictive confidence (MPC). Individualized predictive confidence estimates confidence for each patient, APC assesses it across profiles, and MPC combines both. We evaluate our method on 4 datasets: 1 simulated, 2 public, and 1 private clinical dataset. Metrics by declaration rate curves show how performance changes when retaining only the most confident predictions, while interpretable decision trees reveal profiles with higher or lower model confidence.

**Results**
We demonstrate our method in internal, temporal, and external validation settings, as well as through a clinical example. In internal validation, limiting predictions to the 93% most confident cases improved sensitivity by 14.3% and the area under the receiver operating characteristic curve by 5.1%. In the clinical example, MED3pa identified a patient profile with high misclassification risk, demonstrating its potential for safer deployment.

**Discussion**
By identifying low-confidence predictions, our framework improves model reliability in clinical settings. It can be integrated into decision support systems to help clinicians make more informed decisions. Confidence thresholds help balance model performance with the proportion of patients for whom predictions are considered reliable.

**Conclusion**
Better leveraging confidence in model predictions could improve reliability and trustworthiness, supporting safer and more effective use in health care.


## Poster
<iframe src="./Lefebvre_olivier_kafefak_2026.pdf" width="100%" height="600px" style="border: none; background: transparent;"></iframe>
