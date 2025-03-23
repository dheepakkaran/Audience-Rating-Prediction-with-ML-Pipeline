# **Audience Rating Prediction with ML Pipeline**

## **Project Overview**
This project focuses on predicting **audience ratings** using a machine learning pipeline. The goal is to analyze audience preferences and trends based on historical data. The model follows a structured approach, including data preprocessing, feature transformation, model training, and evaluation. A **Random Forest Regressor** is used to predict audience ratings, ensuring a balance between performance and interpretability.

---

## **Tools and Technologies Used**

### **Programming Language:**
- **Python**: Used for data processing, machine learning, and evaluation.

### **Libraries and Frameworks:**
- **Pandas**: Handling data loading, preprocessing, and manipulation.
- **Scikit-Learn**:  
  - `train_test_split`: Splitting the dataset into training and testing sets.  
  - `LabelEncoder`: Encoding categorical variables for model compatibility.  
  - `StandardScaler`: Normalizing numerical features to improve model performance.  
  - `RandomForestRegressor`: Machine learning model for audience rating prediction.  
  - `Pipeline`: Automating data transformation and model training for efficiency.  
  - `mean_absolute_error` & `r2_score`: Evaluating model accuracy and predictive power.  
- **Matplotlib & Seaborn**: Visualizing data trends, correlations, and model performance.

---

## **Techniques Implemented**

✅ **Data Preprocessing**  
   - Handling missing values to ensure clean data.  
   - Encoding categorical data for machine learning compatibility.  
   - Scaling numerical features to standardize input data.  

✅ **Machine Learning Pipeline**  
   - Automating data transformation and model training.  
   - Ensuring a modular and efficient ML workflow.  

✅ **Model Training & Evaluation**  
   - Using **Random Forest Regressor** to predict audience ratings.  
   - Measuring model performance using **Mean Absolute Error (MAE)** and **R² Score**.  

✅ **Exploratory Data Analysis (EDA)**  
   - Visualizing feature distributions using **Seaborn & Matplotlib**.  
   - Understanding correlations between different variables.  

---

## **Model Validation & Performance Metrics**
The model successfully captured audience rating trends, although some predictions slightly deviated from actual values. The evaluation metrics are:

- **Mean Absolute Error (MAE)**: `11.3321`  
- **R² Score**: `0.4589`  

These values indicate that the model performs well in identifying overall audience preferences, though improvements can be made with hyperparameter tuning or additional feature engineering.

---

## **Project Insights & Outcomes**
- The machine learning pipeline provided reliable predictions for **audience ratings**.  
- The **Random Forest Regressor** captured audience preferences, although minor prediction differences were observed.  
- The project showcases the importance of **data preprocessing, feature engineering, and model evaluation** in a structured ML workflow.  
- Further **hyperparameter tuning and additional data sources** could enhance model performance.  

---

## **Installation & Usage**
1. Clone this repository:
   ```bash
   git clone https://github.com/dheepakkaran/audience-rating-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd audience-rating-prediction
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook
   ```

---

## **Where I Learned & Implemented This**
- **Hands-on Practice in Google Colab**  
- **Self-research and Online Learning Resources**  
- **Machine Learning Courses & Real-World Applications**  

---

## **Contributing**
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 🚀 **Let's Connect!**
If you have any questions or suggestions, feel free to connect with me on **[LinkedIn](https://www.linkedin.com/in/dheepak-karan-es/)**!

