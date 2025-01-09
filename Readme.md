### Binance Prediction using Machine Learning  

#### **Project Overview**  
This project aims to predict Binance price trends using various machine learning models, including Decision Trees, Random Forests, Deep Neural Networks (DNN), LightGBM, and XGBoost. The dataset consists of historical market data, and the objective is to classify price movements (e.g., "Price Up," "Price Down") or predict continuous price values.  

---

#### **Key Features**  
- **Models Used**: Decision Trees, Random Forests, DNN, LightGBM, XGBoost  
- **Data Handling**: Addressed class imbalance using SMOTE  
- **Evaluation Metric**: Accuracy
  - XGBoost baseline model performed better than the tuned version.  
  - Other models such as Random Forests and LightGBM offered competitive results.  

---

#### **Usage**  
1. **Preprocess the Data**:  
   - Normalize, engineer features, and handle missing values.  
   - Apply SMOTE for class imbalance if applicable.  

2. **Train Models**:  
   - Experiment with different models using the provided scripts.  

3. **Evaluate Results**:  
   - Assess model performance using accuracy
   - Compare model performance across different models.
#### **Future Work**  
- Improve feature engineering by incorporating domain-specific indicators.  
- Perform advanced hyperparameter tuning (e.g., Optuna, Bayesian Optimization).  
- Optimize the DNN architecture and explore transformer-based models.  