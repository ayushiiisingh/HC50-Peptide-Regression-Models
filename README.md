# Machine Learning Regression Models for Predicting Hemolytic Concentration (HC₅₀) of Peptides

This repository contains the implementation of machine learning regression models developed as part of my M.Tech thesis titled:

**"Machine Learning Regression Models for Predicting Hemolytic Concentration (HC₅₀) of Peptides Using Curated Activity Data"**

## 📌 Project Summary

Hemolytic peptides can rupture red blood cells and are important for therapeutic drug design. This study focuses on building robust regression models to predict the **hemolytic concentration (HC₅₀)** of peptides using **curated experimental data**, enabling better screening of therapeutic candidates.

---

## 📊 Dataset

- **Total Sequences**: 13,215 peptides
- **Features**:
  - Physicochemical descriptors (via [Pfeature](https://webs.iiitd.edu.in/raghava/pfeature/))
  - Sequence-based k-mer features
- **Target Variable**: HC₅₀ (log-transformed for model training)

---

## ⚙️ Methodology

### 🔬 Feature Extraction:
- Pfeature descriptors (excluding AAC, DPC, SPC, PCP)

### 🧠 Regression Models:
- Random Forest Regressor (RFR)
- Extra Trees Regressor (ETR)
- Deep Neural Networks (DNN)
- BiLSTM (for embedding inputs)

### ✅ Evaluation:
- Cross-validation and independent test set
- Metrics: R², MAE, RMSE, Pearson’s correlation

---

## 🔗 Key Technologies

- Python, scikit-learn, PyTorch, LightGBM, CatBoost
- Jupyter Notebook, Pandas, NumPy, Matplotlib
- Feature Engineering: Pfeature tool

---

👩‍💻 Author
Ayushi Singh
M.Tech, IIIT-Delhi

📜 License
This project is licensed under the MIT License.

🙏 Acknowledgements
IIIT-Delhi, Department of Computational Biology

Thesis supervisor: G.P.S. Raghava

