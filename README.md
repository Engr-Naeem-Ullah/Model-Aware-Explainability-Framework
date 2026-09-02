# Model-Aware Explainability Framework for Multi-Source Learning

## 📖 Overview

This repository contains the complete implementation of the **Model-Aware Explainability Framework** proposed in the paper:

> *"A Novel Model-Aware Explainability Approach for Multi-Source Learning: An Application to Crop Yield Forecasting"*

The framework introduces two novel methods:

1. **DAAX (Dynamic-Static Ablation with Aggregated SHAP eXplanation)** – A controlled ablation framework to quantify the contribution of semantically grouped feature sets.
2. **S-LAP-XAI (SHAP-Logic Association Patterns XAI)** – A model-aware explainability method that extracts validated, human-interpretable model logic rules from SHAP attributions.

## 🚀 Key Features

- 🔬 **Leakage-safe three-set split** – Training (2006–2014), Validation (2015–2016), Test (2018–2020)
- 📊 **Comprehensive ablation study** – Track 1 (dynamic-only) and Track 2 (dynamic+static)
- 🤖 **10 tabular learning architectures** – XGBoost, CatBoost, LightGBM, TabNet, NODE, FT-Transformer, ExcelFormer, SAINT, DANN, TabPFN
- 📈 **Multi-horizon forecasting** – h=3, 6, 9, 11 months with cumulative aggregates
- 🔍 **S-LAP-XAI rule extraction** – Discovery, Consistency, and Mixed rules with multi-criteria validation

## 🛠️ Installation

### Prerequisites
- Python 3.12+
- pip or conda

