# Temporal Dynamics of Learner Engagement

This repository contains the code, data outputs, and final report for the analysis of two distinct educational datasets: the Open University Learning Analytics Dataset (OULAD) and a Moodle Learning Management System (LMS) interaction log. 

The project applies Educational Data Mining (EDM) techniques to explore how the temporal distribution of student effort impacts academic success, utilizing both supervised classification and unsupervised behavioral segmentation.

## Repository Structure

```text
📁 ET-610-Assignment-2/
├── 📄 README.md                  # Project overview and instructions
├── 📁 notebooks/
│   ├── oulad_analysis.ipynb      # Supervised learning pipeline (Random Forest)
│   └── moodle_analysis.ipynb     # Unsupervised learning pipeline (K-Means)
├── 📁 outputs/
│   ├── 📁 oulad/                 # Generated CSV metrics and temporal visualizations
│   └── 📁 moodle/                # Cluster profiles, PCA scatters, and evaluation metrics
└── 📄 Final_Report.pdf           # Comprehensive 10-page academic report
