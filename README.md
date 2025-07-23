# 🩺 Healthcare Diagnosis Prediction with Machine Learning

A classification-based machine learning project designed to predict medical diagnoses from healthcare datasets. This project includes preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 🚀 Features

- Cleaned and preprocessed healthcare data  
- Feature encoding and normalization  
- Multiple classification models for comparison  
- Performance metrics: Accuracy, Precision, Recall, F1-score  
- Visual tools: Confusion matrices and data distributions

---

## 📊 Dataset

**Healthcare Patient Records**
- Demographic information: Age, Gender  
- Medical metrics: Blood Pressure, Glucose Level, BMI, etc.  
- Target: Diagnosis (Binary or Multiclass labels)

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.7 or later  
- `pip` or other package manager

### 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/healthcare-diagnosis-ml.git
cd healthcare-diagnosis-ml
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook Healthcare_Diagnosis_Prediction.ipynb
```

---

## 🧠 Model Architecture

Three models were trained on the dataset:

- **Logistic Regression**  
- **Random Forest Classifier**  
- **XGBoost Classifier**

Each model was evaluated using standard metrics and confusion matrices.

---

## 📈 Performance

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 34%      |
| Random Forest       | 32%      |
| XGBoost             | 33%      | 

✅ **Logistic Regression** was chosen as the best-performing model for further use due to its superior generalization and class balance.

---

## 🔍 Evaluation & Visualizations

- Confusion Matrix for each model  
- Correlation heatmaps for features  


---

## 🛠️ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn

---

## 🔮 Future Improvements

- Add SHAP or LIME for model explainability  
- Explore Machine learning models for more complex patterns  
- Integrate real-time health records (EHR systems)  


---

## 📝 License

This project is open source and available under the MIT License.
