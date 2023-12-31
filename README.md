# Diagnosis-of-Heart-and-Kidney-disease

## Data set source link:
### Heart : https://archive.ics.uci.edu/dataset/45/heart+disease
### kidney: https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease

## Both the topics are binary classification type

## Folder structure
This project has two folders namely BackEnd and FrontEnd.   
Used python for BackEnd and Streamlit for FrontEnd

### BackEnd folder
This code is built in a scalable way so that we can add multiple project and use common code
To train new classification problem you can simply add newtopic.py under BackEnd/train and corresponding resource under BackEnd/resource/topics/newtopic

#### Common packages and steps are located under resource folder as python file
Example: loading csv, loading object, columnformat, feature encoding, model metrics, ml and neural network and hyperparameter tuning.

#### Input Folder:
Both for training and prediction input files are located under corresponding names under topics folder
Example: Kidney train and test input files are located in the following path

train      -->  BackEnd/resource/topics/kidney/input/train/kidney.csv

prediction -->  BackEnd/resource/topics/kidney/input/predict/test1.csv


#### Training
To train any topic simply follow the template located in the following loaction: BackEnd\train
Example: To train kidney dataset, execute following command: python BackEnd\train\kidney.py

#### Prediction 
To predict any topic simply follow the template BackEnd/predict/
Example: To predict kidney normal/abnormal status, execute following command: python BackEnd\predict\kidney.py

#### Feature Importance for kidney dataset

![newplot(1)](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/d1296a5d-37b1-449e-a0d5-483cf66efe6a)



### Model performance metrics comparision for heart

![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/226b3da2-7b8c-43a3-84f2-8720d66ef394)


### Model performance metrics comparision for kidney

![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/0b578ffe-a31e-41be-b32d-49e6c27991f9)



### FrontEnd folder
To run FrontEnd, execute streamlit run FrontEnd/app.py

Please find the screenshots below for FrontEnd

###### key feature: App Navigation option
![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/eb4db8e7-99dc-4afb-af05-2dfda5cedad7)

### Heart
![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/c51f56c6-ee76-41e7-b93f-315a6ce25dc1)
![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/ee916739-95ec-45c7-9ef0-afd02ca2d5a7)
![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/ff8d1830-72f0-4c42-abea-4bf404eaec16)



### Kidney

![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/79a0be1f-b1bb-4027-9351-6a3eb57683b0)
![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/cf05a10f-c8b3-4788-b967-e22578a60d4a)
![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/cd6ff51d-d61c-448b-b206-0b4f505df232)
![image](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/486fcb37-aea9-42ff-92b3-4e33d1b4db06)








