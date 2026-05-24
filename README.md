# 🩺 Diabetes Classification using Machine Learning

A Machine Learning project that predicts whether a patient is diabetic or not using health-related medical attributes. This project uses classification algorithms like **Logistic Regression** and **Support Vector Machine (SVM)** to analyze and classify diabetes outcomes.

---

## 📌 Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early prediction and detection can help improve healthcare outcomes.

In this project:
- Medical dataset preprocessing was performed
- Data was standardized using `StandardScaler`
- Multiple ML classification models were trained
- Model performance was evaluated and compared

---

## 🚀 Features

✅ Data Cleaning & Preprocessing  
✅ Exploratory Data Analysis  
✅ Feature Scaling  
✅ Logistic Regression Model  
✅ Support Vector Machine (SVM) Model  
✅ Accuracy Comparison  
✅ Prediction System for New Input Data  
✅ Visualization using Matplotlib

---

## 📂 Dataset Features

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose concentration |
| BloodPressure | Blood pressure value |
| SkinThickness | Skin fold thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes hereditary score |
| Age | Age of patient |
| Outcome | 0 = Non-Diabetic, 1 = Diabetic |

---

## 🛠️ Technologies Used

- 🐍 Python
- 📘 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🤖 Scikit-learn
- 📓 Jupyter Notebook

---

## 📈 Machine Learning Models Used

### 1️⃣ Logistic Regression
A supervised classification algorithm used for binary classification problems.

### 2️⃣ Support Vector Machine (SVM)
A powerful classification algorithm that separates classes using hyperplanes.

---

## 📊 Model Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | ~71% |
| SVM | ~72% |

> Accuracy may slightly vary depending on train-test split and preprocessing.

---

## 📁 Project Structure

```bash
Diabetes-Classification/
│
├── Diabetes_prediction.ipynb
├── diabetes.csv
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ParthKohale/Diabetes-Classification.git
```

### 2️⃣ Navigate to Project Folder

```bash
cd Diabetes-Classification
```

### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then run:

```bash
Diabetes_prediction.ipynb
```

---

## 📦 Requirements

Create a `requirements.txt` file with:

```txt
numpy
pandas
matplotlib
scikit-learn
jupyter
```

---

## 🔍 Workflow of the Project

```text
Dataset Collection
        ↓
Data Preprocessing
        ↓
Feature Scaling
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Prediction
        ↓
Performance Evaluation
```

---

## 🎯 Future Improvements

- Add Deep Learning models
- Deploy using Flask/Streamlit
- Add real-time prediction UI
- Improve accuracy with hyperparameter tuning
- Add feature importance visualization

---

## 📸 Sample Output

```python
Input Data → Patient Health Metrics
Prediction → Diabetic / Non-Diabetic
```

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork this repository and improve the project.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Parth**  
AIML Engineering Student passionate about AI, ML, and real-world healthcare applications.

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub and share it with others!
