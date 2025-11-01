#  Market Campaign Analysis using Machine Learning

##  Project Overview  
This project focuses on analyzing and predicting the success of marketing campaigns using machine learning techniques.  
By exploring customer data, the model identifies key features influencing customer responses and helps businesses design more effective, targeted campaigns.

---

##  Objective  
Many companies run marketing campaigns but often struggle to identify which customers are most likely to respond positively.  
This project aims to:
- Understand customer behavior through data analysis.  
- Build a predictive model to classify whether a customer will respond to a campaign.  
- Generate insights that can optimize future marketing strategies.

---

##  Dataset  
- **File:** `superstore_data.csv`  
- **Description:** Contains information about customers, their demographics, past purchases, and responses to marketing campaigns.  
- **Key Columns:**  
  - `Age`  
  - `Gender`  
  - `Income`  
  - `Spending_Score`  
  - `Response` *(target variable — whether the customer responded to the campaign)*  

---

##  Tech Stack  
- **Language:** Python   
- **Tools & Libraries:**  
  - pandas, numpy — data manipulation  
  - matplotlib, seaborn — data visualization  
  - scikit-learn — model training & evaluation  
  - Jupyter Notebook — experimentation environment  

---

##  Project Workflow  
1. **Data Loading & Cleaning**  
   - Handle missing values, duplicates, and inconsistent data.  
   - Encode categorical variables.  

2. **Exploratory Data Analysis (EDA)**  
   - Analyse distributions of key features using **bar charts** and **box plots**.  
   - Capture customer behaviour patterns and relationships between variables.  
   - Perform **binning and segmentation** to categorize continuous variables and identify meaningful groups for analysis.    

3. **Feature Engineering**  
    - **Encoding:** Convert categorical variables into numerical formats suitable for machine learning models (e.g., one-hot encoding or label encoding).  
   - **Train-Test Split:** Partition the dataset into training and testing sets to evaluate model performance reliably.  
   - **SMOTE (Synthetic Minority Oversampling Technique):** Apply oversampling to balance classes in the target variable, addressing class imbalance issues.  

4. **Model Building & Evaluation**  
   The following algorithms were developed and optimised:  
   - **AdaBoost Classifier** using `GridSearchCV` for hyperparameter tuning.  
   - **Gradient Boosting Classifier** using `RandomizedSearchCV`.  
   - **XGBoost Classifier**, with hyperparameters tuned via `Optuna`.  
   - **LightGBM Classifier**, hyperparameters tuned via `Optuna`.  
 

5. **Insights & Interpretation**  
   - Determine the most important features driving campaign success.  
   - Recommend strategies for customer targeting and segmentation.  

---

## Results  
- The best-performing model achieved:  
  - **Accuracy:** ~85%  
  - **Precision:** ~82%  
  - **Recall:** ~80%  
- **Key Insights:**  
  - Middle-aged customers with medium-to-high income are more responsive.  
  - Previous purchases strongly correlate with campaign success.  
  - Personalized offers improve conversion rates significantly.  

---

##  How to Run the Project  

### Clone the Repository  
git clone https://github.com/kashish2610/ML_Project_Market_campign.git
cd ML_Project_Market_campign

