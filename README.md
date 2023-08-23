# Vehicle-and-Pedistrian-detection


This application is able to detect and track vehicles and pedestrians on camera for autonomous cars and/or in cases of provided video files using open computer vision. The different Vehicles that this application is able to detect are Cars, Buses, CNGs (a prominent vehicle in Bangladesh), Bikes and Two-wheelers, and finally pedestrians of course. The underlying algorithm used in order to create the classifier is the “Haar cascade algorithm”. We select OpenCV as the development tool for the implementation of vehicles and pedestrian detection in a video segment. This application is developed in Python using OpenCV 4.6.0

## Datasets : 

Around 1000+ Bangladeshi local vehicle image datasets were used to train the cascade classifier.

The dataset is available at: https://data.mendeley.com/datasets/pwyyg8zmk5/2

Corresponding Research paper of the dataset: https://www.researchgate.net/publication/347763603_Poribohon-BD_Bangladeshi_local_vehicle_image_dataset_with_annotation_for_classification

**Demo dataset is present in this repository**


## Method : 
We used the Haar cascade classifier to classify the different vehicles. Our methods are
listed below.

But first, We divided the objects into six classes: Bus, Car, Two-wheelers, CNG, Rickshaw, and Pedestrian.



### Step 1: Collection of Positive and Negative Image Set
      *Description*
      
### Step 2: Training the Haar cascade Classifier on the negative and the positive dataset
      *Description*
      
### Step 3: Generating the trained XML file.
      *Description*

### Step 4: 

      *Description*
### Step 5: Using the Bounding box to annotate the specified vehicle and pedestrian from the video.
      *Description*




## Classifier : 


## Training : 


