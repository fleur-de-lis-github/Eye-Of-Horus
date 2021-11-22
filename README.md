# Eye-Of-Horus

## Problem Scenario
Satellite imagery is important for many applications including disaster response, law enforcement, and environmental monitoring. These applications require the
manual identification of objects and facilities in the imagery. Because the geographic expanses to be covered are great and the analysts available to conduct the searches are few, automation is required. Yet traditional object detection and classification algorithms are too inaccurate and unreliable to solve the problem. 

## Our Approach

Scene understanding and analysis has gained significant importance and widely used in computer vision and robotics field. Classification of complex scenes in a real-time environment is a difficult task to solve. Convolution Neural Networks (CNNs) is a widely used deep learning technique for the image classification. But the training of CNNs is not an easy task since it requires large scale datasets for training. Also, the construction of CNN architecture from scratch is a complex work. The best solution for this problem is employing transfer learning which gives the desired result with small scale datasets. A novel approach of IncpetionV3 and VGG16  based transfer learning method for classifying images into their classes has been proposed in this project.


## Business Client
![image](https://user-images.githubusercontent.com/73738414/142716167-9d3bd41c-2770-44e1-937e-279f30c83724.png)
In “Geospatial Imagery Analytics Market — Global Forecast to 2021” by Markets and Markets, the total imagery market is estimated to be $2,639 million in 2016 which is expected to rise to $9,696 million by 2021. Out of this, defense and government take up the lion’s share of the global geospatial imagery analytics market. In fact, the share is shown to increase by 2021 at a CAGR of 24.9% and 30.3% respectively.

## Project Workflow
:pushpin:- Data Preprocessing
:pushpin:- Data Visualization
:pushpin:- Data Augmentation
:pushpin:- Simple CNN Model (sCNN)
:pushpin:- Transfer learning
:pushpin:- InceptionV3 
:pushpin:- Complex CNN Model based on Pre-trained VGG16 Model
:pushpin:- Conclusion and Next Steps

## Data Summary  

:closed_book: The data was taken from Kaggle and it contains around 25k images of Natural Scenes around the world. All training and testing images with a size of 150x150
are classified into 6 categories:
- buildings = 0
- forest = 1
- glacier = 2
- mountains = 3
- sea = 4
- street = 5
:blue_book: The data consists of 3 separated datasets:
- Train with 14034 images
- Test with 3000 images
- Prediction with 7301 images
This data was originally published on https://datahack.analyticsvidhya.com by Intel for the Image Classification Competition.

## Citations
https://www.azavea.com/blog/2019/11/05/an-introduction-to-satellite-imagery-and-machine-learning/
https://www.researchgate.net/publication/343057531_TRANSFER_LEARNING_STRATEGY_FOR_SATELLITE_IMAGE_CLASSIFICATION_USING_DEEP_CONVOLUTIONAL_NEURAL_NETWORK
https://arxiv.org/abs/2010.06497
https://www.gislounge.com/transforming-satellite-imagery-classification-deep-learning/
