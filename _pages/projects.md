---
layout: page
title: projects
permalink: /projects/
description: "Here are some personal projects that I have worked on in the past:"
nav: true
display_categories: [work, fun]
horizontal: false
---

___
- __Image Super Resolution__ 
[[Code]](https://github.com/HareeshBahuleyan/image-super-resolution){:target="_blank"} <br>
  <p style="text-align:justify">A CNN architechture (with residual connections) is trained to transform low resolution images to high resolution. The input to the model is a 72x72 image which is fed through a series of convolutional and residual blocks (to learn necessary features), and then upsampled (either by UpSampling2D or Deconv2D from Keras) to obtain a 288x288 image.</p>

___

- __Neural Style Transfer__ 
[[Code]](https://github.com/HareeshBahuleyan/neural-style-transfer){:target="_blank"} <br>
  <p style="text-align:justify">Given two images A (content image) and B (style image), the task is to transfer the style of image A into that of image B, while being able to preserve the content of image A. The idea is to start with a random noise image (input image), and to update its pixel values so that we minimize both the style and content loss.</p>

___

- __Music Genre Classification__ 
[[Code]](https://github.com/HareeshBahuleyan/music-genre-classification){:target="_blank"} <br>
  <p style="text-align:justify">Automatic recognition of music genre using the ensemble of two approaches: (1) Spectrogram based end-to-end image classification using a CNN (VGG-16), (2) Feature Engineering Approach using Logistic Regression, SVMs, Random Forest and eXtreme Gradient Boosting.</p>

___

- __Music Language Modelling__ 
[[Code]](https://github.com/HareeshBahuleyan/midi-music-generator){:target="_blank"} <br>
  <p style="text-align:justify">Generate music using language modelling approach with LSTM neural networks. MIDI instructions are converted into a sequence of 'words' and the task is to predict the next word in the sequence, given the previous _n_ words.</p>

___

- __Kaggle Seizure Prediction Challenge__ 
[[Code]](https://github.com/HareeshBahuleyan/seizure-prediction-kaggle){:target="_blank"} <br>
  <p style="text-align:justify">EEG signals record electrical activity of the brain and can be used to predict the onset of a seizure. A competition conducted by the University of Melbourne on Kaggle required participants to classify 10-minute EEG clips into clips into either interictal or pre-ictal. I appoached the problem using an XGBoost classifier trained on (1) Time domain features, (2) Frequency domain features, and (3) EEG Specific Features. </p>

___

- __Text Classification using LSTMs__ 
[[Code]](https://github.com/HareeshBahuleyan/deeplearning-tutorials/tree/master/text-classification-lstm){:target="_blank"} <br>
  <p style="text-align:justify">Carry out a sentiment analysis task on the Rotten Tomatoes movie review dataset using recurrent neural networks. Specifically, an LSTM was trained with sentences (sequence of words) to predict the sentiment label.</p>

___

- __Airbnb Rental Price Prediction__ 
[[Code]](https://github.com/HareeshBahuleyan/airbnb-analysis){:target="_blank"} <br>
  <p style="text-align:justify">Python Selenium is used to scrape listings data from airbnb.ca for the city of Toronto. An extensive exploratory data analysis is carried out, following which, a price prediction model is built using information such as in-house amenitites and neighbourhood facilites as features.</p>

___