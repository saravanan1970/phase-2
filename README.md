# 🚗 Traffic Accident Analysis and Injury Risk Prediction

This project uses machine learning to analyze and predict the risk of injuries in road traffic accidents based on historical collision data. It provides insights into contributing factors and helps authorities improve traffic safety.

---

## 📊 Dataset

- **Source:** [NYC Open Data - Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- **Format:** CSV  
- **Size:** ~1.5 million records  
- **Key Features:**  
  - Crash time, date, location  
  - Contributing factor  
  - Injuries and fatalities  
  - Vehicle types

---

## ✨ Features

- Parsing and feature extraction from date/time  
- Encoding of categorical variables  
- Outlier handling and scaling  
- Severity scoring based on injuries/fatalities  
- Visual insights via EDA

---

## 🔧 Technologies Used

- **Language:** Python  
- **IDE:** Jupyter Notebook / VS Code  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn (Random Forest, preprocessing, metrics)  
- **Deployment:** Streamlit (optional)  
- **Version Control:** Git

---

## 📈 Model

- **Model Used:** `RandomForestClassifier`  
- **Target Variable:** `HAS_INJURY` (Binary Classification)  
- **Evaluation Metrics:**  
  - Accuracy  
  - Precision & Recall  
  - F1 Score  
  - Confusion Matrix  
  - ROC-AUC

---

## 📊 EDA Examples

- Frequency of crashes by hour/day  
- Heatmap of correlations  
- Boxplots for severity by weekend/weekday  
- Top contributing factors

---

## 🚀 Deployment

- **Deployed Using:** Streamlit Cloud  
- **Demo Link:** [https://traffic-risk-predictor.streamlit.app](#) *(replace with your actual link)*  
- **UI:**  
  - Input: Date, hour, borough, vehicle type, contributing factor  
  - Output: Risk classification (High/Low), severity score

---

## 🔮 Future Enhancements

- Real-time prediction using live GPS and weather data  
- Integration with IoT sensors and smart city platforms  
- Severity estimation in numeric form  
- Generalization for other cities globally

---

## 📁 Getting Started

```bash
git clone https://github.com/yourusername/traffic-accident-prediction.git
cd traffic-accident-prediction
pip install -r requirements.txt
jupyter notebook  # or streamlit run app.py
