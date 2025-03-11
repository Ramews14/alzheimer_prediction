# Alzheimer's Disease Classification using Random Forest

## Project Description
This project applies **Random Forest Classifier** to predict Alzheimer's disease stages based on clinical and demographic data. The model identifies key features that contribute to classifying individuals as **Demented**, **Nondemented**, or **Converted**.

## Dataset
The dataset includes the following features:
- **Group**: Diagnosis status (Demented/Nondemented/Converted)
- **M/F**: Gender
- **Age**: Patient's age
- **EDUC**: Years of education
- **SES**: Socioeconomic status
- **MMSE**: Mini-Mental State Examination score
- **CDR**: Clinical Dementia Rating
- **eTIV**: Estimated total intracranial volume
- **nWBV**: Normalized whole-brain volume
- **ASF**: Atlas scaling factor

## Project Steps
1. **Data Preprocessing**
   - Handled missing values using appropriate strategies.
   - Encoded categorical variables for model compatibility.
   - Scaled numeric features for improved model performance.

2. **Model Training**
   - Implemented a **Random Forest Classifier**.
   - Applied **SMOTE** to address class imbalance.
   - Tuned hyperparameters using **GridSearchCV** for optimal performance.

3. **Evaluation**
   - Achieved an accuracy score of **0.91** on the test data.
   - Evaluated performance using **classification report** and **confusion matrix**.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/alzheimer-classification.git
