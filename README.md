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

# 📁 AI4Mars Project Repository Structure

- **data/**
  - **raw/**
    - edr/ → Raw Mars images from Curiosity
    - mxy/ → Rover masks
    - rng-30m/ → Range masks beyond 30 meters
    - labels/ → Train/test label masks
  - processed/ → Cleaned or resized data
  - data_dictionary.md → Documentation about dataset classes, RGB values, etc.

- **notebooks/**
  - 01_data_exploration.ipynb
  - 02_data_preprocessing.ipynb
  - 03_model_training.ipynb
  - 04_model_evaluation.ipynb

- **visuals/**
  - data_samples/ → Random image-label overlays
  - class_distribution/ → Pie charts, bar graphs
  - model_metrics/ → Loss curves, confusion matrices

- **src/**
  - data_loader.py → PyTorch Dataset class for AI4Mars
  - utils.py → Helper functions
  - train.py → Model training script

- **reports/**
  - AI4Mars_Final_Report.pdf
  - AI4Mars_Final_Report.mp4

- **presentation/**
  - slides.pptx

- **meta/**
  - team_contacts.txt
  - meeting_notes.md
  - role_assignment.md
  - ai_usage_notes.md

- requirements.txt → Python dependencies
- README.md → Project overview and instructions
- .gitignore → Files and folders to exclude from Git

