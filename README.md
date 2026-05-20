# Towards Explainable and Interpretable Predictive Monitoring of Collaborative Processes

**Authors:** Roberto Nai, Emilio Sulis, Daniel Calegari García, Andrea Delgado

---

## Abstract

Collaborative processes involve multiple interacting participants that coordinate activities to achieve shared objectives. In these settings, process behaviour depends not only on activity sequences but also on interaction dynamics among actors, making predictive process monitoring (PPM) particularly challenging. Moreover, many predictive approaches remain black-box models, limiting the interpretability of their outputs. 

This work proposes integrating explainability and interpretation components into a PPM pipeline for collaborative business processes. The approach transforms traditional event logs into collaborative event logs enriched with participant-oriented, interaction-aware information that describes inter-participant interactions and message exchanges. The predictive layer employs Transformer-based techniques, while the explainability layer analyses the contributions of activities, participants, and interaction-aware elements to predictive outcomes using SHAP explanations. In addition, a locally deployed Large Language Model-based interpretation layer generates human-readable explanations while preserving data privacy. 

The experimental evaluation was conducted on four benchmark collaborative event logs and, additionally, on a new real-world healthcare event log from an Emergency Department, introduced as a collaborative healthcare case study for this work. 

## Project Scripts

The scripts and data for this project are available at: [https://github.com/roberto-nai/PREDICT-COLLAB](https://github.com/roberto-nai/PREDICT-COLLAB)

## Folders

| Folder | Description |
|--------|-------------|
| `images` | High-resolution images of the figures included in the paper |

---

**Contact author:** Roberto Nai (<roberto.nai@unito.it>)
