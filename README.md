# 🩺 Diabetes Prediction Using Machine Learning

This project uses a machine learning model to predict the likelihood of a person having diabetes based on diagnostic health features.

---

## 📌 SDG Alignment

🎯 *UN Sustainable Development Goal 3: Good Health and Well-being*  
This project contributes to SDG 3 by using AI to improve early detection of chronic diseases like diabetes — enhancing patient outcomes and access to care.

---

## 📊 Dataset

- *Source*: [Plotly GitHub](https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv)
- *Features*:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (target: 0 = No, 1 = Yes)

---

## ⚙️ ML Pipeline

### Tools & Library
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

### Workflow
1. Data loading and inspection
2. Data visualization and exploration
3. Train/test split
4. Model training: RandomForestClassifier
5. Model evaluation: Accuracy, Confusion Matrix, Classification Report

---

## 📈 Model Performance

- *Accuracy*: ~85% (depends on train-test split)
- *Model*: Random Forest (100 trees)

Confusion Matrix and F1-score used to evaluate true positives vs. false positives/negatives.

---

## 🧠 Ethical Reflection

- *Bias*: Dataset may have demographic biases (e.g., age, gender).
- *Fairness*: Model must be carefully monitored before use in real-world diagnosis.
- *Sustainability*: Early diagnosis reduces long-term healthcare costs and mortality.

---

## 📁 Project Structure

## 🚀 Try It Yourself

Open the notebook in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<your-repo>/blob/main/diabetes_model.ipynb)

---

## 👤 Author

- *Name*: Tess
- *GitHub*: [@tess](https://github.com/Tess-cloud)

---

## 📜 License

This project is open-source under the MIT License.
