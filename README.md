#  Handwritten letters recognition

[Презентация](https://docs.google.com/presentation/d/1_aIhxWSQumb78REf4R8cmY15M6yjEAcA5Mjs5CtLui8/edit#slide=id.p) по проекту

### Autor:
- Filichkin Kirill


### Installing dependencies
```console
foo@bar:~$ pip3 install -r requirements.txt
```

##  Source data description
- [dataset](https://www.kaggle.com/datasets/olgabelitskaya/classification-of-handwritten-letters) from kaggle.com, csv file with pictures

## My purposes
Write a model for recognizing handwritten letters

## Used algorithms

  I used: my CNN, ResNet18, DenseNet121, MobileNetV2. The outputs of the last three have been modified.

## Metrics

I used the f1 metric. The F1 measure is a good metric for the handwriting recognition model because it takes into account both precision and completeness (recall). This is especially important when you have unbalanced classes, which is often the case when recognizing handwritten characters. The F1 measure combines both metrics into one, which makes it convenient for evaluating the model in such cases


## Results

Results of training on f1 metrics:

- MyCNN - 0.8094226444217009
- ResNet18 - 0.8712417861233892
- DenseNet121 - 0.8850935009633695
- MobileNetV2 - 0.6255127405806763
