# PneumoNet

## Introduction
### Abstract
The purpose of PneumoNet is to utilize machine learning to create a model that would be able to determine if chest X-rays had signs of pneumonia. The assistance of machine learning in the medical field aims to reduce doctors' workload and decide which patients need urgent care. Using the model, doctors would spend more of their time on the patients that need urgent care and hopefully save lives. We utilized a dataset containing 10,192 X-rays of normal healthy lungs and 1,345 X-rays of viral pneumonia patients. The ratio between normal X-rays and X-rays of patients with viral pneumonia in the dataset is 1:10 making the dataset very unbalanced. The transfer learning technique was employed to save time on training the model and increase the accuracy with better feature extraction. ResNet50, VG166, and MobileNetV2 were used as base models and compared to see which provided the best accuracy. MobileNetV2, combined with additional layers, proved the highest accuracy. The dataset used to train the model was unbalanced, but the resulting model had an accuracy of 97.46%, with an F1 score of .88774. The model is not designed to make a diagnosis of the patient but to only assist doctors in making a diagnosis.

### What
PneumoNet is a machine learning model that uses a convolution neural network (CNN), a deep learning technique commonly used for image identification and classification.
It can suggest if a patient's lung X-rays show signs of pneumonia, helping radiologists give a faster and more accurate diagnosis. 
PneumoNet is not a diagnostic tool and rather aims to help radiologists with making their diagnoses.

### Why
Pneumonia is one of the leading causes of death in the US today, with nearly 50,000 people dying from it annually. 
This makes diagnosing the disease quickly not only important, but life saving. 
Unfortunately, radiologists tend to only be accurate about 80% of the time when diagnosing pneumonia. This is where we aim to help with PneumoNet.

### How
PneumoNet was designed using transfer learning, a model-building method that saves on both time and processing power by taking the feature extraction layers of another model already trained. 
This saves time on building a new feature extractor and allows more focus on developing the classification layers of the model instead.

## Getting Started 

### Colab 

https://drive.google.com/drive/folders/1uqx1NEY0vrAONnxZPSGbKKDEKiOZEddw?usp=sharing

First right click in the project `PneumoNet-main` and select `Add Short cut to Drive`

After you are all set to run the notebook!

## Video
### [Link](https://youtu.be/IEHWXPrZHlo)


## Team Members
* Dominic Amaral (amaraldaf@gmail.com)
* Leon Chen
* Robert Martini

## References used
Optimal Threshold for Precision-Recall Curve
- https://www.tensorflow.org/tutorials/structured_data/imbalanced_data 
- https://machinelearningmastery.com/threshold-moving-for-imbalanced-classification/ 
- https://keras.io/api/metrics/classification_metrics/ 

- https://www.tensorflow.org/api_docs
- https://keras.io/

## Credit
- Prof. Mehmet Ergezer, PhD 
