# MY MINI PROJECTS
These are the dummy or simple projects I've done in my fields of interest

# LIST OF PROJECTS
 - **pong game using** (arduino, python): 
   This project is about making use of the MPU-6050 sensor as a ping-pong racket in a python-generated pong-game. The segmentation is as explained below: 

   1. Chapter 0: INTRODUCTION
      - Sensors: MPU-6050 and MPU-9250
      - Methods of extracting data 
      - Calibration 
      - Kalman and Complementary filters
      - Processing data with Python 
      - Game Design with Python 
   2. Chapter 1: DATA EXTRACTION
      - Setup of the Arduino kit
      - Data extraction 
      - Plotting the data
   3. Chapter 2: FILTERS
      - Kalman filter on raw data
      - Complementary filter
   4. Chapter 3: DATA PROCESSING
      - Rotation matrix (from roll, pitch yaw)
      - Rotation matrix (from quaternion values)
   5. Chapter 4: GAME DESIGN 
      - Making the game with Python 
      - MPU-6050 data to Game input


![Arduino Setup](https://i.postimg.cc/GcFZJ5TJ/setup.jpg)
![Pong Game](https://i.postimg.cc/Qtz6ChB7/game.png)
         
 - **image mask detection** (python)
   This one is about some basic image processing. 
   1. Chapter 0: INTRODUCTION 
      There are two part to this project. the first image processing problem is mask detection. meaning the python script first has to detect a face and then determine if it has a mask on. 
      The second part is finding the cube objects using binary masks, and then calculate the centroid and orientation of the cube.
   2. Chapter 1: MASK DETECTION 
      - Set up (virtual environment and jupyter notebook)
      - Face detection (using haar features in python)
      - Mask detection (with pre-trained NN)
   3. Chapter 2: CUBE DETECTION
      - Set up (virtual environment and jupyter notebook)
      - Converting to binary mask 
      - Position and orientation (based on the contour) 

![mask detection - masked](https://i.postimg.cc/3NXLvdfz/sample-3.jpg)
![mask detection - un-masked](https://i.postimg.cc/NjzxL6f5/sample-1.jpg)
![cube detection](https://i.postimg.cc/JhH5XsGK/pic1-centeroid.png)


 - **ROS - turtlesim** (python):
   This main goal of this project was to write your own name with the turtles in ROS - turtlesim. 
   1. Installing Linux OS
   2. Installing ROS 
   3. Writing python script

![turtlesim](https://i.postimg.cc/Bv5Fv9FJ/arvin.png)


- **AlexNet and LeNet image classification** (Python)
  This is about image augmentation and addressing the issue of overfitting.