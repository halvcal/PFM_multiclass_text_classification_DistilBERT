# Multiclass classification of texts with DistilBERT

Master in machine learning, deep learning and artificial intelligence with UCAM and Big data international campus.

Master thesis about applied NLP in a commecial setting.

This repository comes along with the master's thesis submitted where the approach to this task and decisiones made are explained in detail.

The master's thesis can be found in the following link (Note that it is written in Spanish):

https://drive.google.com/drive/folders/1lNr4WivIz8wXLcg4oBkGVdOzmf0Twe9U?usp=sharing

## Objective

The objective of this master's thesis is to check if a multiclass classification of sentences can be done reasonably accurately using a type
of pretrained BERT model.

The state-of-the-art model DistilBERT was used for this purpose.

The muticlass text clasiffier was deployed using a pre-trained model from Hugging Face which in turn support the integration of Pytorch.

The data used for training are property of Kaggle and, therefore, have not been uploaded to the public repository.

## Data

The size of the dataset is 20,000 events with documents and its emotions.

For training and evaluation, the data were partitioned according to the following proportions:

80% Training
10% Validation or hold-out
10% Testing

## Models

The weights of the trained models are publicly available and can be downloaded at the link below:

https://www.kaggle.com/code/hugoalvcal/pfm-clasifsentdistilbert/data

## Results

The multiclass text classifier achieved an accuracy of 92.3% on the validation set.

Confusion matrix:

![image](https://user-images.githubusercontent.com/107633593/211154236-fccb8752-84b1-4681-8f98-ee7ce752eda2.png)
