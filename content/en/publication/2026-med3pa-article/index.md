---
title: "Paper: Predictive performance precision analysis in medicine: identification of low-confidence predictions at patient and profile levels (MED3pa I)"
date: 2026-03-31
image:
  focal_point: 'top'

type: book

authors:
  - Olivier Lefebvre
  - Martin Vallières

categories: Journal Papers
where: JAMIA
---

![Journal of the American Medical Informatics Association (JAMIA)](featured.png)

## Date

2026-03-31

## Authors

  - [Olivier Lefebvre]({{< relref "/authors/olivier-lefebvre" >}})<sup>1</sup> 
  - [Félix Camirand Lemyre](https://www.usherbrooke.ca/mathematiques/nous-joindre/personnel/corps-professoral/professeurs/felix-camirand-lemyre)<sup>2</sup> 
  - [Jean-François Éthier](https://www.usherbrooke.ca/recherche/specialistes/details/jean-francois.ethier)<sup>3</sup> 
  - [Ludmila Amriou]({{< relref "/authors/ludmila-amriou" >}})<sup>4</sup> 
  - [Lyna Hiba Chikouche]({{< relref "/authors/Lyna-Hiba-Chikouche" >}})<sup>4</sup>
  - [Dan Poenaru](https://www.mcgill.ca/pediatricsurgery/dan-poenaru)<sup>5, 6</sup>
  - [Martin Vallières]({{< relref "/authors/martin-vallieres" >}})<sup>1, 7</sup> 

<sup>1</sup> Computer science department, Université de Sherbrooke, Sherbrooke (QC), Canada

<sup>2</sup> Mathematics department, Université de Sherbrooke, Sherbrooke (QC), Canada

<sup>3</sup> Medicine department, Université de Sherbrooke, Sherbrooke (QC), Canada

<sup>4</sup> Department of Higher Studies (CS), École nationale Supérieure d’Informatique, Alger, 16309, Algeria

<sup>5</sup> Department of Pediatric Surgery, Montreal Children’s Hospital, Montreal, QC H4A 3J1, Canada

<sup>6</sup> Centre for Outcomes Research and Evaluation, Research Institute of the McGill University Health Centre, Montreal, QC H4A 3J1, Canada

<sup>7</sup> Medical Physics Unit, Department of Oncology, McGill University, Montreal, QC H3A 0G4, Canada

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

## Links

  - [Paper in JAMIA](https://doi.org/10.1093/jamia/ocag034)
