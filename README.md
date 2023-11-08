# Stroke Prediction Analysis

## Introduction
This repository contains the analysis and visualization for stroke prediction as part of a bootcamp exercise at [Código Facilito](https://codigofacilito.com/). The dataset utilized in this project is obtained from the Kaggle repository: [Brain Stroke Dataset](https://www.kaggle.com/datasets/jillanisofttech/brain-stroke-dataset/data).
The notebook is in Spanish.

## Objective
The primary goal of this project is to explore and visualize data to predict the likelihood of a stroke. This includes preprocessing the dataset, selecting features, and training a machine learning model.

## Tools and Technologies
- Python
- Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn, scikit-learn, imbalanced-learn

## Project Structure
- `stroke_prediction.ipynb`: Jupyter notebook containing the exploratory data analysis, preprocessing, and machine learning model.
- `brain_stroke.csv`: The dataset used for the analysis.
- `requirements.txt`: A list of Python libraries required to run the notebook.

## Setup
To run this project, install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Analysis Overview
The analysis involves the following steps:
1. Data Cleaning: Handling missing values and incorrect data types.
2. Exploratory Data Analysis: Visualizing distributions and relationships in the data.
3. Data Preprocessing: Encoding categorical variables and normalizing the data.
4. Model Training: Using a RandomForestClassifier and tuning it with GridSearchCV.
5. Model Evaluation: Assessing model performance with cross-validation.

## Results
The analysis provides insights into the key factors that contribute to stroke risk and the performance of the predictive model. Due to the imbalance in the dataset, techniques like SMOTE were applied to improve model performance.

## Contribution
This is an open project, and contributions are welcome. If you have suggestions or want to contribute, please fork the repository and submit a pull request.

## License
This project is open-sourced under the MIT license.

## Acknowledgments
- Kaggle for providing the dataset.
- Código Facilito for the opportunity to learn and apply data science skills.
- All the contributors who have invested time and effort in improving the project.