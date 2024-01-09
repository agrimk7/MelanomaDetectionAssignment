# Melanoma-Detection-Assignment
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

In this assignment, we will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements



## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

You can download the dataset [here](https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing).

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



## Technologies Used
- pandas
- sci-kit learn
- numpy
- seaborn
- matplotlib
- Jupyter Notebook
- Tensorflow
- Keras
- Github



## Conclusions
1. Base Model:
Training accuracy is significantly higher than validation accuracy, as the graph illustrates. We also observe changes in the loss functions between the training and validation data around the 19th and 20th epochs. This is an obvious case of overfitting, where the model is unable to function adequately on the validation dataset because it has learned too much from the training dataset.
   - Training Accuracy: 85.66
   - Validation Accuracy: 53.69
  
2. Augmented data Model:
   Compared to the baseline model, training accuracy has not risen, but the difference between training and validation accuracy has decreased. Furthermore, there is a slight improvement in validation accuracy compared to the original model. Additionally, the difference between validation loss and training loss is reduced. We also observe that the reduction in overfitting brought about by data augmentation.
   - Training Accuracy: 61.16
   - Validation Accuracy: 52.13
  
3. Training and validation accuracy have significantly increased as a result of augmentation and class imbalance control. It is not an overfit model and can be considered as the final model.
   - Training Accuracy: 95.20
   - Validation Accuracy: 80.92



## Contact
Created by [Agrim Koundal](https://github.com/agrimk7) - feel free to contact me!
