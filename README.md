# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the background of your project?
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. eborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion
- What is the business probem that your project is trying to solve?
- #Project Pipeline
#### Data Reading/Data Understanding → Defining the path for train and test images
#### Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
#### Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset
#### Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
#### Choose an appropriate optimiser and loss function for model training
#### Train the model for ~20 epochs
#### Write your findings after the model fit, see if there is evidence of model overfit or underfit
#### Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented
- What is the dataset that is being used?
- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~20 epochs
- Write your findings after the model fit, see if the earlier issue is resolved or not? **Class distribution: **
- Examine the current class distribution in the training dataset
- Which class has the least number of samples?
- Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances:
- Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:
- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~30 epochs
- Write your findings after the model fit, see if the issues are resolved or not?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 
- After the analysis the first attempt with epochs=20  recived this anaccuracy: 0.8672 - loss: 0.3553
- After remodeling the first result we get analysis of second attempt with epochs=20  recived this accuracy: 0.7786 - loss: 0.4949 - val_accuracy: 0.5625 - val_loss: 2.2029
- After the analysis the first attempt recived this anaccuracy: 0.8672 - loss: 0.3553

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.0
- pandas - version 2.0
- numpy - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...Healthcare
- References if any...
- This project was based on [this tutorial](https://learn.upgrad.com/course/5800/segment/55852/333577/1009201/5042348).


## Contact
Created by [@anandbanshi123] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->