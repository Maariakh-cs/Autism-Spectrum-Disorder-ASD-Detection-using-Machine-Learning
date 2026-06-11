# 🧠 Autism Spectrum Disorder (ASD) Detection using Machine Learning

A multimodal Machine Learning framework for early Autism Spectrum Disorder (ASD) detection that integrates **behavioral questionnaires**, **eye-tracking patterns**, and **facial analysis** to improve diagnostic accuracy. The project combines **Random Forest (RF)** and **Support Vector Machine (SVM)** models with **Particle Swarm Optimization (PSO)** for feature optimization and **SHAP-based Explainable AI (XAI)** to provide transparent predictions.

---

## 📌 Overview

Autism Spectrum Disorder (ASD) is a neurodevelopmental condition where early identification can significantly improve intervention outcomes.

Unlike traditional approaches that rely on a single source of information, this project adopts a **multimodal framework** by combining:

- 📝 Behavioral Questionnaire Data
- 👀 Eye-Tracking Features
- 😊 Facial Analysis

The integration of these modalities enables the system to capture a broader range of ASD indicators while improving robustness and interpretability.

---

## 🚀 Features

- 🧠 Multimodal ASD detection framework
- 📊 Behavioral questionnaire analysis
- 👀 Eye-tracking feature extraction
- 😊 Conceptual facial analysis module
- 🤖 Random Forest and Support Vector Machine classifiers
- ⚡ Particle Swarm Optimization (PSO) for feature selection
- 🔍 SHAP-based Explainable AI for model interpretability
- 📈 Performance evaluation using multiple classification metrics

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- SHAP
- Flask
- Particle Swarm Optimization (PSO)

---

## ⚙️ Machine Learning Pipeline

1. Data Collection
2. Data Preprocessing
3. Behavioral Feature Analysis
4. Eye-Tracking Feature Processing
5. Facial Feature Analysis
6. Feature Optimization using PSO
7. Model Training using Random Forest and SVM
8. SHAP-based Explainability Analysis
9. Multimodal Prediction Integration
10. Performance Evaluation

---

## 🤖 Models Used

- Random Forest (RF)
- Support Vector Machine (SVM)
- Particle Swarm Optimization (PSO) for feature optimization
- SHAP Explainability Framework

---

## 📊 Integrated System Performance

| Metric | Score |
|---------|------:|
| **Accuracy** | **90%** |
| **Precision** | **88%** |
| **Recall** | **92%** |
| **F1 Score** | **90%** |
| **ROC-AUC** | **0.93** |

The multimodal integrated system demonstrated improved performance compared to relying on a single diagnostic modality.

---

## 💡 Explainable AI Insights

SHAP analysis identified the following influential factors:

### 📝 Behavioral Module

Most influential questionnaire features:

- A3 (Social Communication)
- A7 (Social Communication)
- A5 (Restricted Behaviors)
- A9 (Restricted Behaviors)

### 👀 Eye-Tracking Module

Key predictors:

- Fixation Duration
- Saccade Variability

### 😊 Facial Analysis Module

- Eye Contact Stability served as a moderate but meaningful predictor.

These findings align closely with recognized behavioral and neurocognitive indicators of ASD.

---

## 💡 Key Highlights

- Built a multimodal ASD detection framework combining behavioral, cognitive, and visual data.
- Integrated Random Forest and Support Vector Machine classifiers for robust prediction.
- Applied Particle Swarm Optimization (PSO) to improve feature selection and reduce redundancy.
- Implemented SHAP-based Explainable AI for transparent and interpretable predictions.
- Achieved **90% Accuracy**, **90% F1 Score**, and **0.93 ROC-AUC** on the integrated system.

---

## 📂 Project Workflow

```text
Behavioral Data
        │
        ▼
Eye-Tracking Data
        │
        ▼
Facial Analysis
        │
        ▼
Feature Optimization (PSO)
        │
        ▼
Random Forest + SVM
        │
        ▼
SHAP Explainability
        │
        ▼
Integrated ASD Prediction
```

---

## 🔮 Future Improvements

- Integration of larger adult facial datasets
- Real-time webcam-based facial analysis
- Deep Learning-based multimodal fusion
- Cloud deployment using Flask/FastAPI
- Clinical decision support dashboard

---

## ⚠️ Disclaimer

This project is intended for educational and research purposes only. It is designed as a decision-support tool and should **not** replace professional medical diagnosis or clinical evaluation.

---

## 👩‍💻 Author

**Maaria Khan**

- GitHub: https://github.com/Maariakh-cs
- LinkedIn: https://www.linkedin.com/in/maariakh-cs/

---

⭐ If you found this project useful, consider giving it a star on GitHub!
