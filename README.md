
# Heart_Disease

## Table of content

1. [Abstract](https://github.com/adijams01/cleveland_heart_disease_classification/blob/main/README.md#abstract)
2. [Data](https://github.com/adijams01/cleveland_heart_disease_classification/blob/main/README.md#data)
3. [Results](https://github.com/adijams01/cleveland_heart_disease_classification/blob/main/README.md#results)
4. [Refrences](https://github.com/adijams01/cleveland_heart_disease_classification/blob/main/README.md#refrences) 
5. [Contributors](https://github.com/adijams01/cleveland_heart_disease_classification/blob/main/README.md#contributors)

## abstract

heart diseases are now-a-days very common, so we developed Deep Learning model where it predicts a person is having heart disease or not, by taking 13 attributes as input

There are 13 attributes
1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
* Value 0: typical angina
* Value 1: atypical angina
* Value 2: non-anginal pain
* Value 3: asymptomatic
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
* Value 0: normal
* Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
* Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
* Value 0: upsloping
* Value 1: flat
* Value 2: downsloping
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
and the label

We used [binary classification](https://en.wikipedia.org/wiki/Binary_classification#:~:text=Binary%20classification%20is%20the%20task,basis%20of%20a%20classification%20rule.) algorithm in our model to predict results

## Data

we got Data from [kaggle](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
and it looks like this

![WhatsApp Image 2022-11-25 at 11 20 13 AM](https://user-images.githubusercontent.com/92617405/203923874-cc815f3f-618a-44e6-98eb-1f2b15f9282b.jpeg)


## Results

We got the following results

* loss: 0.4518 - accuracy: 0.8111

* Confusion matrix
![WhatsApp Image 2022-11-25 at 11 21 15 AM](https://user-images.githubusercontent.com/92617405/203923888-363e2435-0674-474b-b593-5880443b88f7.jpeg)

## Refrences

https://github.com/mrdbourke/tensorflow-deep-learning
## Contributors

[Chandu Bayyavarapu](https://github.com/Chandu106)

[Aaditya nair](https://github.com/ad5454)


