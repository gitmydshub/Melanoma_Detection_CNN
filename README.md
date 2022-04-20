# Melanoma Detection using CNN
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Business Goal](#business-goal)
* [Model Building](#model-building)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

## Business Goal
You are required to model build a CNN based model that can evaluate images and alert dermatologists about the presence of melanoma.

## Model Building
The model is built using CNN, and to get best alpha score from both. Final model created with the help of Augmentor package, which is giving better accuracy.

## Conclusions
- Initially we tried without the ImageDataGenerator which created data to over fit at high ratio
- Then we introduced dropout and ImageDataGenerator which reduced the over fit
- At last we tried Batch Normalization and Augumentation which really helped in carry forward

## Technologies Used
- pandas
- numpy
- matplotlib
- tensorflow
- keras
- augmentor
