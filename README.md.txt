# Project Name: Melanoma Detection Assignment

# Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


General Information
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
Build a multiclass classification model using a custom convolutional neural network in TensorFlow
Dataset: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following 9 diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Seborrheic keratosis
Squamous cell carcinoma
Pigmented benign keratosis
Vascular lesion

Conclusions
There are 4 models building during the development process
First model is a overfitting model where the accuracy & loss difference for training and validation data is significantly large
Second model is build to handle the overfitting by introducing agumentation, but the model accuracy is low (Training accuracy 60.5% and test accuracy 56.1%)
Third model is built with dropouts. There is underfitting of the model (Training accuracy 62.8% and test accuracy 54.8%)
Fourth model is build to handle class imbalance and observed the improvement in accuracy (Training accuracy 84.26% and validation accuracy 80.77%)
Finally the model performed very well on test data with accuracy of 99.66%



## Acknowledgements
Give credit here.
- This project was inspired by Upgrad CNN Assignment


## Contact
Created by [@SreeSatyaS] - feel free to contact me!
