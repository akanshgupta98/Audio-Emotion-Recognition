# Audio-Emotion-Recognition
This project has been done taking 2 dataset. 
RAVDESS data-set. picked from kaggle. This is a audio only dataset. 
Link for RAVDESS dataset: https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio
Size of dataset= 536 MB.
Another dataset used is SAVEE DATASET.
Link for SAVEE dataset: https://www.kaggle.com/barelydedicated/savee-database
Size of dataset= 155 MB.
Emotion recognition is a complex task as it is subjective. 
Here many techniques have been used. 
Total of 8 emotions were detected.
No of instances in RAVDESS: 1440
Accuracies obtained for RAVDESS:70.83 %
RAVDESS DATASET
Logistic Regression : 52.78 %
Random Forest       : 61.81 % 
MLP Classifier      : 68.75 %
CNN                 : 70.83 %
SVM                 : 70.13 %
KNN                 : 61.11 %
Naive-Bayes         : 36.45 %

No of instances in SAVEE: 480
Max accuracy obtained for SAVEE : 75 %
SAVVEE DATASET
Logistic Regression : 70.83 %
Random Forest       : 68.75 % 
MLP Classifier      : 75.00 %
CNN                 : 61.46 %
SVM                 : 70.83 %
KNN                 : 63.54 %
Naive-Bayes         : 48.95 %

No of instances in RAVDESS and SAVEE combined: 1920
Max accuracy obtained for combination of ravdess and savee dataset: 68 %
RAVDESS AND SAVVEE COMBINED DATASET
Logistic Regression : 44.01 %
Random Forest       : 60.68 % 
MLP Classifier      : 68.22 %
CNN                 : 65.46 %
SVM                 : 68.22 %
KNN                 : 58.33 %
Naive-Bayes         : 29.42 %
