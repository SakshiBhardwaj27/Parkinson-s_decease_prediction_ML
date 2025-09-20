# 🧠 Parkinson’s Disease Prediction

This project applies **Data Science and Machine Learning** techniques to predict the presence of Parkinson’s disease based on biomedical voice measurements. The dataset contains various voice features, and the target variable `status` indicates whether a person is healthy (`0`) or has Parkinson’s disease (`1`).

---

## 📊 Project Overview
- Performed **data preprocessing** (cleaning, EDA, handling outliers, correlation analysis).
- Explored multiple **machine learning models**:
  - Decision Tree  
  - Random Forest  
  - K-Nearest Neighbors (KNN)  
  - AdaBoost  
- Evaluated models using **accuracy, confusion matrix, and classification report**.
- Visualized key insights with **Seaborn and Matplotlib**.

---

## 🗂 Dataset
- Source: `parkinsons.csv`  
- Rows: 195  
- Features: 24 (including biomedical voice features like `MDVP:Fo(Hz)`, `PPE`, `spread1`, etc.)
- Target: `status`  
  - `0` → Healthy  
  - `1` → Parkinson’s disease  

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/parkinsons-disease-prediction.git
cd parkinsons-disease-prediction
pip install -r requirements.txt
