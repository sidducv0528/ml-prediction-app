<div align="center">

# 🤖 ML Prediction Web App

### 4 Machine Learning Models · Real-Time Predictions · Zero Backend · Runs in Browser

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-Visit%20App-brightgreen?style=for-the-badge)](https://sidducv0528.github.io/ml-prediction-app)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/sidducv0528/ml-prediction-app)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<br/>

> An interactive web application that simulates **4 trained Machine Learning models** with real-time predictions, feature importance charts, and colour-coded risk indicators — **entirely in the browser, no server required**.

<br/>

![App Preview](https://opengraph.githubassets.com/704dbe096282514337ded746b9b732595df1a5dbd7a40bf9197ea2a2555fed08/sidducv0528/ml-prediction-app)

</div>

---

## 📌 Table of Contents

- [🌐 Live Demo](#-live-demo)
- [🎯 Models & Accuracy](#-models--accuracy)
- [✨ Features](#-features)
- [🧠 How Each Model Works](#-how-each-model-works)
- [🗂️ Project Structure](#%EF%B8%8F-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🛠️ Tech Stack](#%EF%B8%8F-tech-stack)
- [📊 Datasets Used](#-datasets-used)
- [👤 Author](#-author)

---

## 🌐 Live Demo

> **[👉 Click here to open the app](https://sidducv0528.github.io/ml-prediction-app)**

No installation. No login. Just open and predict.

---

## 🎯 Models & Accuracy

| # | Tab | Model Name | Algorithm | Performance |
|---|-----|-----------|-----------|-------------|
| 1 | 📞 Churn Predictor | Customer Churn | Random Forest | **80% Accuracy** |
| 2 | 🏥 Insurance | Premium Predictor | Linear Regression | **R² = 0.875** |
| 3 | 🏦 Bank Deposit | Subscription Predictor | Logistic Regression | **AUC = 0.992** |
| 4 | ❤️ Heart Disease | Risk Predictor | Decision Tree | **96.2% Accuracy** |

---

## ✨ Features

- ⚡ **Real-time predictions** — get results instantly as you adjust sliders and dropdowns
- 📊 **Feature importance bar charts** — visual breakdown of what drives each prediction
- 🟢🔴 **Colour-coded risk indicators** — Green = Safe / Low Risk, Red = At Risk / High Risk
- 📱 **Fully responsive** — works seamlessly on mobile, tablet, and desktop
- 🔒 **No backend, no server** — all logic runs client-side in the browser
- 🎓 **Educational annotations** — each model tab explains the algorithm and dataset context

---

## 🧠 How Each Model Works

<details>
<summary><b>📞 Customer Churn Predictor — Random Forest</b></summary>

Predicts whether a telecom customer will churn (leave) based on account details and usage patterns.

- **Dataset:** IBM Telco Customer Churn — 7,043 records
- **Algorithm:** Random Forest (ensemble of decision trees)
- **Inputs:** Tenure, Monthly Charges, Contract Type, Internet Service, Senior Citizen status, Tech Support
- **Output:** Churn / Not Churn with probability score
- **Accuracy:** 80%

</details>

<details>
<summary><b>🏥 Insurance Premium Predictor — Linear Regression</b></summary>

Predicts the annual health insurance premium based on a patient's personal health profile.

- **Dataset:** Health Insurance dataset
- **Algorithm:** Linear Regression
- **Inputs:** Age, BMI, Number of Children, Smoking status, Gender, Past Hospitalisations
- **Output:** Estimated annual premium (USD)
- **Performance:** R² = 0.875

</details>

<details>
<summary><b>🏦 Bank Term Deposit Predictor — Logistic Regression</b></summary>

Predicts whether a bank customer will subscribe to a term deposit after a marketing call.

- **Dataset:** UCI Bank Marketing — 41,199 records
- **Algorithm:** Logistic Regression
- **Inputs:** Age, Last Call Duration, Campaign Contacts, Account Balance, Job Type, Housing Loan status
- **Output:** Subscribe / Not Subscribe with probability score
- **Performance:** AUC = 0.992

</details>

<details>
<summary><b>❤️ Heart Disease Risk Predictor — Decision Tree</b></summary>

Predicts the presence of heart disease using clinical diagnostic measurements.

- **Dataset:** Cleveland Heart Disease Dataset — 303 patients
- **Algorithm:** Decision Tree (with Z-score + IQR outlier treatment)
- **Inputs:** Age, Serum Cholesterol, Max Heart Rate, ST Depression, Chest Pain Type, Gender
- **Output:** Disease Present / Not Present with risk factors
- **Accuracy:** 96.2%
- ⚠️ *For educational purposes only. Not a medical diagnosis tool.*

</details>

---

## 🗂️ Project Structure

```
ml-prediction-app/
│
├── index.html          # Entire app — all 4 models, UI, CSS & JS in one file
├── .gitignore
└── README.md
```

> The entire application — HTML structure, CSS styling, and JavaScript ML logic — lives inside a single `index.html` file. No frameworks, no build tools, no dependencies.

---

## 🚀 Getting Started

### Option 1 — Use it live (recommended)

👉 Open **[https://sidducv0528.github.io/ml-prediction-app](https://sidducv0528.github.io/ml-prediction-app)** in any browser.

### Option 2 — Run it locally

```bash
# Clone the repository
git clone https://github.com/sidducv0528/ml-prediction-app.git

# Navigate into the folder
cd ml-prediction-app

# Open index.html in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

No `npm install`. No `pip install`. No setup whatsoever.

---

## 🛠️ Tech Stack

| Technology | Role |
|-----------|------|
| **HTML5** | Structure & layout |
| **CSS3** | Dark-themed responsive UI, animations |
| **Vanilla JavaScript** | ML model simulation, prediction logic, chart rendering |
| **GitHub Pages** | Free hosting & live deployment |

> **No external libraries. No frameworks. No backend.** A pure demonstration of what front-end JavaScript can do.

---

## 📊 Datasets Used

| Dataset | Source | Records |
|---------|--------|---------|
| IBM Telco Customer Churn | [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) | 7,043 |
| Health Insurance | [Kaggle](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset) | ~1,300 |
| UCI Bank Marketing | [UCI ML Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing) | 41,199 |
| Cleveland Heart Disease | [UCI ML Repository](https://archive.ics.uci.edu/dataset/45/heart+disease) | 303 |

---

## 👤 Author

<div align="center">

### Siddu Varikuppala

🎓 B.Sc (Honours) · Data Science & AIML · Hyderabad  
📜 IIT Roorkee Data Science  with AI Programme 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddu-data/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sidducv0528)

</div>

---

<div align="center">

⭐ **If you found this project useful, please give it a star!** ⭐

*Part of my Data Science & ML Portfolio*

</div>
