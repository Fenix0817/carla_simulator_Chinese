# CARLA Self Driving Car Simulator in Chinese Traffic Scenes
## Introduction
To build a self driving car simulator for Chinese traffic, which based on intel open source simulator [Carla](https://github.com/carla-simulator/carla).

There are several targets show below:
* Integrate perception, localization, path planning and control in Carla simulator.
* Setup Chinese city traffic map
* Verify multi-camera + radar solution feasibility
* Setup metrics to evaluate self driving car algorithm

## Status
Reproduce Carla modular pipeline

## questions


## Tasks and plans
1. Carla installation and learning
  * Receive measurement data from server
  * Send control data to control vehicle
  * Define radar sensor
  * Reproduce Carla team modular pipeline.
2. Integrate perception, localization, path planning and control
  * Lane detection
  * Traffic Signs detection
  * Vehicles, pedestrian detection
  * Localization
  * Path planning
  * Vehicle control
  * Integrating
3. Customize Chinese city map
4. Verify multi-camera + radar solution feasibility
5. Evaluate self driving car algorithm

## Environment
* Ubuntu 16.04
* ROS
* Python 3.5
* Anaconda
* Tensorflow 1.4.0

## Resources
* [Carla github](https://github.com/carla-simulator/carla)
* [Carla document](http://carla.readthedocs.io/en/latest/)
* [Carla 0.7 baidu pan 链接: https://pan.baidu.com/s/1eSuBh5K 密码: dgqz](https://pan.baidu.com/s/1eSuBh5K)
* [Carla introduction zhihu](https://zhuanlan.zhihu.com/p/30979943)
* [Carla paper](http://proceedings.mlr.press/v78/dosovitskiy17a/dosovitskiy17a.pdf)
* [Carla tutorial](./doc/carla.md)
* [Udacity self driving car simulator](https://github.com/udacity/self-driving-car)
* [Airsim](https://github.com/Microsoft/AirSim)

## Roadmap
* Traffic lights filter if there are several detections.

Examples: if model detects two green lights from front camera images, there should be a pipeline to determine which light should be used.
* Vehicle dynamics simulation improvements
* Vehicle customization  

## Core contributors
The core contributors are a team including several Chinese Udacity self driving car Nanodegree graduates.

## Licenses
CARLA Self Driving Car Simulator in Chinese Traffic Scenes specific code is distributed under MIT License.

Related assets follows [CARLA Licenses](https://github.com/carla-simulator/carla)
