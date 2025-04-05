# 💳 Credit Card Fraud Detection using Machine Learning

A comprehensive machine learning solution to identify fraudulent credit card transactions — helping financial institutions mitigate losses and enhance customer trust.

---

## 🌐 Problem Statement

With over **$30 billion lost annually** due to credit card fraud, it's critical for financial institutions to adopt intelligent, data-driven fraud detection systems. This project aims to build and evaluate machine learning models that can effectively detect fraudulent credit card transactions from highly imbalanced datasets.

---

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Total Records**: 284,808
- **Fraudulent Cases**: 492 (~0.172%)
- **Features**: 31
  - 28 anonymized via PCA
  - 1 `Time`, 1 `Amount`, 1 `Class` (target)

---

## 🎯 Objectives

- Train ML models to classify transactions as **fraudulent or legitimate**
- Handle class imbalance effectively
- Compare multiple algorithms
- Evaluate model performance using **classification metrics**
- Visualize fraud patterns and insights

---

## 🧠 Algorithms Used

| Model                | Train Accuracy | Test Accuracy |
|---------------------|----------------|---------------|
| K-Nearest Neighbors (K=3 & 7) | 100%          | 100%         |
| Decision Tree        | 100%          | 100%         |
| Support Vector Machine | 97.59%        | ~97%         |
| Logistic Regression  | 93.51%        | 91.88%       |

---

## 🧪 Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC AUC
- Confusion Matrix

> **Note:** Precision and Recall were prioritized due to the high cost of false negatives in fraud detection.

---

## 🧰 Tech Stack & Libraries

- **Languages**: Python
- **Tools**: Jupyter Notebook
- **Libraries**:
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Class Balancing: `imbalanced-learn` (SMOTE)
  - Model Persistence: `joblib`

---

## 📉 Class Imbalance Handling

- **SMOTE (Synthetic Minority Over-sampling Technique)** was used to generate synthetic examples of the minority class, significantly improving the model's ability to detect fraud without overfitting.

---

## 📈 Visualizations & Insights

- Fraud vs Non-Fraud distribution
- Correlation heatmap of features
- Amount and time-based fraud trends
- Confusion matrices for all models

> 📷 *Include screenshots here if uploading to GitHub for visual appeal.*

---

## 📌 Potential Real-World Applications

- Real-time fraud alert systems in banks and fintech apps
- Integration into mobile banking APIs
- Rule-based + ML hybrid decision engines
- Scalable backend microservices for fraud scoring

---

## 🔮 Future Enhancements

- Deploy model as a REST API using Flask or FastAPI
- Create a live web app using Streamlit or Dash
- Use deep learning models (Autoencoders, LSTM)
- Incorporate additional metadata (location, device, etc.)
- Model interpretability using SHAP or LIME

---

## 📄 License

This project is open-sourced under the MIT License.

---

## 🙌 Acknowledgements

- ULB Machine Learning Group (for dataset)
- Kaggle and Scikit-learn Community

---

## 🔗 Connect with Me

- [LinkedIn](https://www.linkedin.com/in/panwar-mayank)
- [Portfolio Website](https://panwar-mayank.streamlit.app)
- [Email](mailto:mayank.panwar.ug22@nsut.ac.in)
- [Email](mailto:mayankpanwar5943@gmail.com)

---

