COVID-19 Vaccine Analysis with Deep Learning
Project Overview
This project is a deep learning proof-of-concept that simulates the analysis of a clinical trial for a new COVID-19 vaccine. It uses a synthetic dataset to demonstrate how machine learning can be applied to evaluate a vaccine's effectiveness (immunogenicity) and safety, without relying on real-world patient data.

Study Description
The analysis in this project is based on a simulated Phase 3 clinical trial cohort, designed to reflect a public report on the LP.8.1-adapted monovalent COMIRNATY® (COVID-19 Vaccine, mRNA) 2025-2026 Formula.

Trial Population: The study cohort includes 100 participants, divided into two groups:

Adults aged 65 and older.

Adults aged 18 through 64 with at least one underlying risk condition for severe COVID-19.

Vaccine: A 30-µg dose of the LP.8.1-adapted monovalent COMIRNATY® vaccine.

Key Metrics: The project focuses on two primary outcomes of the trial:

Immunogenicity: The vaccine's ability to generate a robust immune response, measured by the increase in neutralizing antibody titers.

Safety: The occurrence of post-vaccination adverse events.

Methodology
Data
Due to the sensitive nature of clinical trial information and patient privacy regulations, this project uses a synthetic dataset. The data is artificially generated using Python's numpy library to mimic the structure and key findings of a real study. The dataset includes columns for age, risk conditions, baseline antibody titers, and simulated post-vaccination results.

Deep Learning Model
The deep learning model used is a Sequential Neural Network built with TensorFlow and Keras.

Architecture: The model consists of multiple dense layers with dropout for regularization.

Purpose: The model is trained to perform a binary classification task, predicting the probability of seroconversion (a significant increase in antibody titers) based on the participant's age, underlying risk, and baseline immune status.

Key Findings (Simulated)
Based on the simulated data, the analysis concludes:

Robust Immune Response: The vaccine elicited a strong immune response in both age groups, with a simulated average fold-increase of at least 4x in antibody titers, consistent with public reports.

Favorable Safety Profile: The simulated rate of adverse events was low, with no significant differences between the cohorts, aligning with public statements on the vaccine's safety.

Disclaimer
This project is for educational and demonstrative purposes only. The dataset is synthetic and does not contain any real-world patient data. The findings and conclusions are not based on actual clinical trial results and should not be used to make medical decisions.

