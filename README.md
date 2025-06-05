# drug-discovery-stack-regressor
AI-XAI based pIC50 prediction using ensemble modeling and explainability tools (SHAP, LIME)
# 🧪 Drug Discovery Stack Regressor

**An Explainable AI Framework for Predicting pIC50 in Drug-Like Compounds**

This repository presents a summary of our research on integrating machine learning with explainable AI (XAI) to predict pIC50 values for drug discovery. The models are designed using Random Forest, SVR, and MLP, and combined using a stacking ensemble. SHAP and LIME are used to interpret both global and local feature contributions.

📄 **[Read the full paper here](paper/drug_discovery_paper.pdf)**

---

## 🔍 Overview

- **Task**: Predict pIC50 values from molecular descriptors
- **Models Used**:
  - Random Forest (RF)
  - Support Vector Regression (SVR)
  - Multi-Layer Perceptron (MLP)
  - Stacked Regressor (Ridge meta-model)
- **Interpretability**: SHAP and LIME
- **Dataset**: COVID-19 compound descriptors (Drug Discovery Hackathon)

---

## 📊 Key Results

| Model                 | MSE  | R²   | MAE  |
|----------------------|------|------|------|
| Random Forest         | 0.25 | 0.82 | 0.39 |
| SVR                   | 0.32 | 0.78 | 0.43 |
| MLP                   | 0.26 | 0.81 | 0.40 |
| **Stack Regressor**   | ✅ **0.18** | ✅ **0.88** | ✅ **0.32** |

---

## 📈 Explainability Plots

### 🔹 SHAP Summary Plot
![SHAP Summary](SHAP.png)

### 🔹 LIME Explanation (Sample)
Open [`lime_explanation.html`](LIME.png) to explore local feature influences.

---

## 🚫 Code Availability

The source code is not publicly available at this time. For collaborations or academic inquiries, please contact the authors.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
