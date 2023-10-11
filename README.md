# Project Name

> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion
- In this assignment, we have build a multiclass classification model using a custom convolutional neural network in TensorFlow. To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Dataset provided by Upgrad is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Starting with a simple CNN we observered that there was overfitting of the model, where the train accuracy was very high and validation accuracy was very low.
- Augmention technique was used for the CNN model to understand the minor differences and similarities between images which improved the overfitting issue.
- Batch Normalization and Droput was also used in conjunction with Augmentaion to have a better fir model.
- There was class imbalance in the dataset and hence Augmentor pipeline was used to generate an even class balance of 500 for each class and then we saw that the overfitting issue was resolved.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- python
- Numpy
- Matplotlib
- tensorflow
- pandas
- pathlib
- Augmentor
- GoogleColab

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

Give credit here.

- This project was inspired by Upgrad Melanoma Detection Assignment.
- Wikipedia
- Medium
- StackOverflow

## Contact

Created by [@TanishaS21] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
