# Melanoma_Detection_Assignment
CNN based model which can accurately detect melanoma. Skin disease.

## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* Import libraries
* Data Reading/Data Understanding
* Dataset Creation
* Dataset visualization
* Model Building & training
* Choose hperparameter techniques
  like, Choose an appropriate data augmentation strategy to resolve underfitting/overfitting 
* Class distribution
* Handling class imbalances, Augmentor library
* Conculsion of model
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Model is a multiclass classification model using a custom convolutional neural network in TensorFlow
- Problem
  To build a CNN based model which can accurately detect melanoma.
- This model doesn't used any pre-trained model using Transfer learning. 
   All the model building process should be based on a custom model.
- Dataset
  The dataset consists of 2357 images of malignant and benign oncological diseases with 9 classes, which were formed from the International Skin Imaging Collaboration (ISIC). Below are the sample of each diseases.
 
  ![image](https://user-images.githubusercontent.com/104660411/196772782-a2a955b5-0c3d-4352-b641-f7eb62ceb30a.png)
  
  There is an data imbalace between classes, has been handle using augmentation
  
![image](https://user-images.githubusercontent.com/104660411/196772387-cfe4cbe5-7589-48e7-8682-b3d8a1017991.png)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- pipeline is built with 3 model
 1.0 basic model
 2.0 Model with augmented layer with drop out
 3.0 Model with augmentor library for imbalance
 
![image](https://user-images.githubusercontent.com/104660411/196771908-91b20b8f-332a-45d3-ab89-8084a4d3be5a.png)

By augmentor with sample 500 on each class added in training set. Both training & validation accuracy is improved by 93% & 65%. Model is performing better than previous 2 model seen. But, further model need to fine tune using hyperparameter methods, changing epochs, adding drop out, pooling layer, etc for better accuracy of validation wrt to training accuracy.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow
- nummy & pandas
- matplotlib
- Model is build from colab with GPU runtime
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad and IIIT- B faculty ...


## Contact
Created by [@aerokhaleel] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
