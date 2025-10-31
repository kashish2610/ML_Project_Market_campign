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
- **Language:** Python 🐍  
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
   - Visualize data distributions and correlations.  
   - Identify key patterns influencing customer response.  

3. **Feature Engineering**  
   - Derive new variables from existing ones (e.g., income brackets, purchase frequency).  

4. **Model Building & Evaluation**  
   - Train multiple models (e.g., Logistic Regression, Random Forest).  
   - Evaluate using metrics like Accuracy, Precision, Recall, and F1-score.  
   - Select the best-performing model for prediction.  

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

