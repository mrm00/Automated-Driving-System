# Automated-Driving-System

Automated Driving Systems (ADS) have often been a phenomenon confined to science fiction media. However, recent advancements in computer vision, computation power, and big data technologies have allowed this phenomenon to become a reality. At the heart of every ADS or self-driving car is the ability to sense its environment. In fact, this ability is the most important feature in driving an automobile. We humans almost take this ability for granted when we get behind the wheel, but for an ADS the process of learning this task and implementing it takes years of optimization and incorporation of several technologies. 
	This project aims to optimize a very important variable that an ADS must evaluate after analyzing its environment: the steering angle. The steering angle is incredibly important to a self-driving car to ensure that it handles turns well, stays in its lane, avoids objects and collisions, and performs correctly in several other scenarios. 
	Udacity has open sourced software that puts a user behind the wheel of a car. The user has the choice of two tracks to drive around: a lake or a mountain. This simulator, built on Unity, has a couple of features key to this project - the ability to collect various driving data, and the ability to test a trained model on a specified track. The simulated car is equipped with 3 cameras on its windshield that capture a center, left, and right view of the car’s frontal surroundings.  Furthermore, the car is equipped with sensors that measure throttle, speed, reverse, and steering angles. Thus, the data collected consists of 3 images and 4 measured variables per recorded observation. To generate this data, a user drives around the track with the record option toggled on. Therefore, my project will be an exercise in behavioral cloning- where I generate my own data and train a model based upon it. 

# Image Data
https://drive.google.com/open?id=1TgqfRU4dghA3Xjdh4cOr32kmrUUnmFGE

# Lake Track Simulation
https://drive.google.com/open?id=1sQspYS0nLOOsj5a6ARhR3p1sIMykF4W2

# Mountain Track Simulation
https://drive.google.com/open?id=1TpnWA_0R_C5FVdLO3gViW5TYZikkP112

# Resources
  1. NVIDIA Convolutional Neural Networks
    https://developer.nvidia.com/discover/convolutional-neural-network
  2. NVIDIA ADS Architecture
    https://images.nvidia.com/content/tegra/automotive/images/2016/solutions/pdf/end-to-end-dl-using-px.pdf
  3. Flask and Socketio documentation
    https://flask-socketio.readthedocs.io/en/latest/
  4. Udacity Self-Driving Car Simulation repository
    https://github.com/udacity/self-driving-car-sim
  5. Self-Driving Car Flask and Socketio app adaptation
    https://github.com/udacity/CarND-Behavioral-Cloning-P3
