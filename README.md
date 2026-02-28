🚀 VLSI_EDA_ML_Pipeline
Machine Learning-Augmented Electronic Design Automation for VLSI Optimization
📌 Overview

This repository implements a structured Machine Learning pipeline designed to enhance Electronic Design Automation (EDA) workflows in VLSI design.

Modern VLSI design flows are computationally intensive and rely heavily on heuristics. This project integrates data-driven predictive modeling to accelerate optimization stages such as timing analysis, power estimation, congestion prediction, and design space exploration.

The goal is to bridge AI and semiconductor physical design through scalable ML-assisted automation.

🎯 Key Objectives

Build an end-to-end ML pipeline tailored for EDA data

Predict critical VLSI metrics:

Timing violations

Power consumption

Routing congestion

Placement quality

Reduce physical design iteration cycles

Enable intelligent feedback-driven optimization

🏗️ System Architecture
EDA Reports / Netlist Data
        ↓
Data Parsing & Cleaning
        ↓
Feature Engineering
        ↓
Feature Selection
        ↓
Model Training (ML/DL)
        ↓
Performance Evaluation
        ↓
Optimization Feedback Loop
📂 Repository Structure
VLSI_EDA/
│
├── data/                # Raw and processed EDA datasets
├── notebooks/           # Experimental notebooks
├── src/                 # Core pipeline scripts
├── models/              # Saved trained models
├── results/             # Evaluation outputs and plots
├── requirements.txt
└── README.md
📊 Dataset Description

The pipeline supports structured EDA outputs such as:

Static Timing Analysis (STA) reports

Power analysis reports

Netlist-derived structural features

Layout geometric features

Congestion metrics

Preprocessing steps include:

Missing value handling

Scaling & normalization

Outlier filtering

Feature correlation analysis

🤖 Models Implemented
Classical Machine Learning

Random Forest

XGBoost

LightGBM

Support Vector Regression

Deep Learning

Fully Connected Neural Networks

(Planned) Graph Neural Networks for netlist topology modeling

📈 Evaluation Metrics
Regression Tasks

Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

R² Score

Classification Tasks

Accuracy

Precision / Recall

F1 Score

ROC-AUC

Cross-validation and hyperparameter tuning are supported.

⚙️ Installation

Clone the repository:
git clone https://github.com/Ayushdevo/VLSI_EDA.git
cd VLSI_EDA
Install dependencies:
pip install -r requirements.txt
Run the pipeline:
python vlsi_eda_ml_pipeline.py
🔬 Research Scope & Extensions

This framework is structured for advanced research and industrial applications:

Reinforcement Learning for placement optimization

Graph Neural Networks for netlist representation

Surrogate modeling for rapid design space exploration

AutoML integration for hyperparameter tuning

ML-driven congestion mitigation

📊 Experimental Results

(To be updated after benchmarking)

Model	          MAE 	RMSE	R²
Random Forest	TBD	TBD	TBD
XGBoost	          TBD       TBD       TBD
Neural Net	TBD	TBD	TBD
🧠 Why This Project Matters

As semiconductor technology scales to advanced nodes (sub-5nm and beyond), traditional heuristic EDA approaches face scalability challenges.

Machine Learning-assisted EDA enables:

Faster convergence

Improved optimization quality

Reduced runtime

Smarter design feedback loops

This project represents a step toward AI-accelerated chip design.

👨‍💻 Author

Ayush Tiwari
Data Science & AI
IIT Guwahati

AI × VLSI × Optimization

📜 License

MIT License
