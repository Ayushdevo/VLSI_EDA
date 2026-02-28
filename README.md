🚀 VLSI_EDA_ML_Pipeline
Machine Learning-Augmented Electronic Design Automation for VLSI Optimization
📌 Abstract

Modern Electronic Design Automation (EDA) workflows for VLSI systems are computationally intensive and heavily heuristic-driven. This project introduces a modular Machine Learning (ML) pipeline designed to assist and accelerate critical EDA stages such as timing analysis, power estimation, congestion prediction, and design space exploration.

The objective is to integrate data-driven predictive models into conventional EDA flows to reduce runtime, improve optimization quality, and enable intelligent feedback mechanisms.

🎯 Objectives

Develop an end-to-end ML pipeline tailored for EDA data

Predict critical VLSI metrics:

⏱ Timing violations

🔋 Power consumption

📍 Routing congestion

📐 Placement quality

Reduce iteration cycles in physical design

Establish a scalable research framework for ML-driven chip design

🏗️ System Architecture
EDA Reports / Netlist Data
          ↓
Data Parsing & Cleaning
          ↓
Feature Engineering
          ↓
Feature Selection / Dimensionality Reduction
          ↓
Model Training (ML / DL)
          ↓
Performance Evaluation
          ↓
Design Optimization Feedback
📂 Repository Structure
VLSI_EDA/
│
├── data/                # Raw and processed datasets
├── notebooks/           # Exploratory and experiment notebooks
├── src/                 # Core pipeline scripts
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── train.py
│   ├── evaluate.py
│   └── utils.py
│
├── models/              # Saved trained models
├── results/             # Performance metrics and plots
├── requirements.txt
└── README.md
📊 Dataset Description

The dataset consists of structured EDA outputs including:

Static Timing Analysis (STA) reports

Power analysis reports

Netlist-derived structural features

Layout-based geometric features

Congestion metrics

Data preprocessing includes:

Missing value handling

Normalization / scaling

Outlier filtering

Feature correlation analysis

🤖 Models Implemented
Classical ML Models

Random Forest Regressor

XGBoost

LightGBM

Support Vector Regression

Deep Learning Models

Fully Connected Neural Networks

(Planned) Graph Neural Networks for netlist topology modeling

📈 Evaluation Metrics

Depending on prediction task:

Regression Tasks

Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

R² Score

Classification Tasks

Accuracy

Precision / Recall

F1 Score

ROC-AUC

Cross-validation and hyperparameter tuning are performed using GridSearchCV / Bayesian Optimization.

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/Ayushdevo/VLSI_EDA.git
cd VLSI_EDA

Install dependencies:

pip install -r requirements.txt

Run training pipeline:

python src/train.py
🔬 Research Extensions

This repository is structured to support advanced research directions:

Reinforcement Learning for placement optimization

Graph Neural Networks for structural netlist modeling

Surrogate modeling for rapid design space exploration

AutoML integration for hyperparameter optimization

Hardware-aware ML models for ASIC flows

📊 Experimental Results

(To be updated after experiments)

Model	MAE	RMSE	R² Score
Random Forest	TBD	TBD	TBD
XGBoost	TBD	TBD	TBD
Neural Net	TBD	TBD	TBD
🧠 Why This Project Matters

As chip complexity increases (sub-5nm nodes, billion-transistor designs), traditional heuristic EDA flows become bottlenecks. ML-augmented EDA can:

Reduce runtime significantly

Improve optimization quality

Enable adaptive design strategies

Accelerate tape-out cycles

This project bridges AI and VLSI physical design — a growing research and industry frontier.

👨‍💻 Author

Ayush Tiwari
Data Science & AI
IIT Guwahati
AI × VLSI × Optimization

📜 License

MIT License
