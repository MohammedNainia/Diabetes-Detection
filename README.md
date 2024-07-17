  Diabetes Prediction System

Welcome to the Diabetes Prediction System project. This project aims to predict diabetes using a dataset of various health metrics. Below you'll find an overview of the tools used, the dataset, and the process followed to build and evaluate the model.

   Tools and Libraries Used

- Pandas for data manipulation and analysis
- Matplotlib and Seaborn for data visualization
- Scikit-learn for model building and evaluation

   Dataset

The dataset contains 768 entries with the following health-related features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome

   Project Workflow

1.   Data Loading
   - Loaded the dataset from a CSV file located at `diabetes.csv`.

2.   Data Inspection
   - Used `df.info()` to check the dataset's structure and ensure there were no missing values.

3.   Exploratory Data Analysis (EDA)
   - Visualized data distributions and relationships to better understand the dataset.

4.   Model Building
   - Used a Random Forest Classifier to build the predictive model.

5.   Model Evaluation
   - Assessed the model's performance using metrics like accuracy, confusion matrix, and ROC AUC score.

   Key Takeaways

- The importance of thorough data inspection and preprocessing
- Visualization helps in understanding data patterns and relationships
- Random Forest Classifier proved effective for this classification task

   


