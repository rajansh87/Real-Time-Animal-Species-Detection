## Major-Project: Real-Time Animal Species Detection

## Description:
#### A CNN model for the detection of a variety of animal species which are captured with the help of the mobile application. We are making predictions in real-time, as the animal comes in front of the camera, each frame would be sent to the system where our model will produce the output within a few micro-seconds.
#### Project Consists of the following subtask:
##### 1. Data Exploration and Collection
##### 2. Dataset Creation
##### 3. Data Preprocessing
##### 4. Image Preprocessing
##### 5. Model Creation
##### 6. Model Training with Optimization and Enhancement
##### 7. Using a Trained model with Computer Vision Techniques

#### We collected various datasets of images of various animal species which was present on Kaggle, from their by the help of kaggle api key imported these datasets to our Google Colab notebook and did some processing and merged them to make a single dataset then divided whole dataset into train and test dataset. By the help of Keras framework we did image preprocessing on batches of dataset. Then these batches of dataset was applied to our CNN model and based on that network, we made our model learn the features of images and later on classify animal images into classes.
#### After training our ML model it was ready for its final working, So we used a Mobile application called “IPCam” and using it we imported the live stream video from that application to our system and then each frame of that video was captured and processed and for each frame by the help of our model we find which animal species was present in that particular frame on real time.

 
## Data Sources: 
##### 1. https://www.kaggle.com/biancaferreira/african-wildlife
##### 2. https://www.kaggle.com/kdnishanth/animal-classification
##### 3. https://www.kaggle.com/viswatejag/animal-detection-small-dataset
##### 4. https://www.kaggle.com/jerrinbright/cheetahtigerwolf
