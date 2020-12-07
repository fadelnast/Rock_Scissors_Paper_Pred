# Rock Paper Scissors Classifier

We create a tensorflow model to classify each picture of the hand gesture as a rock, paper, or scissors. In this project we used Convolutional Neural Network.

## Dataset

Training and Testing Dataset that we were uses are sourced from dicoding as it is part of their module : https://dicodingacademy.blob.core.windows.net/picodiploma/ml_pemula_academy/rockpaperscissors.zip \
  -O /tmp/rockpaperscissors.zip

This dataset consists of 2188 hand gesture images formed a rock, paper or scissors. There are 726 rock images, 712 paper images, and 750 scissors images.


## Model

For this model, we use Convolutional Neural Network base in Tensorflow. There are 5 layers of Conv2D and Maxpooling. We also used Data Augmentation and Image Data Generator to help the training processed.

## Prerequisites

There is no need to install anything because it is basically written in google colab notebook with cloud service.

* Copy this repository link to your google colab https://github.com/fadelnast/Rock_Scissors_Paper_Pred/blob/main/Dicoding_RPS_1.ipynb 
* After successfully open the notebook, you can get the datasets in here https://dicodingacademy.blob.core.windows.net/picodiploma/ml_pemula_academy/rockpaperscissors.zip \
-O /tmp/rockpaperscissors.zip


## Built with
Tensorflow Keras



