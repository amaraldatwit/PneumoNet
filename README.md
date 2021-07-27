# PneumoNet

## Introduction
### Abstract
The purpose of PneumoNet is to utilize machine learning to create a model that would be able to determine if chest X-rays had signs of pneumonia. The assistance of machine learning in the medical field aims to reduce doctors' workload and decide which patients need urgent care. Using the model, doctors would spend more of their time on the patients that need urgent care and hopefully save lives. We utilized a dataset containing 10,192 X-rays of normal healthy lungs and 1,345 X-rays of viral pneumonia patients. The ratio between normal X-rays and X-rays of patients with viral pneumonia in the dataset is 1:10 making the dataset very unbalanced. The transfer learning technique was employed to save time on training the model and increase the accuracy with better feature extraction. ResNet50, VG166, and MobileNetV2 were used as base models and compared to see which provided the best accuracy. MobileNetV2, combined with additional layers, proved the highest accuracy. The dataset used to train the model was unbalanced, but the resulting model had an accuracy of 97.46%, with an F1 score of .88774. The model is not designed to make a diagnosis of the patient but to only assist doctors in making a diagnosis.

### Who
Our project is aimed at healthcare workers, particularly doctors such as radiologists.
We hope to leverage artificial intelligence in an effort to decrease the strain on healthcare workers.

### What
The main objective is to create a machine learning model that will assist doctors by flagging patients who possess a high probability of having viral pneumonia to notify them of the patients who may be in need of more urgent care. 
Our model gives each patient a probability of having viral pneumonia depending on their chest X-ray.

### Why
Doctors must dedicate a portion of their time to examining X-rays and diagnosing patients before administering a treatment.
With a model such as ours, they can streamline this process and make more time for communicating and treating patients.

### How
We used machine learning to train a model to recognize chest X-rays where the patients might have a positive case of viral pneumonia. 
The model looks at each chest X-ray that feeds into it and gives a probability from 0 to 1 if the X-rays have signs of pneumonia.
To refine your accuracy of the model to make the best prediction and minimize errors did optimizations where tried to minimize false negatives and one where we aimed for the highest accuracy. 

## Getting Started 

### Colab 

- Needs Work

### Windows Locally

#### List of PreReqs	

Installing the libraries needed (Windows)
Open the command prompt or the Anaconda ENV cmd and run each line

		> pip install --upgrade pip	
		> pip install matplotlib
		> pip install pillow
		
		> pip install tensorflow
		
For conda run 

		> conda update conda
		> conda install -c conda-forge matplotlib
		> conda install -c conda-forge pillow
		
		> conda create -n tf tensorflow
		> conda activate tf

## Video
### [Link]
- Needs work

## Team Members
* Dominic Amaral
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
- Needs Work
