# myocardial-infarction-using-ML
This project focuses on the detection of myocardial infarction (heart attack) using machine learning techniques. We leverage the PTB diagnostic database, a widely used dataset in the field of cardiology.Myocardial infarction, a critical medical condition, requires prompt diagnosis and treatment. Machine learning algorithms offer the potential to aid healthcare professionals in accurately identifying myocardial infarction cases from electrocardiogram (ECG) data.

Dataset taken from Kaggle - https://www.kaggle.com/datasets/shayanfazeli/heartbeat

Methodology-

Data Preprocessing: Adding labels,normalizing the data,handling the imbalance.

Feature Extraction: Reducing feature size using PCA.

Algorithms Used: KNN , Random forest , SVM

Model Training: Training machine learning models, including but not limited to, Support Vector Machines (SVM), Random Forest, and K-Nearest Neighbours (KNN), on the extracted features.

Model Evaluation: Evaluating the performance of trained models using metrics such as accuracy, sensitivity, specificity, and area under the receiver operating characteristic curve (AUC-ROC).

Deployment: Deploying the best-performing model for real-time or batch prediction of myocardial infarction.

Usage

1.Clone the repository:
git clone https://github.com/yourusername/myocardial-infarction-detection.git

2.Install the required dependencies:
pip install -r requirements.txt

3.Explore the Jupyter notebooks in the notebooks/ directory to understand the data preprocessing, feature extraction, model training, and evaluation processes.

4.Run the notebooks sequentially to replicate our experiments or adapt the code to your specific requirements.

Results
Our experiments demonstrate promising results in myocardial infarction detection using machine learning techniques. The models achieve high accuracy and sensitivity, indicating their potential for assisting healthcare professionals in diagnosing myocardial infarction.

Future Scope - 
Citation - Kachuee, M., Fazeli, S. and Sarrafzadeh, M., 2018, June. Ecg heartbeat classification: A deep transferable representation. In 2018 IEEE international conference on healthcare informatics (ICHI) (pp. 443-444). IEEE.

License
This project is licensed under the MIT License - see the LICENSE file for details.

