# 💳 Credit Card Approval Prediction System

## 📌 Project Overview

The **Credit Card Approval Prediction System** is a Machine Learning-based web application developed to predict whether a customer's credit card application should be approved or rejected. The system analyzes applicant information using trained Machine Learning models and provides quick, reliable, and accurate predictions through an interactive web interface.

---

## 🎯 Problem Statement

Financial institutions receive a large number of credit card applications every day. Manually evaluating each application is time-consuming and may lead to inconsistent decisions. This project automates the approval process using Machine Learning, helping banks make faster, more accurate, and data-driven decisions.

---

## 🚀 Features

- Predicts Credit Card Approval Status
- User-friendly Web Interface
- Machine Learning-based Decision Making
- Fast and Accurate Predictions
- Responsive Web Design
- Easy-to-use Application

---

## 🛠️ Technologies Used

- Python
- Flask
- HTML5
- CSS3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## 🤖 Machine Learning Algorithms

The following Machine Learning algorithms were trained and evaluated:

- Logistic Regression
- Random Forest
- Decision Tree

All three models were trained using the same dataset and evaluated using Accuracy, Precision, Recall, and F1-Score. The best-performing model was selected based on its overall performance.

---

## 📊 Model Performance

| Algorithm | Accuracy |
|------------|----------|
| Logistic Regression | 99.91% |
| Decision Tree | 99.90% |
| Random Forest | 99.95% |

Among all the trained models, **Random Forest** achieved the highest prediction accuracy and better fraud detection performance.

---

## 📂 Project Structure

```
Credit-Card-Approval-Prediction-System
│
├── 1. Brainstorming & Ideation
├── 2. Requirement Analysis
├── 3. Project Design Phase
├── 4. Project Planning Phase
├── 5. Project Development Phase
│   ├── app.py
│   ├── creditcard.csv
│   ├── creditcard.ipynb
│   ├── model.pkl
│   ├── static
│   │     └── style.css
│   └── templates
│         └── index.html
│
├── 6. Project Testing
├── 7. Project Documentation
├── 8. Project Demonstration
└── README.md
```

---

## 📊 Dataset

- **Dataset Name:** Credit Card Dataset
- **File Format:** CSV
- **Purpose:** Used for training and testing Machine Learning models to predict credit card approval.

---

## ⚙️ Installation & Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/aliasuhana2005-lab/Credit-Card-Approval-Prediction-System.git
```

### Step 2: Open the Project Folder

```bash
cd Credit-Card-Approval-Prediction-System
```

### Step 3: Install Required Libraries

```bash
pip install flask pandas numpy scikit-learn joblib
```

### Step 4: Run the Application

```bash
python app.py
```

### Step 5: Open in Browser

```
http://127.0.0.1:5000
```

---

## 📈 Working Process

1. Load the Credit Card Dataset
2. Preprocess the Data
3. Split the Dataset into Training and Testing Sets
4. Train Multiple Machine Learning Models
5. Compare Model Performance
6. Select the Best Performing Model
7. Deploy the Model using Flask
8. Predict Credit Card Approval through the Web Application

---

## 📸 Project Output

The web application accepts applicant details as input and predicts whether the credit card application is likely to be **Approved** or **Rejected** instantly.

---

## 🔮 Future Enhancements

- Deploy the application on IBM Cloud
- Integrate with a Real-Time Database
- User Login and Authentication
- Email Notification System
- Explainable AI for Prediction Results
- Interactive Dashboard and Analytics

---

## 👥 Project Team

This project was developed as part of the **IBM SkillsBuild Internship Program**.

| Role | Name |
|------|------|
| **Team Lead** | **Shaik Alia Suhana** |
| **Team Member** | Karri Kamakshi |
| **Team Member** | Karri Pujitha |
| **Team Member** | Mallampati Bhanu Keerthi |
| **Team Member** | Bellamkonda Venkatesh |

---

## 🔗 GitHub Repository

Repository Link:

https://github.com/aliasuhana2005-lab/Credit-Card-Approval-Prediction-System

---

## 🙏 Acknowledgement

We sincerely thank **IBM SkillsBuild** for providing the opportunity, learning resources, and platform to develop this project. This project enhanced our practical knowledge of Machine Learning, Flask web development, and collaborative software development.

---

## 📄 License

This project has been developed for **educational and academic purposes** as part of the **IBM SkillsBuild Internship Program**.
