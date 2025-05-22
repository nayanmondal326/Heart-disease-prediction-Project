# Heart-disease-prediction-Project
#❤️ Heart Disease Prediction
This project aims to predict the presence of heart disease in patients using a supervised machine learning approach on structured clinical data. The project uses various preprocessing techniques and classification models to analyze patient records.

#📊 Dataset
The dataset is loaded from a CSV file (heart.csv).

It contains patient data including age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, and more.

The target variable is target (1 = presence of heart disease, 0 = absence).

🔍 Data Preprocessing
Checked for null values (none found).

Removed duplicate records to ensure data integrity.

Split the data into features (X) and target (y).

Applied both Standardization and Normalization:

StandardScaler for centering and scaling.

Normalizer for scaling each sample to unit norm.

🧠 Machine Learning Models
1. Support Vector Classifier (SVC)
Kernel used: 'rbf'

Trained and evaluated on:

Raw features

Standardized features

Normalized features

Accuracy score computed for each variant.

2. Decision Tree Classifier
Criterion: 'entropy'

Also evaluated with standardized and normalized features.

Performance compared with SVC.

🧪 Model Testing
Used train_test_split with 80/20 ratio.

Evaluated each model on unseen test data.

Performed prediction for individual patients to demonstrate inference capability.

📈 Key Insights
Preprocessing significantly impacts model performance.

Both SVC and Decision Tree showed high predictive capabilities.

The system is capable of making real-time predictions on new patient data.

✅ Project Highlights
Clean preprocessing pipeline with no missing values.

Comparative model analysis with SVC and Decision Tree.

Includes individual prediction example using processed features.

Ready for deployment or integration into medical diagnostic tools.
