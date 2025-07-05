
# 🎓 AI-Based Student Performance Prediction App

This project leverages machine learning to predict student performance based on historical academic data, behavioral patterns, and lifestyle choices. It is designed to help students, educators, and institutions make data-driven decisions to improve academic outcomes.

---

## 🔍 Overview

The app predicts a student's likely academic score using the following features:

* 📘 Previous exam marks
* 💤 Sleep duration
* 📚 Study hours
* 🏃‍♀️ Extracurricular activity participation
* 📝 Sample question paper results

The trained model outputs both the **predicted score** and a **performance index** (High, Medium, Low) to indicate the student's academic risk level.

---

## 🛠️ Technologies Used

| Category      | Tools / Libraries               |
| ------------- | ------------------------------- |
| Language      | Python 3.x                      |
| ML Framework  | XGBoost, Scikit-learn           |
| Data Handling | Pandas, NumPy                   |
| Visualization | Matplotlib, Seaborn             |
| UI            | Flask, HTML, CSS                |
| Environment   | Google Colab / Jupyter Notebook |

---

## 📁 Files and Folders

```
.
├── Main_project.ipynb      # Core notebook for model training & testing
├── xgboost_model.pkl       # Saved model file (generated after training)
├── merged_file.xlsx        # Input dataset for training
├── app.py                  # Flask app (if implemented)
├── templates/
│   └── index.html          # Frontend HTML (if implemented)
└── README.md               # Project documentation
```

---

## 📈 Model Summary

* **Algorithm**: XGBoost Regressor
* **Performance Metric**: R² Score
* **Output**: Predicted academic percentage + Performance level (High / Medium / Low)

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/student-performance-app.git
cd student-performance-app
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Notebook

Launch `Main_project.ipynb` in Jupyter or Google Colab and execute all cells.

### 4. Optional: Run Flask App

```bash
python app.py
```

---

## 📊 Sample Output

| Input                 | Value    |
| --------------------- | -------- |
| Study Hours           | 3.0      |
| Sleep Hours           | 7.5      |
| Extracurricular       | Yes      |
| Previous Marks        | 82%      |
| Sample Paper Score    | 78%      |
| **Predicted Marks**   | `84.21%` |
| **Performance Index** | `High`   |

---

## 💡 Future Enhancements

* Add user login and dashboard
* Enable CSV data upload for batch prediction
* Mobile responsive UI
* Daily/weekly study planner generation
* Export prediction reports

---



