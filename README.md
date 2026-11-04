🧠 Blood-Brain Barrier (BBB) Permeability Predictor



An AI-driven cheminformatics predictive pipeline and interactive web application for classifying the Blood-Brain Barrier (BBB) permeability of drug-like molecules.

This project bridges computational biology and machine learning, utilizing molecular feature extraction to predict whether a compound can successfully cross the BBB—a critical bottleneck in neuro-pharmaceutical drug discovery. The results are accessible through a clean, minimalistic user interface built with Streamlit.

✨ Features

SMILES Parsing: Convert raw chemical structures input as SMILES strings into manipulable molecular objects using RDKit.

Cheminformatics Feature Extraction: Automatically calculate core physicochemical properties:

Molecular Weight (MolWt)

Partition Coefficient (MolLogP)

Topological Polar Surface Area (TPSA)

Hydrogen Bond Donors & Acceptors (NumHDonors, NumHAcceptors)

Machine Learning Prediction: Deploy a trained Random Forest classifier to categorize molecules into BBB+ (Permeable) or BBB- (Impermeable) with confidence probabilities.

Interactive Workflows:

Single-Molecule Analysis: Enter a custom SMILES string for instant inspection.

Batch Processing: Upload a CSV file containing multiple SMILES strings for high-throughput screening.

Data Visualization: Inspect feature importance rankings and molecular property distributions.

Export Capability: Download predictive results as a clean CSV report.

Modern UI: Clean, zero-clutter glassmorphism user interface designed for scientific dashboards.
