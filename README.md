# Forest-Cover-Type-Classification
🌲 Forest Cover Type Classification
   This project predicts the forest cover type from cartographic variables using the UCI Covertype dataset. The dataset contains various geographical and environmental features (e.g., elevation, aspect, slope, soil type, distance to water sources) that influence vegetation growth.

📌 Objective
The goal is to classify the type of forest cover from 7 possible categories based on environmental factors, enabling better land management, ecological studies, and resource planning.

📊 Dataset
Source: UCI Machine Learning Repository

Target Variable: Cover_Type (7 classes)

Features:

Elevation (meters above sea level)

Aspect (degrees from north)

Slope (degree incline)

Horizontal & Vertical Distance to Hydrology

Horizontal Distance to Roadways

Hillshade (at 9am, noon, 3pm)

Horizontal Distance to Fire Points

Wilderness Area (4 binary columns)

Soil Type (40 binary columns)

🔍 Methodology
Data Preprocessing

Handling target label encoding (Cover_Type shifted to start at 0)

Splitting dataset into training and testing sets

Normalizing and standardizing features (optional)

Model Training

Implemented classification models such as:

Random Forest

Gradient Boosting

XGBoost

Used feature_importances_ to identify top predictive features

Evaluation

Accuracy, Precision, Recall, and F1-Score

Confusion matrix to evaluate class-specific performance

🚀 Results
Achieved 85% accuracy using [best model name]

Found Elevation, Soil_TypeX, and Horizontal_Distance_To_Roadways to be the most influential features

🛠 Tools & Libraries
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

 LightGBM 
