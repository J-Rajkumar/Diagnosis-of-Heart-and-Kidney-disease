# Diagnosis-of-Heart-and-Kidney-disease

## Data set source link:
### Heart : https://archive.ics.uci.edu/dataset/45/heart+disease
### kidney: https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease

## Folder structure
This project has two folders namely BackEnd and FrontEnd.   
Used python for BackEnd and Streamlit for FrontEnd

###BackEnd folder
This is code is built in a scalable way so that we can add multiple project and use common code
To train new classification problem you can simply add newtopic.py under BackEnd/train and corresponding resource under BackEnd/resource/topics/newtopic

To predict any topic simply follow the template BackEnd/predict/

### FrontEnd folder
To run FrontEnd, streamlit run FrontEnd/app.py

