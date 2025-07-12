# AI4Mars Project

Welcome to the AI4Mars Project!

This repository contains code, documentation, and resources for working with the **AI4Mars Merged Dataset (version 0.1)**, featuring Mars surface images captured by NASA’s Curiosity rover.

Our goal is to explore the dataset and build machine learning models to segment Martian terrain into classes such as soil, bedrock, sand, and big rocks.

---

## 🚀 Project Overview

**AI4Mars Merged Dataset v0.1** includes:

- Raw Mars imagery from Curiosity (MSL)
- Semantic labels for:
  - Soil
  - Bedrock
  - Sand
  - Big Rock
  - NULL (no label)
- Rover masks (to mask out rover hardware)
- Range masks (to exclude regions beyond 30 meters)

We aim to build semantic segmentation models for Martian terrain analysis.

---

## 📂 Repository Structure

ai4mars-project/
-│
-├── data/
-│ ├── raw/
-│ │ ├── edr/
-│ │ ├── mxy/
-│ │ ├── rng-30m/
-│ │ └── labels/
-│ ├── processed/
-│ └── data_dictionary.md
-│
├── notebooks/
│ ├── 01_data_exploration.ipynb
│ ├── 02_data_preprocessing.ipynb
│ ├── 03_model_training.ipynb
│ ├── 04_model_evaluation.ipynb
│
├── visuals/
│ ├── data_samples/
│ ├── class_distribution/
│ ├── model_metrics/
│
├── src/
│ ├── data_loader.py
│ ├── utils.py
│ └── train.py
│
├── reports/
│ ├── AI4Mars_Final_Report.pdf
│ └── AI4Mars_Final_Report.mp4
│
├── presentation/
│ └── slides.pptx
│
├── meta/
│ ├── team_contacts.txt
│ ├── meeting_notes.md
│ ├── role_assignment.md
│ └── ai_usage_notes.md
│
├── requirements.txt
├── README.md
└── .gitignore
