## Forest Type Classification using Machine Learning

### Project Overview
This project aims to classify forest cover types using machine learning models. The dataset consists of various geographical and ecological features to predict one of seven possible forest cover types. The end-to-end data science pipeline includes data exploration, feature engineering, model building, evaluation, and interpretation.

### Objectives
- Build a reliable classification model to predict forest cover types.
- Compare various models like Logistic Regression, Random Forest, XGBoost, SVM, and LightGBM.
- Optimize models using hyperparameter tuning.
- Evaluate model performance using metrics like Accuracy, F1-Score, and Confusion Matrix.

### Tools & Technologies
- Python: Data Manipulation & Analysis
- Pandas, NumPy: Data Handling
- Matplotlib, Seaborn: Visualization
- Scikit-Learn: ML Model Building
- XGBoost, LightGBM: Advanced ML Models

### Data Overview
Dataset: Forest Type dataset with 581,012 observations and 54 features.
Features: Elevation, Slope, Soil Type, Wilderness Area, and others.
Target: Cover_Type (1 to 7).
The dataset has categorical features (e.g., Wilderness Area, Soil Type) that were one-hot encoded for model training.

### Model Comparison
Model	                Accuracy (%)	F1 Score (%)	Notes
Logistic Regression	    68	          68	        Baseline model
Random Forest	          95	          95	        Strong results without tuning
XGBoost	                93	          93	        Required tuning to improve
SVM	                    63	          63	        Very slow; had to downsample
LightGBM	              96	          96	        Best performer; fast and efficient

### Conclusion:
LightGBM outperformed all other models with an accuracy of 96.6%. Its faster training time and better performance make it the preferred model for this dataset.

🚧 Disclaimer
- My purpose is to get hands-on with data science and in the process:
- Learn new data science tasks (end-to-end), tools, and techniques.
- Document learnings so they can be repeated, updated, and industrialized.


