# Summary of Findings

## **Key Drivers of Used Car Prices**

### **1. Mileage (Odometer Reading)**
- **Observation**: Cars with lower mileage tend to have higher resale prices due to better perceived condition and reliability.
- **Recommendation**: Prioritize inventory with low odometer readings to appeal to price-sensitive buyers.

### **2. Manufacturer and Model**
- **Observation**: Certain brands (e.g., BMW, Mercedes) and popular models (e.g., Toyota Corolla, Honda Civic) consistently retain higher value.
- **Recommendation**: Stock vehicles from manufacturers and models that are in high demand to maximize profitability.

### **3. Vehicle Condition**
- **Observation**: Vehicles in "excellent" condition command significantly higher prices.
- **Recommendation**: Emphasize the condition of vehicles in marketing efforts and consider condition as a key pricing factor.


## **Folder Structure of Repository**

### **Project Files**
1. **Summary of Findings**: A document summarizing the analysis on used car price prediction, providing insights and actionable recommendations.
2. **Images**:
   - `crisp.png`: Visual representation of the CRISP-DM framework used in the project.
   - `kurt.jpeg`: Additional visuals used to support the analysis.
3. **Saved Models**:
   - `linear_regression_model.pkl`: Serialized Linear Regression model for predictions.
   - `ridge_regression_model.pkl`: Serialized Ridge Regression model for predictions.
4. **Notebooks**:
   - `predictingcarprice.ipynb`: Jupyter Notebook containing code, analysis, and workflow for predicting car prices.
5. **Documentation**:
   - `readme.md`: Overview of the project, instructions for setup, and details of findings.


## **Model Performance Overview**

### **1. Linear Regression**
- **MAE**: 3098.48
- **RMSE**: 4742.28
- **R²**: 0.86
- **Insight**: Linear Regression is a simple and effective baseline model, capturing 86% of the variance in car prices.

### **2. Ridge Regression**
- **Best Alpha**: 0.1
- **MAE**: 3102.53
- **RMSE**: 4730.04
- **R²**: 0.86
- **Insight**: Ridge Regression slightly reduces overfitting and provides performance comparable to Linear Regression.

### **3. Gradient Boosting Regression**
- **Best Parameters**: 
  - `learning_rate`: 0.2
  - `max_depth`: 3
  - `n_estimators`: 300
- **MAE**: 3969.35
- **RMSE**: 5581.38
- **R²**: 0.80
- **Insight**: Gradient Boosting underperformed due to computational constraints limiting hyperparameter tuning.


## **Evaluation Metrics**
- **MAE (Mean Absolute Error)**: Highlights average prediction error magnitude.
- **RMSE (Root Mean Squared Error)**: Penalizes larger errors more heavily, reflecting model accuracy.
- **R² (Coefficient of Determination)**: Explains the proportion of variance captured by the model.


## **Recommendations for Dealers**
1. **Focus on Popular Brands and Models**: Stock vehicles from high-demand manufacturers and top-selling models.
2. **Emphasize Low Mileage**: Promote inventory with low odometer readings to justify higher prices.
3. **Highlight Vehicle Condition**: Ensure marketing materials include detailed descriptions of condition to attract premium buyers.
4. **Utilize Predictive Models**: Deploy Linear or Ridge Regression for pricing decisions due to their simplicity and effectiveness.
5. **Improve Features**: Add detailed metrics like fuel efficiency and safety ratings for better future predictions.

## **Next Steps**
1. **Feature Engineering**: Enhance dataset with additional attributes to capture non-linear patterns.
2. **Optimize Gradient Boosting**: Allocate computational resources to explore advanced tuning for tree-based models.
3. **Continuous Model Updates**: Regularly retrain models with updated data to improve predictive accuracy and relevance.
