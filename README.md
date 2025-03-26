# Melanoma Skin Cancer Detection
In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Melanoma Skin Cancer Detection
Abstract
In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.

Problem Statement
In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.

Motivation
The overarching goal is to support the efforts to reduce the death caused by skin cancer. The primary motivation that drives the project is to use the advanced image classification technology for the well-being of the people. Computer vision has made good progress in machine learning and deep learning that are scalable across domains.

Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.

The data set contains the following diseases:

<img width="148" alt="image" src="https://github.com/user-attachments/assets/604e790d-8656-49af-a0ce-150e417303d9" />



## Conclusions
Significant Reduction in Overfitting:

The training and validation accuracy curves are much closer than in previous models, indicating improved generalization.

Validation accuracy has improved, reaching around 80%, suggesting that the model is now learning meaningful patterns rather than memorizing training data.

More Stable Loss Curves:

The training and validation loss curves follow a similar trend, with no sharp divergence, meaning the model is not overfitting as before.

Validation loss no longer increases drastically after a few epochs, indicating that early stopping prevented excessive overfitting.

Effectiveness of Data Augmentation:

The improvement in validation accuracy suggests that augmenting the dataset with transformations (e.g., rotation, flipping, zooming) helped the model learn more generalizable features.

The model is now more robust and less sensitive to variations in input data.

Early Stopping Helped Avoid Overtraining:

Training was stopped at the optimal point before the model started to overfit.

This ensures that the final model has good generalization without unnecessary additional training epochs.

Final Verdict:
✅ Overfitting is significantly reduced.
✅ Validation accuracy has improved, indicating better generalization.
✅ Loss curves suggest stable learning.
✅ Class rebalancing and augmentation likely helped in performance improvement

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
TensorFlow: 2.18.0
Keras: 3.8.0
NumPy: 2.0.2
Pandas: 2.2.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad PGP certificaion program
- References from Upgrad Study material
  - This project was based on the data from https://www.cancer.org/cancer/melanoma-skin-cancer/about/what-is-melanoma.html


## Contact
Created by [@abhilashawasthi1900] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
