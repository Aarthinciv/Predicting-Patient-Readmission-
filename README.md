
# 📊 Predicting Patient Readmission Using Binary Logistic Regression  
*A machine learning approach for hospital readmission prediction.*  

## 📜 Project Description  
This project examines the likelihood of **diabetes-related patient readmission** within **30 days or after 30 days** of hospitalization using **Binary Logistic Regression**. By analyzing **101,763 patient records** with **47 features**, the study identifies key factors influencing readmission rates and evaluates model performance using multiple metrics.  

### Key Highlights:  
- **Hospital Readmission Analysis:** Investigating patient characteristics and medical history affecting readmission.  
- **Binary Classification:** Predicting readmission status (`1` for readmitted, `0` for not readmitted).  
- **Feature Engineering:** Exploring influential factors like **age, prior hospital visits, medication use, and lab results**.  
- **Data Preprocessing:** Handling missing values, class imbalance, feature scaling, and encoding categorical variables.  
- **Performance Evaluation:** Using **accuracy, recall, precision, F1-score, and ROC-AUC** for model assessment.  

Findings emphasize the **importance of early detection** of high-risk patients and offer insights for **hospital decision-making and healthcare optimization**. 🚀  

---

## 🔍 Research Objectives  
- **Predictive Modeling:** Build a **Binary Logistic Regression model** for **hospital readmission prediction**.  
- **Key Factor Identification:** Determine **significant medical and demographic factors** affecting readmission.  
- **Feature Importance Analysis:** Quantify the impact of **medications, lab results, and emergency visits** on hospital readmissions.  
- **Model Evaluation & Improvement:** Assess performance using **confusion matrix, ROC curves, and classification metrics**.  

---

## 🏗 Technology Stack  
The project uses **Python-based machine learning tools** for predictive modeling:  
- **Data Processing:** `Pandas`, `NumPy`, `Scikit-learn`  
- **Machine Learning Model:** `Binary Logistic Regression`  
- **Data Preprocessing:** Handling missing values, feature encoding, and class balancing  
- **Evaluation Metrics:** `Confusion Matrix`, `Accuracy Score`, `ROC-AUC`, `Precision`, `Recall`, `F1-score`  
- **Visualization:** `Matplotlib`, `Seaborn`, `Plotly`  

---

## 🔢 Data Sources  
The dataset is adapted from **B. Strack et al.'s 2014 research**, containing **101,763 patient records** with **47 features** covering:  
- **Demographics:** Age, gender, race  
- **Medical History:** Prior hospitalizations, diagnoses, medication use  
- **Hospitalization Details:** Admission type, length of stay, discharge disposition  
- **Readmission Status:** Binary target variable (`1` = Readmitted, `0` = Not readmitted)  

---

## 📈 Results & Findings  
- **Influential Factors:** **Number of emergency visits, diagnoses, and diabetes medication usage** impact readmission rates significantly.  
- **Model Accuracy:** **62.1%**, reflecting a moderate ability to predict readmissions.  
- **ROC-AUC Score:** **0.66**, indicating room for improvement in discriminating readmitted vs. non-readmitted patients.  
- **Feature Importance:** Emergency visits (`10.2%` impact), multiple diagnoses (`7.8%`), diabetes medications (`6.4%`).  

The study reinforces the **need for improved predictive models** in healthcare analytics, highlighting areas for enhancement in **feature selection and model optimization**.  

---

## 🚧 Limitations  
- **Class Imbalance:** Fewer readmission cases compared to non-readmission cases, potentially affecting prediction accuracy.  
- **Data Bias:** The dataset focuses on diabetes-related readmission, limiting generalizability to other medical conditions.  
- **Interpretability vs. Accuracy:** While deep learning models may improve accuracy, **Logistic Regression remains preferred for interpretability** in healthcare decisions.  

---

## 🔮 Future Enhancements  
🚀 **Implement ensemble learning** (Random Forest, Gradient Boosting) to improve prediction accuracy.  
🩺 **Explore deep learning models** (ANN, CNN) for more sophisticated patient readmission forecasting.  
📊 **Develop real-time hospital applications** for early identification of high-risk patients.  

---




## 👩‍💻 About Me  
I'm **Aarthi Vijayaragavan**, a **Data Analytics** student at **National College of Ireland**, passionate about AI, healthcare, and predictive analytics. My goal is to leverage **machine learning** for **data-driven healthcare solutions**, focusing on improving hospital outcomes and patient care.  

📧 **aarthiragav6666@gmail.com**  


