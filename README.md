## About
---
This challenge was conducted by [Hackerearth](https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-identify-dance-form/) where the dataset contained images of 8 different dance forms.

![Dance Forms](sample.jpg)



The model is built using VGG16 via transfer learning and achieves a train accuracy of 99% with validation accuracy of 81.8%.


There are 2 notebooks in this repo:

- Dataset Preparation: Contains script to split the dataset into train and validation sets and then organize them into class-wise folder structure for keras.

- Dance_Form_Classifier: Contains code for model training and inference.   
