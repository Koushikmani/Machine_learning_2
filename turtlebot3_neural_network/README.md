# MACHINE_LEARNING_FOR_ROBOTICS_2

## Obstacle Avoidance using Neural Networks, Random Forest, KNN, CNN and Decision tree Classifiers using ROS

### Developed by Jerin Joy and Koushikmani Maskalmatti Lakshman under the guidance of professor Luca Oneto.
This project demonstrates the implementation of obstacle avoidance in ROS (Robot Operating System) using various machine learning classifiers such as Neural Networks, Random Forest, KNN, and CNN. The purpose of this project is to create a robot that can navigate autonomously without colliding into any obstacles in its path.

![TurtleBot3_WafflePi](https://user-images.githubusercontent.com/81651764/194770503-45cbd61b-7b50-442e-b67a-140f7cc4dc28.png)

The software has been tested with the [TurtleBot3 ROBOT](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/) robot model, which is a small, affordable and programmable, ROS-based mobile robot for use in education, research, hobby, and product prototyping.


## Installation Setup

- OS Version:[Ubuntu 20.04] (https://releases.ubuntu.com/focal/)
- This package is developed with the ROS2 Humble and Nav2 package to install this follow the official documentation [ROS](http://wiki.ros.org/noetic/Installation/Ubuntu)


## Classifiers used

- Convolution Neural Network(CNN)
- Random Forest(RF)
- K-Nearest Neighbors(KNN)

## Package Description

## Process to execute the Assignment:

Terminal_1(Gazebo)

    '''
         roslaunch turtlebot3_neural_network turtlebot3_square.launch
    '''
Terminal_2(To run the obstacle avoidance)

    '''
          python3 obstacle_avoidance_tf.py
    '''
Terminal_3(To record the data)

    '''
          python3 data_recorder.py 

    '''
Terminal_4(To Train the neural network)
   
    '''
           python3 data_train.py
    '''
    
Terminal_4(Main script)
   
    '''
           python3 obstacle_avoidance_tf.py 
    '''




## Video
  Find the below video of the task
  
  

  
## ROS graph  

## Presentation of this project

Here you can find the presentation of the assignment
