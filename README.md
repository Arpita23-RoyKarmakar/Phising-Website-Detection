🛡️ Phishing Website Detection — MCA Final-Year PBL Project (Sec - E)
This repository hosts the complete source code for our final-year Problem-Based Learning (PBL) project on Phishing Website Detection, designed and developed for MCA Section - E.
📌 Project Overview
Phishing is a highly prevalent social engineering attack where malicious actors mimic legitimate platforms to compromise sensitive credential details. To counter this threat, we developed an intelligent, machine-learning-driven classifier that analyzes a website's structural and security attributes to output instant legitimacy assessments.
⚙️ Key Technical Features
Feature Extraction Heuristics: Evaluates 8 critical security parameters (including SSL implementation status, domain structure anomaly checking, URL shortening usage, prefix-suffix hyphenation patterns, and URL length attributes).
Exploratory Data Analysis (EDA): Contains comprehensive correlation heatmaps and dataset class imbalance studies using Seaborn and Matplotlib.
Optimized Model Training: Implements an optimized Random Forest Classifier achieving an outstanding validation accuracy of 98.33% with high precision and recall stability across malicious classes.
Live URL Tester: Features an integrated pipeline allowing users to feed in a real-world URL (e.g. https://google.com), automatically extract its properties, and run predictions on the fly.
📊 Model Performance Evaluation
Accuracy: 98.33%
F1-Score (Phishing): 0.98
F1-Score (Legitimate): 0.98
🚀 Quick Start
To execute a test on any live website domain directly from the notebook:
test_real_url("https://your-target-website.com")
