# Melanoma Detection Assignment

## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis

## Data
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Project Pipeline
- Libraries
- Data Reading/Data Understanding
- Dataset Creation
- Dataset visualisation
- Autotuning
- Model Building & training
- Augmentation
- Model Building & training on the augmented data
- Class distribution
- Handling class imbalances
- Model Building & training on the rectified class imbalance data
- Analysis

## Notes
1. You don't have to use any pre-trained model using Transfer learning. All the model building processes should be based on a custom model.
2. Some of the elements introduced in the assignment are new, but proper steps have been taken to ensure smooth learning. You must learn from the base code provided and implement the same for your problem statement.
3. The model training may take time to train as you will be working with large epochs. It is advised to use GPU runtime in Google Colab.

## Platform Used

    - Jupyter notbook
    - Google colab

## Library Used

    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn
    - keras
    - tensorflow
    - glob

## Analysis

- First Model (Simple Model): Training Accuracy: 88%, Validation Accuracy: 52%
- Second Model (With Augmentation): Training Accuracy: 61%, Validation Accuracy: 55%
- Third Model (With Augmentor Library): Training Accuracy: 92%, Validation Accuracy: 83%

    Insights:
    - There is still some differences in accuracy. i.e. model is still slightly overfit but better than previous models
    - Model after handling class imbalance performs better.

## Acknowledgements
- [Jupytor Notebook used as reference](https://github.com/ContentUpgrad/Convolutional-Neural-Networks/tree/main/Melanoma%20Detection%20Assignment).

## Contact
Created by [@khatrisnk](https://www.github.com/khatrisnk) - feel free to contact me!