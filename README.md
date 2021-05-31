# TFG-MFR-CNNFE-ML


English
# Masked Face Recognition using CNNs as feature extractor, PCA for dimensionality reduction and Machine Learning classifiers


Due to the current world situation, the COVID-19 crisis, the use of face masks has become widespread. When attempting to apply the vast majority of existing face recognition techniques on a masked or partially covered face, a significant decrease in performance is observed. This is due to the lack of information and features produced by the occlusion of facial features.

The main goal of this project is to implement a system capable of applying face recognition on images containing people wearing masks. 
For this purpose, the AT & T Laboratories Cambridge ORL dataset has been used. This dataset contains 400 images of 40 people. 
Wear-Mask-To-Face has been adapted to our workspace (Colaboratory) to place a mask on each image of the dataset. 

More information about the original implementation of Wear-Mask-To-Face: https://github.com/Amoswish/wear_mask_to_face

The implementation performs feature extraction using a CNN without the last classification layers, then we use PCA to reduce dimensionality, and finally a classifier is applied.
For this purpose, several pre-trained CNN models and classifiers have been used.
  
CNN models used:
  VGG16
  VGG19
  ResNet50
  ResNet101
  InceptionV3
    
Classifiers:
  MLP
  SVM (LinearSVC)
  Random Forest

Best perfomance models:
  VGG16 + LinearSVC   (~ 94% Accuracy, 0.97 AUC)
  VGG16 + MLP         (~ 93% Accuracy, 0.97 AUC)
  VGG19 + LinearSVC   (~ 92% Accuracy, 0.96 AUC)

This repository contains the entire project developed in Google Colaboratory notebooks.



Spanish
# Reconocimiento facial con uso de mascarilla empleando CNNs como extractor de características, PCA para reducción de dimensionalidad y clasificadores Machine Learning


Debido a la situación mundial actual, la crisis del COVID-19, se ha extendido el uso de mascarillas. Al intentar aplicar la gran mayoría de técnicas existentes de reconocimiento facial sobre una cara con mascarilla o parcialmente tapada, se observa una gran disminución de su rendimiento. Esto es debido a la falta de información y características producida por la oclusión de facciones.

El principal objetivo de este proyecto es implementar un sistema capaz de aplicar reconocimiento facial en imágenes que contienen personas haciendo uso de mascarilla. 
Para ello se ha empleado el dataset ORL de AT & T Laboratories Cambridge. Este dataset contiene 400 imagenes de 40 personas. 

Se ha adaptado Wear-Mask-To-Face a nuestro espacio de trabajo (Colaboratory) para colocar una mascarilla en cada imagen del dataset. 

Más información sobre la implementación original de Wear-Mask-To-Face: https://github.com/Amoswish/wear_mask_to_face

La implementación realiza la extracción de características mediante una CNN sin las últimas capas de clasificación, posteriormente empleamos PCA para reducir dimensionalidades, y por último se emplea un clasificador.
Para ello se han empleado varias redes CNN preentrenadas y clasificadores ML.
  
Redes CNN empleadas:
  VGG16
  VGG19
  ResNet50
  ResNet101
  InceptionV3

Clasificadores:
  MLP
  SVM (LinearSVC)
  Random Forest

Mejores modelos:

  VGG16 + LinearSVC   (~ 94% Accuracy, 0.97 AUC)
  VGG16 + MLP         (~ 93% Accuracy, 0.97 AUC)
  VGG19 + LinearSVC   (~ 92% Accuracy, 0.96 AUC)

Este repositorio contiene los ficheros del proyecto desarrollado en cuadernos de Google Colaboratory.
