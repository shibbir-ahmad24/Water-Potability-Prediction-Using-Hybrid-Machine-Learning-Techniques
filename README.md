# Water Potability Prediction Using Hybrid Machine Learning Techniques

### **Problem**
Access to safe drinking water is a fundamental human right, yet millions of people worldwide lack reliable access to potable water. Contaminated water poses significant health risks, leading to diseases and even death. Ensuring water safety requires robust predictive models to determine potability based on various chemical and physical properties of water. 

### **Solution**
The project aimed to develop a machine learning model that accurately predicts water potability. Multiple algorithms were employed, including Logistic Regression, Random Forest, LightGBM, K-Nearest Neighbors (KNN), and a custom Hybrid Model. The models were trained using historical water quality data and validated on test datasets to assess their performance.

### **Impact**
The developed Hybrid Model achieved the highest accuracy, precision, recall, and F1-score, significantly improving water potability predictions. This model can be used by water safety authorities to assess the safety of drinking water and take preventive measures, thereby reducing the risk of waterborne diseases and enhancing public health.

### **Technology Used**
- **Python**
- **Machine Learning**
- **Numpy**
- **Pandas**
- **Scikit-learn**

### **Dataset**
- **Dataset Link:** [Link to Dataset](#)
- **Features Description:**
  1. **pH**: pH of water (0 to 14).
  2. **Hardness**: Capacity of water to precipitate soap in mg/L.
  3. **Solids**: Total dissolved solids in ppm.
  4. **Chloramines**: Amount of Chloramines in ppm.
  5. **Sulfate**: Amount of Sulfates dissolved in mg/L.
  6. **Conductivity**: Electrical conductivity of water in μS/cm.
  7. **Organic_carbon**: Amount of organic carbon in ppm.
  8. **Trihalomethanes**: Amount of Trihalomethanes in μg/L.
  9. **Turbidity**: Measure of light emitting property of water in NTU.
  10. **Potability**: Indicates if water is safe for human consumption. Potable - 1 and Not potable - 0.

### **Method**
- **Data Load**: Imported the dataset into Python using Pandas.
- **EDA (Exploratory Data Analysis)**: Analyzed the dataset for missing values, outliers, and feature distributions.
- **Data Cleaning**: Handled missing values and outliers, ensuring data quality.
- **Data Sampling**: Split the dataset into training and testing sets.
- **Normalization**: Scaled the feature data to improve model performance.
- **Model Training**: Trained multiple machine learning models on the training dataset.
- **Model Testing**: Evaluated the models on the testing dataset using various performance metrics.
- **Comparative Result Analysis**: Compared the models based on accuracy, precision, recall, and F1-score.
- **Summary**: Highlighted the best-performing model and discussed its potential applications.

### **Analysis Visuals**
[Include visualizations here: e.g., model performance comparison charts, feature importance plots]

### **Comparative Analysis**

**Accuracy:**
The **Random Forest**, **LightGBM**, and **Hybrid Model** exhibit the highest accuracy (0.62), outperforming Logistic Regression (0.48) and KNN (0.51).

# **Precision**
The Hybrid Model leads in precision (0.62), slightly surpassing Random Forest (0.58) and LightGBM (0.59). Logistic Regression and KNN trail behind with 0.46 and 0.48, respectively.

## **Recall**
The **Hybrid Model** achieves the highest recall (0.62), matching **Random Forest** and slightly exceeding **LightGBM** (0.60). **Logistic Regression** shows a higher recall (0.59) compared to **KNN** (0.47).

### **F1-Score**
The **Hybrid Model** has the highest F1-Score (0.62), followed by **Random Forest** and **LightGBM** (both 0.60). **Logistic Regression** and **KNN** score lower at 0.51 and 0.47, respectively.

### **Summary**

The **Hybrid Model** outperforms other models across all metrics, closely followed by **Random Forest** and **LightGBM**. **Logistic Regression** and **KNN** underperform in comparison, particularly in terms of accuracy, precision and F1-Score.

