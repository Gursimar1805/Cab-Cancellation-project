🚖 Cab Booking Cancellation Prediction using Machine Learning
This project aims to build a predictive machine learning model to identify and analyze factors leading to cab booking cancellations. The solution helps improve business decisions, reduce operational inefficiencies, and enhance customer experience.

📌 Project Overview
Cab booking platforms often suffer losses due to unexpected cancellations. This project analyzes historical cab booking data to:

Detect patterns in canceled vs. completed rides

Identify key factors contributing to cancellations

Build classification models to predict the likelihood of a booking being canceled

🗃️ Dataset
The dataset contains details such as:

Booking and travel dates

Travel types and categories

City, distance, customer ID

Cancellation labels (0 = Completed, 1 = Cancelled)

Note: Dataset is not public. Available upon request or used only for academic purposes.

🧠 Machine Learning Workflow
1. Data Preprocessing
Handled missing values

Parsed and extracted features from datetime columns (weekday, month, lead time)

Label encoding and data type handling

2. Exploratory Data Analysis (EDA)
Analyzed cancellation trends over weekdays, months, travel types, etc.

Visualized feature distributions and class imbalance

3. Feature Engineering
Created custom features: lead time, weekend travel, same-day booking, etc.

Converted categorical variables

4. Model Building
Applied classification models:

Logistic Regression

Decision Tree

Random Forest

Used confusion matrix and classification reports for evaluation

5. Model Evaluation
Metrics used: Accuracy, Precision, Recall, F1-score

Identified misclassification trends and improved with feature selection

✅ Key Results
Random Forest achieved the best performance on test data

Key features impacting cancellations:

Travel Type ID

Booking lead time

Day of travel (weekday/weekend)

City and distance

