# LIVER CIRRHOSIS DETECTION

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the disease that are trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Disease :

- Liver Disease

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Liver Disease  | Deep Learning Model      | 78%      |
                       ( Densenet-169 )
                       
==> Python version 3.6.8 was used for the whole project.<br>

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

The Dataset was collected from various MRI and CT scan centres and related hospitals .
Its a self processed dataset and took lots of time for cleaning .
Do support to me through PAYPAL - riteshpanditarp@gmail.com
- [Liver Disease Dataset](https://www.kaggle.com/datasets/riteshpandita/liver-cirrhosis-data-for-deep-learning-analysis)

- [Liver Disease Notebook](https://github.com/riteshpanditarp/LIVER-CIRRHOSIS-DETECTION-USING-DEEP-LEARNING/blob/main/Liver_Disease_Prediction.ipynb)
