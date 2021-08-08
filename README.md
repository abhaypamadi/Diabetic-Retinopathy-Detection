# Diabetic-Retinopathy-Detection

Diabetic retinopathy is a microvascular diabetic condition that affects the eyes. It is caused by impairment to the blood vessels in the retina.

This project is aimed at demonstrating two convolutional neural networks (CNN) models, one of them a binary classification to detect the presence of retinopathy and another multinomial classification model to further classify retinopathy into five distinct and widely used stages - None, Mild, Moderate, Severe and Proliferative Diabetic Retinopathy. 

Using Gaussian filtered fundus images, resized into 224*224 pixels improves the recognition of subtle features used for diagnosis. Transfer learning on a pre-trained MobileNetV2 model further enhances the accuracy to 80% for a multinomial classification and up to 97% for binomial classification.

The link to the dataset - https://www.kaggle.com/sovitrath/diabetic-retinopathy-224x224-gaussian-filtered
