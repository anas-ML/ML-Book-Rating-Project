# **Books Rating Prediction**

### **Project Overview**
This project aims to predict the average ratings of books using the Goodreads dataset. The analysis involves comprehensive data cleaning, exploratory data analysis (EDA), feature engineering, and the application of machine learning models. Various regression models were tested and evaluated with relevant performance metrics.

The final feature engineering step includes leveraging historical statistics (e.g., average ratings and ratings count) for authors and publishers, while avoiding data leakage. The insights derived from this project can be valuable for publishers and book enthusiasts to understand patterns in book ratings.

---

### **Dataset**
- **Source**: Goodreads  
- **Columns**:  
  - `title`, `average_rating`, `isbn`, `isbn13`, `language_code`, `num_pages`, `rating_count`, `text_reviews_count`, `publication_date`, `publisher`, `author_1`

---

### **Key Steps in the Project**

1. **Data Cleaning**:  
   Focused on ensuring dataset quality by handling missing or inconsistent data, standardizing formats, and preparing features for analysis and modeling.

2. **Exploratory Data Analysis (EDA)**:  
   Conducted a thorough exploration to identify trends, distributions, correlations, and potential outliers to guide feature selection and engineering.

3. **Feature Engineering**:  
   Transformed and enhanced features to improve predictive power. Included deriving new features, addressing imbalances, and incorporating author/publisher statistics while mitigating data leakage risks.

4. **Model Training and Evaluation**:  
   - Tested five regression models:  
     - Linear Regression  
     - Decision Tree  
     - Random Forest  
     - Support Vector Machine (SVM)  
     - Multi-Layer Perceptron (MLP)  
   - **Best Model**: Random Forest, though overall performance metrics were suboptimal.

5. **Final Improvements**:  
   - Enhanced author and publisher statistics application to prevent leakage and support generalization, which resulted in good model performance.

---

### **How to Use**

1. **Install Dependencies**:  
   Run the following command to install required libraries:  
   ```bash  
   pip install -r requirements.txt  
