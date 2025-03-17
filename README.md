# Loan Eligibility Prediction  
*A Machine Learning-based approach to automate and optimize the loan approval process.*

## Overview  
This project aims to **predict loan eligibility** using **machine learning models** trained on financial and demographic data. The system automates the loan approval process by analyzing key indicators such as **credit history, income level, and loan amount**. The final model is deployed as a **web application on AWS EC2**, ensuring real-time and scalable predictions.

## Objectives  
- ✅ Automate loan eligibility assessment using **machine learning models**.  
- ✅ Enhance accuracy and efficiency compared to traditional approval methods.  
- ✅ Deploy a **web-based application** for real-time loan predictions.  
- ✅ Optimize models for **higher precision and recall**.  

##  Key Statistics & Findings  
### Dataset  
-  **4,269 data points** from a [Kaggle dataset](https://www.kaggle.com/)  
- Includes **13 features** representing financial and personal information.  
- Processed using **feature engineering and normalization** techniques.  

### Machine Learning Model Performance  
| Model                 | Accuracy | Precision | Recall |  
|----------------------|----------|-----------|--------|  
| **Logistic Regression** | **78%** | **80%** | **76%** |  
| Decision Trees      | 75% | 77% | 74% |  
| **Random Forest** | **83%** | **85%** | **81%** |  
| **XGBoost** (Best) | **87%** | **88%** | **86%** |  

### Deployment Details  
-  **Web application deployed on AWS EC2** for real-time loan prediction.  
-  Backend developed using **Flask** to handle user input and model inference.  

##  Technologies & Tools Used  
-  **Python** (Pandas, Scikit-learn, XGBoost, Flask)  
-  **Jupyter Notebook** for model training and evaluation  
-  **AWS EC2** for cloud deployment  
-  **Flask & Streamlit** for web-based UI  

##  Future Scope  
- **Enhancing model accuracy** using deep learning models.  
- **Integrating external credit history APIs** for better feature enrichment.  
- **Expanding dataset size** to improve model generalization. 
