# cardiac-arrhythmia-Prediction

Cardiac Arrhythmia is a condition in which the heartbeat is abnormal. Different medical data mining and machine learning techniques are being implemented to extract valuable information regarding heart disease prediction. But, the accuracy of the desired results is not yet satisfactory. The lack of specialist doctors and increase in wrong diagnosed cases has necessitated the need for building an efficient heart disease detection system. The aim of this project is to classify the ECG signal data of a person into different types of Arrhythmia such as Bradycardia, Tachycardia etc. After appropriate feature selection, the plan is to solve this problem by developing a heart attack prediction system using Deep learning techniques, such as Neural Networks to predict the likely possibilities of Cardiac Arrhythmia in a patient. This project presents a survey of recent techniques for prediction of Cardiac Arrhythmia and their methodologies.

DATA SET:
The dataset for the project is taken from the UCI Machine Learning Repository https://archive. ics.uci.edu/ml/datasets/Arrhythmia (1 csv file, 1 information file ).There are (452) rows, each representing medical record of a different patient.There are 279 attributes like age, weight and patient‟s ECG related data. The dataset is labeled with 16 different classes. Classes 2 to 15 correspond to different types of arrhythmia. Class 1 corresponds to normal ECG with no arrhythmia and class 16 refers to unlabeled patient.The data set is heavily biased towards the no arrhythmia case with 245 instances belonging to class 1 and 185 instances being split among the 14 arrhythmia classes and the rest 22 are unclassified. 3 of the classes related to the degree of AV block do not appear in the data set. The Labels for this data set are obtained from cardiologists and they are considered to be the gold model. The main challenges in processing this data set are the limited number of training examples compared to the number of features, heavy bias towards the case of normal ECG, missing feature values (about 0.33%) and feature values belonging to both continuous and categorical types.

No. CLASS INSTANCES:
1.	Normal 245
2.	Ischemic changes (Coronary Artery) 44
3.	Old Anterior Myocardial Infarction 15
4.	Old Inferior Myocardial Infarction 15
5.	Sinus tachycardia 13
6.	Sinus bradycardia 25
7.	Ventricular Premature Contraction (PVC) 3
8.	Supraventricular Premature Contraction 2
9.	Left bundle branch block 9
10.	Right bundle branch block 50
11.	Left ventricle hypertrophy 4
12.	Atrial Fibrillation or Flutter 5
13.	Others 22



