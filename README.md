# Project Name-Multiclass-Classification-Model

# Brief description of project-
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis

.
## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
1) Created CNN model, for accurately detect 9 classes present in the dataset.
The model shows clear signs of overfitting because:-Training accuracy is very high, indicating that the model has learned the training data too well, including potentially memorizing it.
Validation accuracy, although improving initially, remains lower than training accuracy and fluctuates without significant improvement.

2) Using Data Augumentation, Created CNN Model
The model shows some signs of underfitting because:Training accuracy is not very high, indicating the model has not learned the training data very well.
Validation accuracy is low and not significantly higher than training accuracy.Both validation accuracy and validation loss show fluctuations, indicating instability in performance on unseen data.

3) Created CNN Model afterrectifying class imbalances
   The training accuracy is very high (over 95%) while the validation accuracy is around 79%-81%, suggesting that the model might be overfitting the training data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad
- This project was based on Convoluted Neural Networks


## Contact
Created by [SaurabSab]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
