# Myocardial-Infarction-using-ML (Binary Classification)
This project focuses on the detection of Myocardial infarction (heart attack) using machine learning techniques. We leverage the PTB diagnostic database, a widely used dataset in the field of cardiology.Myocardial infarction, a critical medical condition, requires prompt diagnosis and treatment. Machine learning algorithms offer the potential to aid healthcare professionals in accurately identifying myocardial infarction cases from electrocardiogram (ECG) data.

Dataset taken from Kaggle - https://www.kaggle.com/datasets/shayanfazeli/heartbeat

## Methodology-

## Data Preprocessing:
Added labels, normalized the data, handled class imbalance.

## Feature Extraction: 
Reduced feature size using PCA.

## Algorithms Used:
KNN , Random forest , SVM

## Model Training: 
Training machine learning models, including but not limited to, Support Vector Machines (SVM), Random Forest, and K-Nearest Neighbours (KNN), on the extracted features.

## Model Evaluation: 
Evaluated the performance of trained models using metrics such as accuracy, sensitivity, specificity, and area under the receiver operating characteristic curve (AUC-ROC).

## Usage

1.Clone the repository:
git clone https://github.com/sidd1915/myocardial-infarction-using-ML

2.Install the required dependencies

3.Start Jupyter Notebook:
  jupyter notebook

4.Open the notebook file (.ipynb) to explore and run the code cells.

## Results
Our experiments demonstrate promising results in myocardial infarction detection using machine learning techniques. The models achieve high accuracy and sensitivity, indicating their potential for assisting healthcare professionals in diagnosing myocardial infarction.
<img width="100%" alt="Confusion Matrices" src="https://github.com/user-attachments/assets/e1e27cde-60a4-497d-af64-7419eba67afc">

<img width="100%" height="500" alt="AUC-ROC curves" src="https://github.com/user-attachments/assets/463ac9de-0f4c-4403-bb5f-c5d68dde4a49">


Future Scope - 
Citation - Kachuee, M., Fazeli, S. and Sarrafzadeh, M., 2018, June. Ecg heartbeat classification: A deep transferable representation. In 2018 IEEE international conference on healthcare informatics (ICHI) (pp. 443-444). IEEE.

License
This project is licensed under the MIT License - see the LICENSE file for details.

