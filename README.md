#  Handwritten letters recognition
HSE ML course project (2nd year)

### Autor:
- Filichkin Kirill


### Installing dependencies
```console
foo@bar:~$ pip3 install -r requirements.txt
```

##  Source data description
- [dataset](https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format) from kaggle.com, csv file with pictures

## Our purposes
Write a model for recognizing handwritten letters

## Used algorithms

The dataset has already been pre-processed well, so the Standard Scaler was used to normalize the values, and the "random forest" and CNN architecture were used to train the model

## Metrics

I used the f1 metric. The F1 measure is a good metric for the handwriting recognition model because it takes into account both precision and completeness (recall). This is especially important when you have unbalanced classes, which is often the case when recognizing handwritten characters. The F1 measure combines both metrics into one, which makes it convenient for evaluating the model in such cases


## Results
The result of the work were two trained models

- RandomForestClassifier : 0.9875
- CNN : 0.7166
