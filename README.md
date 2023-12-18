[model_compare.csv](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/files/13700904/model_compare.csv)# Diagnosis-of-Heart-and-Kidney-disease

## Data set source link:
### Heart : https://archive.ics.uci.edu/dataset/45/heart+disease
### kidney: https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease

## Folder structure
This project has two folders namely BackEnd and FrontEnd.   
Used python for BackEnd and Streamlit for FrontEnd

### BackEnd folder
This is code is built in a scalable way so that we can add multiple project and use common code
To train new classification problem you can simply add newtopic.py under BackEnd/train and corresponding resource under BackEnd/resource/topics/newtopic

To predict any topic simply follow the template BackEnd/predict/

### Model performance metrics comparision for heart

[Uploading model_compare.csv,Accuracy,Train Accuracy,Test Accuracy,Precision,Recall,f1-score,roc_auc_score
knn,0.7435064935064936,87.72999999999999,74.35000000000001,0.7481410649218868,0.7435064935064936,0.7435524586310456,0.746
decision_tree,0.9707792207792207,97.35000000000001,97.08,0.9718297053823368,0.9707792207792207,0.9708029692355711,0.972
logistic_regression,0.8701298701298701,84.66,87.01,0.8725528579325966,0.8701298701298701,0.8695098592796803,0.867
naive_bayes,0.8441558441558441,81.58999999999999,84.42,0.8443250164334835,0.8441558441558441,0.8439178333968763,0.842
svc,0.8538961038961039,83.12,85.39,0.8595261242964609,0.8538961038961039,0.8526141749790016,0.849
neuralnetwork,0.8766233766233766,86.89,87.66000000000001,0.8791365403475639,0.8766233766233766,0.8760343663156962,0.874
…]()

### Model performance metrics comparision for kidney


[model_compare.csv](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/files/13700913/model_compare.csv),Accuracy,Train Accuracy,Test Accuracy,Precision,Recall,f1-score,roc_auc_score
knn,0.675,77.14,67.5,0.6850349650349651,0.675,0.6777407696123592,0.674
decision_tree,0.95,96.43,95.0,0.9514354066985646,0.95,0.9495887191539365,0.941
logistic_regression,0.925,89.64,92.5,0.9253808565679793,0.925,0.9251243601759067,0.924
naive_bayes,0.95,94.64,95.0,0.9508571428571428,0.95,0.9501580914055764,0.951
svc,0.9416666666666667,97.14,94.17,0.9419948260994537,0.9416666666666667,0.9417633912479274,0.941
neuralnetwork,0.6,63.57000000000001,60.0,0.36,0.6,0.44999999999999996,0.5




### FrontEnd folder
To run FrontEnd, execute streamlit run FrontEnd/app.py

Please find the screenshots below for FrontEnd

![heartscreen1](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/dfaf8961-24c5-4fe1-9234-ab1ec95e2e4b)

![heartscreen2](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/c3f41a36-6d6e-4820-9e3e-bbc8a6f4aded)


![kidneyscreen1](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/68d9bb53-77fe-41e9-b926-78b017fee99b)

![kidneyscreen2](https://github.com/J-Rajkumar/Diagnosis-of-Heart-and-Kidney-disease/assets/151571679/343e8037-79d5-4929-8495-27bc74dfd5b1)




