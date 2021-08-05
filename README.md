# Rock-Paper-Scissors Image Classification with Sequential Model using TensorFlow and Keras Library

This is my Final Project of Belajar Machine Learning Pemula Course by Dicoding Indonesia. Image Classifier Rock Paper Scissors with Sequential Model using TensorFlow and Keras Library

## Dataset
This dataset contains images of hand gestures from the Rock-Paper-Scissors game. The dataset contains a total of 2188 images corresponding to the 'Rock' (726 images), 'Paper' (710 images) and 'Scissors' (752 images) hand gestures of the Rock-Paper-Scissors game. All image are taken on a green background with relatively consistent ligithing and white balance.

All images are RGB images of 300 pixels wide by 200 pixels high in .png format. The images are separated in three sub-folders named 'rock', 'paper' and 'scissors' according to their respective class.

Dataset of Rock Paper Scissors can be downloaded [here](https://drive.google.com/drive/folders/1kV17Ta8IiDq3_RFrZU9WrXXdhZpQe_UB?usp=sharing)

## Submission Criteria
+ The dataset should be divided into a train set and a validation set.
+ The size of the validation set must be 40% of the total dataset (training data has 1751 samples, and validation data is 437 samples).
+ Implement image augmentation using ImageDataGenerator
Using Sequential model
+ Training of the model less than 30 minutes
+ Model accuracy at least 85%
+ Able to predict image uploaded to Colab widget
+ Add personal data (according to the Dicoding profile) in the submitted submission/project.

## Result
Model composed of 4 Convolutinal 2D layers with 32, 64, 128, and 128 channels, 4 MaxPooling2D layers, 1 Flatten layer, 1 Fully Connected Layer with 512 channels, output layer with 3 channels and softmax activation function, and epoch is 25 epochs.

Accuracy : 

| Loss  | Acc | Val_acc |Val_loss |
| :-----: |:-----:| :-----:|:-----:|
| 16% | 94 %  | 93% | 12% |


## Files Description
+ MLpredict.py

  This file contains preprocessing, training and testing programs for Image Classifier Rock Paper Scissors with Sequential Model using TensorFlow and Keras Library

+ Dicoding_ML.ipynb

  This is a file submission made on google colab. The result of this file is a training model with: loss: 0.1576 - accuracy: 0.9406 - val_loss: 0.1198 - val_accuracy: 0.9271 and the training time is approximately 8 minutes.
