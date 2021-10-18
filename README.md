# Car-Damage-Detection-using-mask-rcnn
Identifies and locates the damages in car using mask-rcnn
# Table of content:
- [Demo]()
- [OVERVIEW]() 
- [BUSINESS PROBLEM]()
- [TECHNICAL ASPECT]()
- [COLLECTING DATA]()
- [INSTALLATION]()
- [DETECTING CAR IN IMAGE]()
- [DETECTING DAMAGE IN CAR]()
- [LOCATING DAMAGE IN CAR]()
- [WEBAPP]()
- [CONCLUSION]()
- [REFERENCES]() 

# Demo:
![](https://github.com/kajal1301/car_damage_detection/blob/main/static/uploads/demo.png)
# Overview:
This is a simple Car Damage Detection app which takes an image or a zip file as input,identifies if thereis a car in image and if the car is damaged and then it locates the damage in the car and displays the result as output. For zip files, it extracts all the images in file, and for each image it detects the damage and result the images with damage located on them in a zip file.
# Business Problem:
Given Image of a car we have to find out :
(i) The given image has a car
(ii) The car is damaged or not.
(iii) If the car is damaged then locate the damage
Mapping the problem into Deep Learning Model:
For detecting the car in the image and detecting damage in the car, it will be a binary
classification problem. And for dealing with images as input CNN(Convolutional Neural
Network) will be used.

# Technical Aspect:
# Collecting Data:
Damaged Car images are downloaded from the internet and further divided into train,
test and validation data.
For this problem we have 2 types of data:
- For detecting cars in image we have some images containing cars and some not
containing cars.
- For detecting damage in cars we have train and validation folders of images containing
damaged and non-damaged cars.
- For locating damage in the car we have train, test and val folders of damaged car
images.

# Installation:
To install the required packages and libraries, run this command in the project directory after [cloning](https://github.com/matterport/Mask_RCNN.git) the repository:
  pip install -r requirements.txt
# Detecting Car in Image:
# Detecting Damage in Car:
# Locating Damage in Car:
# Web app:
  ## For Image:
   ![](https://github.com/kajal1301/car_damage_detection/blob/main/static/uploads/demo3.png)
  ## For Zip file:
   ![](https://github.com/kajal1301/car_damage_detection/blob/main/static/uploads/demo2.png)
   


