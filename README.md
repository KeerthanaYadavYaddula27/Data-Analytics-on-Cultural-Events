# Data-Analytics-on-Cultural-Events

**Dataset Of College Day Cultural Events**
**SL.No**- Series of students count
**TimeStamp**-Time that maximum counts registered
**Name**-Name of the student
**Roll no**- Student Roll no
**Emailid**- Student Email id
**Year**- student Year
**Branch**
**Event**


**Abstract**
This study explores data analytics and predictive modeling techniques applied to college cultural events. By leveraging machine learning algorithms, the project aims to analyze student participation patterns and predict future event attendance. The dataset, sourced from Excel files, undergoes preprocessing, visualization, and classification using Random Forest, Decision Tree, and Logistic Regression classifiers. The results indicate varying prediction accuracies, demonstrating the effectiveness of different machine learning models in event participation forecasting.

**1. Introduction**
Cultural events play a crucial role in student engagement and extracurricular development. Understanding participation trends can help institutions optimize event planning and resource allocation. This project utilizes Python-based data analytics and machine learning techniques to analyze and predict participation patterns in college cultural events. The primary objective is to process the dataset, perform exploratory data analysis (EDA), and classify student participation trends using multiple machine learning models.

**2. Methodology**

2.1 Data Collection and Preprocessing
The dataset is sourced from an Excel file containing details such as timestamp, student name, roll number, email ID, mobile number, year, branch, section, and event name. To ensure data integrity:
- Irrelevant columns such as name, roll number, and email ID were removed.
- Missing values were handled appropriately.
- Categorical data were encoded using Label Encoding.

2.2 Exploratory Data Analysis (EDA)
EDA was performed using Matplotlib and Seaborn to visualize participation distribution:
- Event-wise participation count.
- Distribution of students across branches and years.
- Event participation trends over time.
- Correlation heatmaps for feature analysis.

2.3 Machine Learning Models
The preprocessed data was split into training (80%) and testing (20%) sets. Three classification algorithms were employed:
- **Random Forest Classifier**: A tree-based ensemble model for robust predictions.
- **Decision Tree Classifier**: A simpler tree-based model for interpretability.
- **Logistic Regression**: A statistical model for binary/multiclass classification.

2.4 Model Evaluation
Model performance was evaluated using:
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix for visualizing prediction errors.

**3. Results and Discussion**
The experimental results demonstrated the following accuracies:
- **Random Forest Classifier**: 49%
- **Decision Tree Classifier**: 46%
- **Logistic Regression**: 36%

The Random Forest model outperformed the others, achieving the highest accuracy due to its ensemble nature. The confusion matrix indicated misclassification in low-frequency event categories. Visualization techniques provided insights into participation trends, aiding future event planning strategies.

**4. Conclusion**
This project successfully implemented data analytics and predictive modeling techniques for analyzing college cultural event participation. The findings suggest that machine learning can enhance event forecasting, though improvements in feature engineering and model selection are required for higher accuracy. Future work will focus on incorporating additional features such as student demographics and historical event attendance to improve prediction performance.

**5. References**
- Hastie, T., Tibshirani, R., & Friedman, J. (2009). The Elements of Statistical Learning.
- Pedregosa, F., et al. (2011). Scikit-learn: Machine Learning in Python.
- McKinney, W. (2012). Python for Data Analysis.

**6. GitHub Repository**
The complete source code and dataset can be accessed at: [GitHub Repository Link]

---
This base paper serves as the foundation for documenting your project on GitHub and academic purposes.

