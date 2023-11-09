# Introduction 
This repository contains several notebooks that we worked on. The images and csv files needed to execute them can be found in the original drive but we decided
not to add them becauto make this this repo as light as possible and only exchange our code.

### test.ipynb
In this this notebook, we explore the different ways to exctract bounding boxes with the Faster R-CNN model. 
the results dataframes can be found in the folder Faster R-CNN. This folder contains subfolders for each amelioration of the model and are named : V1, V2, ...,V4
This subfolders contain the csv file as well as some plots

### KNN.ipynb
In this notebook we try to assign the emission of an image using it nearest neighbours within the reference photos of the 100 models.
To get better results, we tried extend the original dataset of reference photos (5 new photos for each model, different angles and colors) 
so that images have more neighbours aroud them. Unfortunately, the results were not better.

### VAE.ipynb
In this notebook, we try to make Variationnal Auto-Encoder  learn a good latent space where similar photos should have similar features. 
Unfortunately, we did not have the time to train it for a long time and the results were very poor.


