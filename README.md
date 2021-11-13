# Binary-classification

Binary classification is the task of classifying the elements of a set into two groups. 

This is a example for using clinical data to predict whether PC (Pancreatic Cancer) patients suffer from cachexia.

python code on Google Colab:
https://colab.research.google.com/drive/1CYD7xDIDa2LKFAS3cb3eEHUVFCHueUeP#scrollTo=wn0hEDhiobLR

## Introduction

Cachexia is a multifactorial metabolic syndrome characterized by ongoing muscle wasting (including skeletal muscle and cardiac muscle), loss of weight, and muscle atrophy. Cachexia is associated with cancer and other chronic diseases. Importantly, the prevalence of PC-associated cachexia is approximate 70% which is the highest rate in different types of cancer. 

In this clinical data, it has 15 independent variables. Then construct 3 different models: NN (Neural Network), SVM (Support Vector Machine), and XGBoost (eXtreme Gradient Boosting) to predict which patients suffer from cachexia.

## Result

I divided all patients into training data (n=50) and validation data (n=47).

Finally, XGBoost is the best model evaluated by ROC curve.

![ROC curve of training data](https://user-images.githubusercontent.com/80352910/141043513-876a9721-97b1-427c-8ad9-c372ac838c3d.png)



![ROC curve of validation data](https://user-images.githubusercontent.com/80352910/141043530-397afead-03e6-4c12-9d76-2f3ace4db434.png)

